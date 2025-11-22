---
title: "All Tags"
layout: page
permalink: /tags/
---

<div class="tags-cloud">
{% assign sorted_tags = site.tags | sort %}
{% for tag in sorted_tags %}
  {% assign tag_name = tag[0] %}
  {% assign tag_posts = tag[1] %}
  <a href="/tag/{{ tag_name | slugify }}/" class="tag-link" data-count="{{ tag_posts.size }}">
    {{ tag_name }} ({{ tag_posts.size }})
  </a>
{% endfor %}
</div>