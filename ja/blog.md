---
layout: "default"
lang: "ja"
title: "ブログ"
---

<ul>
  {% assign sorted_pages = site.pages | sort: "date" | reverse %}
  {% for page in sorted_pages %}
    {% if page.path contains 'ja/posts/' %}
      <li>
        <a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a>
        <span style="color: gray;"> - {{ page.date | date: "%-m-%-d-%Y" }}</span>
      </li>
    {% endif %}
  {% endfor %}
</ul>
