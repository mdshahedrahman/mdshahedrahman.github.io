---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
body_class: homepage
---

Explore my research, academic background, and professional work.

- [About Me]({{ '/' | relative_url }})
{% for item in site.data.navigation.main %}
- [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}

The [XML sitemap]({{ '/sitemap.xml' | relative_url }}) is available for search engines.
