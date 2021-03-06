---
title: "トピックシェアリングとトピックピック"
emoji: ""
type: "idea"
topics: ["トピック指向","コミュニケーション","テキストコミュニケーション"]
published: true
---

![](/images/220613_204352.png)

# コンテキスト
- n人で1つの話題（トピック）について議論するシチュエーションを考える
    - 特にテキストで議論することを考える
    - 議論としては発散のみ、収束のみ、発散と収束、のすべてを想定する
- 通常は以下のような手段を使うと思う
    - Wikiにページをつくる
    - 同時編集可能なドキュメントをつくる

# Before

## トピックシェアリングとは
- n人で「1つのトピック」を仕上げること
- 従来のやり方であり、何も意識しなければ基本的にこれになる
- 議事録や議事メモといった会議の記録も基本的にこれになる

## デメリット
n人全員で1つのアウトプットをつくることに等しいため、たとえば以下に陥りやすい。

- そもそも成立しない（どこに何をどのように書いたらいいかがわからない）
    - そのため通常は **喋る会議を開催して、その議事録や議事メモを取るという形に落着する**
    - しかし会議は参加者全員のリソースを拘束するためよろしくない
- 一人以上がまとめ役に徹してしまい、議論に参加できない
- 遠慮や空気の読み合いが発生してしまい、生産的に議論できない
- 手を抜く人が発生しやすい
- 意見を書くメンバーが固定化しやすい
    - 喋るのが苦手な人が喋らなくなるように、書くのが苦手な人が書かなくなる

# After

## トピックピックとは
- 「1つのトピック」について、n人が各自意見をぶら下げること

## メリット
- トピックシェアリングのデメリットを打ち破れる
- 各自が各自の意見を書けばいいだけなので、意見が出やすい
- 各自が各自の意見を見ながら、さらに意見をふくらませられるので、議論の質が上がる
- 各自が各自のペースで書けるので、満足感が高い
    - 自分のペースで行えると開発体験(Developer Experience)が上がる（と思う）
    - いちいち会議を開催しなくても済む etc

## 書き方
- 識別子（名前やアイコン）を書き、その下に箇条書きでぶら下げれば良い
- 識別子については、
    - Scrapbox のようなツールであればアイコン記法がある
    - アイコン記法がない場合は普通に名前を書くか、愛用する絵文字を決めてそれを使う

### 例: ～～はA案とB案のどちらが良いか（絵文字を使った場合）
A案とB案については[こちら](ダミーです.md)を参照。

🐰

- Aがいいと思う
- ……

🦍

- これ考える余裕がないので任せます

🐢

- 経験者が多いのでBが無難
- ……

🐯

- 必要な知識が足りないので何も言えそうにないです……
- 勉強させてもらいまーす

## Q&A

### Q: 結論などはどうやってまとめればいいのか？
Ans: 意思決定者や担当者が決めてしまえば良い。

[「要はバランスおじさん」のまとめ](https://togetter.com/li/1402258) でも言われているが、情報を出し合えば自然な結論が出ることが多い。

それでも出なくてトレードオフを迫られる場合は、意思決定者や担当者（実際に手を動かす人）などが決めてしまえばいい。トレードオフに延々と悩んだり、宗教論争で平行線になっても仕方がないので、さっさと決める。

### Q: トピックピックに慣れるための良い練習方法はあるか？
Ans: 雑談をすること。

たとえば「好きな食べ物は何？」のような誰でも書けそうなネタを書く。

余談だが、（特に非同期テキストコミュニケーションが増える）リモートにおいては、雑談の代わりに **雑残（ざつだん）** が重要である。とにかく雑談的な内容をたくさん残して、誰でもいつでも好きにコメントできるようにする。そうすることで雑談に近い効果を得ることができる（と思う）。

### Q: 他の人に言及したい場合はどうすればいいか？
Ans: いくつかやり方がある。

#### 直接差し込む
🐯

- 必要な知識が足りないので何も言えそうにないです……
- 勉強させてもらいまーす
- 🐢色んな意見が欲しいので、知識足りなくてもいいしいいかげんでもいいから思ったことを率直に書いてほしい

#### 自分のエリアで返信する（メンション式）
🐢

- 経験者が多いのでBが無難
- ……
- 🐯さん
    - 色んな意見が欲しいので、知識足りなくてもいいしいいかげんでもいいから思ったことを率直に書いてほしい

🐯

- 必要な知識が足りないので何も言えそうにないです……
- 勉強させてもらいまーす

#### 自分のエリアで返信する（引用式）
🐢

- 経験者が多いのでBが無難
- ……
- > 必要な知識が足りないので何も言えそうにないです……
    - 色んな意見が欲しいので、知識足りなくてもいいしいいかげんでもいいから思ったことを率直に書いてほしい

🐯

- 必要な知識が足りないので何も言えそうにないです……
- 勉強させてもらいまーす

### Q: 速やかに結論を出さねばならないシチュエーションでも使えるのか？
Ans: ケースバイケース。

たとえば猶予が3時間くらいあるなら、「まずは1時間で各自トピックピックしてみよう」とすることができる。それで一通り発散させた後、残り2時間で収束していけばいい。

逆に「10分しかありません」というのなら、（従来どおり）その場で関係者を集めて口頭で高速でやり取りするしかないだろう。

### Q: トピックピックのピックって何？
Ans: Pick（刺す）という意味のつもり。

n人が、1つのトピックに自分の意見を刺す、というつもりで名付けた。あと「ピック」という響きが二回続くのが良いなと思って。

が、言葉の選び方を間違えたかもしれない。おかしかったらすみません。
