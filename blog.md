---
layout: default
title: Every Other Epoch
permalink: /blog.html
---

## Every Other Epoch

* * *

Passes over what I'm reading, writing, and getting wrong — mostly on generalization,
feature learning, and what models actually rely on.

{% if site.posts.size > 0 %}
<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%-d %B %Y" }}</time>
    {% if post.excerpt %}
    <p class="post-excerpt">{{ post.excerpt | strip_html | truncatewords: 32 }}</p>
    {% endif %}
  </li>
  {% endfor %}
</ul>
{% else %}

*First post coming soon.*

{% endif %}


[ [Back to homepage] ](./)
