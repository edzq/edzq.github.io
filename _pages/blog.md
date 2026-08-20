---
layout: writing
title: "Writing"
permalink: /blog/
redirect_from:
  - /year-archive/
  - /wordpress/blog-posts/
---

Notes on research, papers I am reading, and things I have had to figure out the hard way.

{% assign written_year = 'none' %}
{% for post in site.posts %}
  {% assign year = post.date | date: '%Y' %}
  {% if year != written_year %}
    {% unless forloop.first %}</ul>{% endunless %}
<h2 id="{{ year }}">{{ year }}</h2>
<ul class="postlist">
    {% assign written_year = year %}
  {% endif %}
  <li>
    <span class="d">{{ post.date | date: "%B %-d" }}</span>
    <span class="t"><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></span>
    {% if post.excerpt %}<div class="x">{{ post.excerpt | strip_html | truncate: 220 }}</div>{% endif %}
    {% if post.tags.size > 0 %}<div class="tags">{% for tag in post.tags %}<span>{{ tag }}</span>{% endfor %}</div>{% endif %}
  </li>
{% endfor %}
</ul>
