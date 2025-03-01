---
layout: default
title: Home
---

{{ site.description }}

[PyCon JP 2025 は2025年9月26日・27日に広島で開催されます](https://2025.pycon.jp/)

[**主催メンバー募集中**](https://forms.gle/7irqYKhZVj7AY7LfA)

<div class="image-center">
![写真 PyCon JP 2025 Chair!! nishimotz と書かれたスライド前で、黄色のスタッフTシャツを着て立っている]({{ site.baseurl }}/assets/images/54039787103_1aec5222f5_c.jpg)
</div>

## 記事

<ul class="list-none ml-0">
  {% for post in site.posts %}
    <li class="mb-4">
      <a href="{{ site.baseurl }}{{ post.url }}" class="block p-4 bg-white shadow hover:bg-gray-100 rounded">
        <span class="text-sm text-gray-500 mb-1">{{ post.date | date: "%Y-%m-%d" }}</span>
        <h3 class="text-lg font-semibold mt-0 mb-2">{{ post.title }}</h3>
      </a>
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
