---
layout: default
title: Home
---

PyCon JP 2025 座長 [@nishimotz](https://github.com/nishimotz) が個人として公開する日報です。

{{ site.description }}

<ul style="list-style-type: none;" class="ml-0">
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.date | date: "%Y年%m月%d日"}} : {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## おまえ誰よ

<ul style="list-style-type: none;" class="ml-0">
  <li>
    [@nishimotz](https://github.com/nishimotz)
  </li>
  <li>
    [about me](https://d.nishimotz.com/aboutme)
  </li>
</ul>

すこしずつ情報を追加していきます。
