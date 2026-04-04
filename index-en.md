---
layout: default
title: English Posts
permalink: /en/
lang: en
---

## English Resources

> **PyCon JP 2025 has ended** (held September 26-28, 2025). This site is an archive of the chair's daily reports.

[**PyCon JP 2025**](https://2025.pycon.jp/en)

> **PyCon JP 2026** will be held on August 21-22, 2026 at the International Conference Center Hiroshima. Staff volunteers welcome!

[**PyCon JP 2026 Official Site**](https://2026.pycon.jp/)

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.lang == "en" %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

[Back to Home]({{ site.baseurl }}/)
