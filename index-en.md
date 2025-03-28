---
layout: default
title: English Posts
permalink: /en/
lang: en
---

# English Posts

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
