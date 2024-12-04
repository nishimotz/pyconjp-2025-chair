---
layout: default
title: Home
---

PyCon JP 2025 座長 [@nishimotz](https://github.com/nishimotz) が個人として公開する日報です。

{{ site.description }}

[主催メンバー募集を開始しました。](https://pyconjp.blogspot.com/2024/12/call-for-organizing-members-ja.html)

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
    <a href="https://github.com/nishimotz">GitHub @nishimotz</a>
  </li>
  <li>
    <a href="https://d.nishimotz.com/aboutme">about me</a>
  </li>
</ul>

## リポジトリ

[pyconjp-2025-chair](https://github.com/nishimotz/pyconjp-2025-chair)

このサイトの更新履歴などをご確認ください。
