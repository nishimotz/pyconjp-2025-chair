---
layout: default
title: チーム別記事一覧
permalink: /teams/
---

# チーム別記事一覧

## 研修会資料

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.team == 'training' %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## プログラムチーム

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.url contains 'program-team' or post.team == 'program' %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## スポンサーチーム

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.url contains 'sponsor-team' or post.team == 'sponsor' %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## 広報チーム

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.url contains 'pr-team' or post.team == 'pr' %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## 参加者管理チーム

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.url contains 'attendee-management-team' or post.team == 'attendee-management' %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## 会場チーム

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.url contains 'venue-team' or post.team == 'venue' %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## 少年とママの会話

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.team == 'conversation' %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## 全般

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.team == 'general' %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## 座長

<ul class="list-none ml-0">
  {% for post in site.posts %}
    {% if post.team == 'chair' %}
      <li class="mb-4">
        <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
          <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
          <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

[トップページに戻る]({{ site.baseurl }}/)
