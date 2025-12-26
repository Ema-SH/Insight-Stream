---
layout: category
title: Insights / 觀點
category: insights
permalink: /insights/
---
<h1>Insights</h1>

<ul>
{% for post in site.categories.insights %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span class="post-date">
      {{ post.date | date: "%B %-d, %Y" }}
    </span>
  </li>
{% endfor %}
</ul>
