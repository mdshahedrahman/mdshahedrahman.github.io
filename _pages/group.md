---
layout: archive
title: "Gallery"
permalink: /group/
author_profile: false
body_class: homepage group-page
---

<p class="gallery-intro">Group photos and shared moments.</p>

{% assign years = site.data.gallery | group_by: 'year' %}
{% for year in years %}
<section class="gallery-year" aria-labelledby="gallery-{{ year.name }}">
  <h2 id="gallery-{{ year.name }}">{{ year.name }}</h2>
  <div class="gallery-grid">
    {% for photo in year.items %}
    <figure class="gallery-card">
      <a class="gallery-image{% if photo.fit == 'contain' %} gallery-image--contain{% endif %}" href="{{ photo.image | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-size photo: {{ photo.alt | escape }}">
        <img src="{{ photo.image | relative_url }}" alt="{{ photo.alt | escape }}" width="{{ photo.width }}" height="{{ photo.height }}" loading="lazy" decoding="async">
      </a>
      <figcaption>
        <time datetime="{{ photo.date }}">{{ photo.label }}</time>
        {% if photo.caption %}<p>{{ photo.caption | escape }}</p>{% endif %}
      </figcaption>
    </figure>
    {% endfor %}
  </div>
</section>
{% endfor %}
