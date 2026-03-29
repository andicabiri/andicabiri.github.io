---
title: Beyond the Multiple
permalink: /beyond-the-multiple/
---

{% assign posts = site.categories['Beyond the Multiple'] | sort: 'date' %}
{% for post in posts %}
<article>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
</article>
{% endfor %}
