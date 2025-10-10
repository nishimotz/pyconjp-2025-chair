---
title: Pythonの禅
layout: default
permalink: /zen-of-python-ja.html
team: chair
---

PyCon JP 2025 座長 [@nishimotz](https://d.nishimotz.com/aboutme) が個人として公開する日報です。

[English version]({{ site.baseurl }}/zen-of-python-en.html)

[PyCon JP 2025](https://2025.pycon.jp/) は9月26日〜28日に広島国際会議場で開催されました。皆様のご参加、ご支援に感謝します。

## Pythonの禅とは

開催準備の意思決定やチーム運営にあたって、私はしばしば「Pythonの禅（The Zen of Python）」に立ち返っていました。これは Python の設計思想を簡潔に表したアフォリズム集で、`python -m this` で表示でき、公式ドキュメントにも引用されています。

この記事では、そのエッセンスをイベント運営にどう活かすかという観点で整理します。

### The Zen of Python（原文 / Tim Peters）

> The Zen of Python, by Tim Peters
>
> Beautiful is better than ugly.
> Explicit is better than implicit.
> Simple is better than complex.
> Complex is better than complicated.
> Flat is better than nested.
> Sparse is better than dense.
> Readability counts.
> Special cases aren't special enough to break the rules.
> Although practicality beats purity.
> Errors should never pass silently.
> Unless explicitly silenced.
> In the face of ambiguity, refuse the temptation to guess.
> There should be one-- and preferably only one --obvious way to do it.
> Although that way may not be obvious at first unless you're Dutch.
> Now is better than never.
> Although never is often better than *right* now.
> If the implementation is hard to explain, it's a bad idea.
> If the implementation is easy to explain, it may be a good idea.
> Namespaces are one honking great idea -- let's do more of those!

## 運営にどう効くか

### 美は醜よりもよい（Beautiful is better than ugly）

- 今回、ロゴやウェブサイトの美しさにこだわることができたのは、嬉しい成果でした。
- もっといろいろな場面で私たちは「美しさ」にこだわれたはずです。

### 明示は暗黙に勝る（Explicit is better than implicit）

- コミュニケーションを過剰なくらい明示的に行うことは大切で、私も繰り返しそうお願いしましたが、私自身もお願いを受けることがありました。
- 直前のミーティングで、主催メンバーの不安度を11段階で開示してもらう工夫をしたら、興味深い結果になりました。つまり、主催メンバーの経験が豊富であればあるほど、不安度は低かったのです。
- 参加者や発表者に対する明示的な情報提供も、多すぎることはありません。
- 座長がブログを書くことも、明示的なコミュニケーションの一環でした。
- 当日の主催メンバーのコミュニケーションで、リアルタイムな情報が足りない、という指摘がありました。

### 単純は複雑に勝る（Simple is better than complex）

- 参加者用 WiFi の自前での運用を諦めたことは、サービスとしては不十分でしたが、妥当な判断だったと考えています。
- 参加者管理について、チケット枠の設計などが複雑だという指摘がありました。
- 会場の使い方はシンプルであることに超したことはありません。

### 複雑でも入り組んでいない方がよい（Complex is better than complicated）

- MCの負担軽減などの観点から、英語トラックの部屋を揃えるなど、複雑であっても運用を入り組ませない工夫をしました。

### 平坦はネストに勝る（Flat is better than nested）

- チーム編成、組織はもっとフラットにできたかもしれません。
- 準備の早い時期から多くの主催メンバーが集まることは難しく、その場合は、より長期間フラットな組織のまま活動を続ける手はあったと思います。判断に迷いはありましたが、自信がなかったため、前例を踏襲して約6カ月前にチームを立ち上げました。
- 会場の使い方としては、地下2階でほぼ完結するように使ったつもりでしたが、主催メンバーは地下1階や1階との位置関係で混乱しがちでした。

### 疎は密に勝る（Sparse is better than dense）

- 参加者数が多すぎなかったことが幸いして、会場はゆとりを持って使えました。ベビーカーの参加者が印象に残りました。
- パーティ会場はやや密になりました。
- 座長の時間的な余裕がもっとあればよかったのですが。もしかしたら座長の仕事は開催の2年くらい前から始めるべきかもしれません。

### 可読性は重要（Readability counts）

- 視覚に障害のある参加者が、事前にウェブサイトで多くの予習ができたと言ってくれたのはよかったことです。
- 英語での情報提供は努力しましたが、むしろ日本語の情報やコンテンツが不足気味だった可能性もあります。
- No Photo ストラップが通常ストラップとあまり区別しにくかったのは反省点です。
- 参加者に向けた会場案内の不足は懸念していましたが実現できませんでした。

### 例外は規則を破るほど特別ではない（Special cases aren't special enough to break the rules）

- 開催地が変わっても、基本的な運営のルールを変える必要はなかったと思います。
- 例外を減らそうという内部の議論はありました。運営の透明性に寄与しているはずです。

### 実用は純粋性に勝る（Although practicality beats purity）

- 予算や人手の制約はどうしてもあり、貫けなかった「純粋な思い」もありました。

### エラーを黙って通してはならない（Errors should never pass silently）

- 問い合わせ/チケット/メールのトリアージがうまくいかなかった。みんなに努力してもらい、支えてもらってなんとか乗り切りました。
- 主催メンバーがうまく活動できていない状況の把握に努めていました。うまくいかなかったとしても、不満や後悔のないように努めました。
- 座長自身の困難を支えてもらえる座長チームの存在は大きかったです。

### 明示的に黙らせる場合を除き（Unless explicitly silenced）

- 主催メンバー内での CoC 違反の懸念には、迅速に対応してもらいました。
- 主催メンバー内、および、コミュニティにおいて、大きな問題が起こらずにイベントを終えられたことに、感謝しています。

### 曖昧さに直面したら推測の誘惑を退けよ（In the face of ambiguity, refuse the temptation to guess）

- 小麦アレルギーの情報提供の要望がありました。その人が公式パーティの参加者かどうかわからなかったのですが、パーティ会場でも確認して情報を提供しました（料理の配慮はできませんでした）。
- 食事等の配慮で、事前に申し出がなかったことについては情報提供していません（諦めました）。

### やり方は一つ（できれば唯一の）明白なものが望ましい（There should be one—and preferably only one—obvious way to do it）

- 参加申し込み、問い合わせ、支払いなどの基本導線を統一しました。
- 招待講演などの人に不必要な手順を踏ませてしまったとは思います。
- 主催メンバーの仕事のやり方も、特に支払いに関しては統一したマニュアルに従ってもらっていました（まだ続いています）。

### ただし最初は明白でないかもしれない（Although that way may not be obvious at first unless you're Dutch）

- 主催メンバーへの仕事のやり方の説明、新規参加者に向けた情報提供などは、もっと具体的にできたと思います。

### 今は決してやらないよりよい（Now is better than never）

- 下書きを早く出し、フィードバックを受ける文化を目指しました。
- 「しくみで不安を克服する」がキーワードだと気づきました。

### ただし今すぐよりやらない方がよい場合もある（Although never is often better than right now）

- 行動規範に関するアクションは慎重に行うように主催メンバーに周知しました。

### 実装が説明しづらいなら悪いアイデア（If the implementation is hard to explain, it's a bad idea）

- ミーティングやレビューで「説明困難」を検知したら、話を止めて見直すように促しました。
- 未経験の主催メンバーのモヤモヤを形にするのには時間がかかったことは事実です。
- 「ダリア1」部屋のハッシュタグが「…2」になっていたのは、わかりにくかったと思われます。

### 実装が説明しやすいなら良いアイデアかもしれない（If the implementation is easy to explain, it may be a good idea）

- シンプルな説明で合意が高速に生まれる案を優先しました。
- 100日前に100日チャレンジのキーノートを告知する。合宿で FastAPI の勉強会を行う。説明がしやすい提案が歓迎されて、実行されたことを嬉しく思います。

### 名前空間は素晴らしいアイデアだ、もっと使おう（Namespaces are one honking great idea — let's do more of those!）

- 基本的には PyCon JP で引き継がれてきた Google ドキュメントや Slack や Jira の運用を踏襲しました。
- 主催メンバーとの英語でのコミュニケーションはずっと課題でしたが、結果的に `prj-international` という英語専用のチャンネルを作りました。
- ずっと使われてきた `random` チャンネルではなく `2025-random` というチャンネルをあえて作り、最終的には「継続的自己紹介」が目的であると位置づけました。

## おわりに

The Zen of Python は、ソフトウェア開発に限らない「Pythonコミュニティらしさ」のための知恵ではないか、と気づいたのは、私が座長をやって学んだことのひとつでした。

参考：The Zen of Python（`import this`、または Python 公式ドキュメントを参照）

## 更新履歴

- 2025-10-10: 初版公開
