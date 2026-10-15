# Preview the working website locally

Run these commands in the VS Code terminal, starting in `My_Website`:

```sh
cd site
export BUNDLE_GEMFILE="$PWD/Gemfile.local"
export BUNDLE_PATH="/private/tmp/shahed-website-gems"
export BUNDLE_USER_HOME="/private/tmp/shahed-bundler"
bundle install
bundle exec jekyll serve --config _config.yml,_config.local.yml --host 127.0.0.1 --port 4000 --destination /private/tmp/shahed-site-preview
```

Open **http://localhost:4000/** in your browser. Leave the terminal running; Jekyll rebuilds when source files change. Refresh the browser to see changes. Stop with **Control+C**. Restart after changing configuration files.

If the terminal is already inside `site/`, skip `cd site`. Repeat the exports when opening a new terminal. The dependencies and generated output are outside OneDrive. Temporary files can be cleared by macOS; rerun `bundle install` if needed.

`Gemfile.local` and its lockfile are shared by local preview and GitHub Actions deployment, using Ruby 4 and Jekyll 3.10. The original `Gemfile` is retained for reference; use `Gemfile.local` for builds. The local configuration uses local links and disables analytics. See [DEPLOYMENT.md](DEPLOYMENT.md) for publishing.

For a one-time build, replace the final command with:

```sh
bundle exec jekyll build --config _config.yml,_config.local.yml --destination /private/tmp/shahed-site-preview
```

## Where to edit

- `_pages/about.md`: About Me and Recent Updates, based on `../CV_Academic_Shahed.pdf`. Announcement months were not inferred where the CV only gives a year.
- `_sass/_homepage.scss`: homepage layout and blue colors.
- `_data/navigation.yml`: menu links.
- `files/CV_Academic_Shahed.pdf`: the downloadable CV copy.

Only `about.md` owns `/`. Biography has its own `/biography/` route; `/background/` redirects there. Obsolete template pages and sample collections have been removed. The macOS filename collisions were resolved by keeping the lowercase awards and skills pages and removing the old publication collection.

Keep `../master-site/` and `../master-site.bundle` unchanged.
