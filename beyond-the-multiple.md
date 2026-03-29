---
title: Beyond the Multiple
permalink: /beyond-the-multiple/
---

{% for post in site.categories['Beyond the Multiple'] %}
<article>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
</article>
{% endfor %}
