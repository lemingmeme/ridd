---
layout: "default"
lang: "zh-CN"
title: "博客"
---

<ul>
  {% assign sorted_pages = site.pages | sort: "date" | reverse %}
  {% for page in sorted_pages %}
    {% if page.path contains 'zh-CN/posts/' %}
      <li>
        <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
        <span style="color: gray;"> - {{ page.date | date: "%-m-%-d-%Y" }}</span>
      </li>
    {% endif %}
  {% endfor %}
</ul>
