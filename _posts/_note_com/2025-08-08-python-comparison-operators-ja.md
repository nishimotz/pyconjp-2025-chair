---
title: Python で a ＜ b ＜ c はどう書くの？ 【PyCon JP 2025】
layout: default
permalink: /note_com/python-comparison-operators-ja.html
published: false
---

答え: a [PyCon JP 2025](https://2025.pycon.jp/) 座長の西本です。
前回、こんな記事を書きました。[https://note.com/24motz/n/n15b9cc1de0ae](https://note.com/24motz/n/n15b9cc1de0ae)あのあとで気になって AI に質問したら、Pythonの「a, b = b, a」のように、複数の変数の値を一行で同時に交換（多重代入）できる構文を持つ言語は、他にも存在します。
ということで Ruby, JavaScript, Perl などの言語が挙がりました。
そうですね。
たしかに Python だけの特長ではありませんね。
じゃあ、こんなのはどうでしょう？**a これ、数学の教科書でよく見る「aはbより小さくて、bはcより小さい」という記号ですよね？**Pythonでは、なんとこの数学の記号をそのまま使うことができるんです！**数学の記号がそのまま使えるって、どういうこと？例えば、あなたが「テストの点数が50点より高くて、80点より低いかどうか」を調べたいとします。
他の多くのプログラミング言語だと、こんな風に書くことが多いです。
点数 > 50 **かつ** 点数 でも、Pythonでは、もっとシンプルに、**数学の書き方と同じように**書けます。
点数 = 60

if 50 よけいな記号がなくて、左から右に、だんだん大きくなっていて、読みやすいですね。
PyCon JP 2025 で、Pythonの「もっとすごい！」を知ろう！学校でPythonを学ぶのは、プログラミングの世界への**素晴らしい第一歩**です。
そして、PyCon JP 2025は、その一歩を踏み出したあなたが、さらに深くPythonの魅力を探るための場所です。
他のプログラミング言語ではa あるいはa のように書くところで、Python は a こういうことが、実は Python の「言語そのものの設計」から生まれていることを、そしてそれが実際のプロの現場でどう使われているのかを、PyCon JPで感じてみませんか？学校では教えてくれなかった、Pythonの「もっとすごい！」部分を、ぜひ見つけに来てください。
PyCon JP 2025 は、**2025年9月末に広島で開催**されます。
あなたもこの「Pythonの魔法」を体験しに、広島へ来ませんか？PyCon JP 2025 登壇者、スポンサーを募集中！PyCon JP 2025 は 2025年9月26日-28日に**広島国際会議場**で開催します。
最終日は開発スプリントです。[https://note.com/24motz/n/n4f6801257221](https://note.com/24motz/n/n4f6801257221)**今年はじめて東京以外の場所で開催される PyCon JP** ですが、現在、登壇者（プロポーザル）を募集しています。
締切は6月29日です。
まだまだ先だと思ってませんか？あっという間ですよ！今年は、**ポスターも、コミュニティポスターも、同じ締切**なので、ご注意ください！[https://pretalx.com/pycon-jp-2025/cfp](https://pretalx.com/pycon-jp-2025/cfp)[https://pyconjp.blogspot.com/2025/05/pyconjp-2025-call-for-proposals.html](https://pyconjp.blogspot.com/2025/05/pyconjp-2025-call-for-proposals.html)**スポンサーも募集しています。
私たちが作りたい PyCon JP を実現するために、ぜひご支援をお願いします。**ご不明なことがあれば、資料に記載されたお問い合わせ先に、お気軽にご相談ください！[https://pyconjp.blogspot.com/2025/06/pyconjp2025-sponsorship-result-ja.html](https://pyconjp.blogspot.com/2025/06/pyconjp2025-sponsorship-result-ja.html)[https://note.com/24motz/n/n8828bcad687a](https://note.com/24motz/n/n8828bcad687a)
