# Publish the updated website

The active repository is `mdshahedrahman/mdshahedrahman.github.io`, branch `master`.
The website address is https://mdshahedrahman.github.io/.
Push only the `site/` repository; the workspace backups and reference websites stay local.

## First deployment

1. In GitHub, open the repository **Settings → Pages**. Under **Build and deployment → Source**, choose **GitHub Actions**. This replaces the previous branch-based build with the checked workflow.
2. In your terminal, authenticate with the repository owner account:

   ```sh
   gh auth login --hostname github.com --web --git-protocol https
   gh auth setup-git
   ```

   Choose the `mdshahedrahman` account. If another account is active, run `gh auth switch --user mdshahedrahman` after login.
3. From `My_Website/site`, push the prepared commit:

   ```sh
   git push origin master
   ```

4. In the repository **Actions** tab, open **Deploy updated website to GitHub Pages**. Both build and deploy must succeed before the new site is live. Open https://mdshahedrahman.github.io/ and refresh the browser.

The workflow builds a fresh `_site` directory using `_config.yml` and the locked `Gemfile.local` dependencies. It uploads and deploys a complete replacement, so retired HTML pages are not retained. The current navigation and linked supporting CV pages remain available. The old source is preserved in Git history and the local master backup; no force push or history deletion is needed.

## Later updates

From `site/`, preview your changes, then:

```sh
git add -A
git commit -m "Update website content"
git push origin master
```

## Production build before publishing

With the environment exports from `LOCAL_PREVIEW.md` set:

```sh
JEKYLL_ENV=production bundle exec jekyll build --config _config.yml --destination /private/tmp/shahed-production-ready
```

Do not include `_config.local.yml` in a production build.
