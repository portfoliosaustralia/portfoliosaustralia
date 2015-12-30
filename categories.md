---
layout: page
title: categories
---

The pages related to site categories are linked, below.

<h3>Terminology</h3>
 <ul>
 {% assign sorted_posts = (site.categories.['terminology'] | sort: 'title') %}
{% for post in sorted_posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
