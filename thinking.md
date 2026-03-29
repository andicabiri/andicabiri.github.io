---
title: Thinking
permalink: /thinking/
---

{% for post in site.categories['Thinking'] %}
<article>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
</article>
{% endfor %}
