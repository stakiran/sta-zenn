---
title: "プレーンテキストで定期タスクを扱うための「定義・生成パターン」"
emoji: ""
type: "idea"
topics: ["タスク管理"]
published: false
---

# TODO
- まずは false のまま articles/ にアップしてデプロイ画面でプレビュー
- publish前にファイル名先頭に日付つける
    - slugは12文字以上である必要があるため日付文字列で稼がないと自然な名前(特に短い名前)をつけれない
- 必要なら emoji と topics をつける
- いけそうなら true

# 1
![](/images/220615_141451.png)

定期タスクの定義。
繰り返し行うタスク。例を拡充させる。自覚してないだけでよくある。
きりみんさんの記事取り上げる。todoist。

一方、タスク管理はプレーンテキストで行なっている人が多いのではないか
markdown などで雑に書けるのでなんだかんだ強い。
しかしこれでは日付情報を扱うのが面倒くさい。毎週月曜日と金曜日だけ、みたいな仕込みがしづらい。
howmのようなアイデア（日付文字列つきの行を書いておくと当日になるにつれて自動的に浮かび上がってくる）もある。
[howm: Hitori Otegaru Wiki Modoki](https://howm.osdn.jp/index-j.html)

この記事で提案するのはもう一つのやり方。

実装としてtodaros。
https://github.com/stakiran/todaros
