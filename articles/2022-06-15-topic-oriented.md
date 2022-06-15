---
title: "トピック指向"
emoji: "✍"
type: "idea"
topics: ["コミュニケーション","会議","トピック指向"]
published: true
---

# トピック指向とは
書き込み先を **トピック（話題）** の単位でつくり、そこにその話題に関することを書き込んでいくこと。

## メリット
- プログラミングでいう分割（モジュール化やクラス化や関数化）の恩恵を、テキストにも持ち込める
- 非同期コミュニケーションを促進しやすい
    - 話題Tに書き込みたい人が、書き込みたい時にTのページにアクセスすればいい
    - 用がない人はTを見なければいいので邪魔にならない
- 「今は（ここは）何の話題について話しているか」を意識する機会が増えるため、脱線が減り、生産性が上がる
- 脱線しやすく、色んなネタを書きやすい
    - 脱線したければ新たにページをつくればいい
- コミュニケーションを促進しやすい
    - たとえば「好きな食べ物」というページをつくって、皆で書き込みあう、といったこともできる

## 実現方法
フロー型（Wikiやファイル配置）を実現できるツールであれば何でも可能。

以下に例を上げる。

- Scrapbox
    - 2022/06/15 現時点で最も良い
- GitHub Discussions
    - 悪くはないが、ページ間の関連付け（リンク）がちょっと弱い
- GitHub Wiki
    - 悪くはないが、ページ間の関連付け（リンク）がちょっと弱い
        - `[]()` で囲めばいけるので、Discussions よりはやりやすいか
- Box Notes
    - ブラウザだけで同時編集できるのが強いが、動作が重い
    - ページ間リンクも弱い
- ※esa.io、Qiita:Team、Dropbox Paper など他にも色んなツールがあると思う

また共有フォルダにファイルを置くようなスタイルであっても適用はできる。

## トピック指向の使い時
色々あるが、いくつか例を上げる。

### 普段のコミュニケーション
チーム（あるいはもうちょっと大きな組織単位）で Wiki を持っている場合、普段から色んなネタを書きこんでいると思う。

ここにトピック指向を持ち込むことができる。日々の議事メモや日報週報、雑談や TIPS から提案まで、何でも書き込みやすくなるだろう。

### プロジェクトの情報置き場
Wiki、ファイル、GitHub のリポジトリなど、プロジェクトに関する情報を一箇所にまとめて置いている例は多いだろう。

ここにもトピック指向を持ち込める。話題単位で情報を置くことで、より扱いやすくなるだろう。

### 会議
一般的に会議は皆で集まって口頭で話し合い、議事メモを書く。しかしこれは原始的なやり方である。同期的であるため拘束が強いし、日程調整の負担もあるし、口頭なので一度に一人しか喋れないといった制約もある。

会議にもトピック指向を持ち込むことができる。たとえば「2022/06/15 定例」ページをつくり、ここに「Aについて」「Bについて」といったページをさらにつくる（議題ごとにページをつくる）。そして、みんなや議題ページにあらかじめ書き込んでおく。こうすると議題ごとの議論を非同期に行うことができ、会議開催するまでもなく結論が出てしまうことも多い。それでも解決しなければ、2022/06/15 の定例のときに口頭で話し合えば良い。

参考: [トピックシェアリングとトピックピック](https://zenn.dev/sta/articles/2022-06-13-topic-pick)。議題ページに各自の意見を書く場合は、トピックピックが良いだろう。

### 個人のメモ
個人で備忘録や日記などメモを取っている方もいらっしゃると思う。

ここにもトピック指向を持ち込める。たとえば Python について日々学んでいる場合、python.md に全部まとめて書くのではなく、「pythonでunittestを書く時に使うテンプレート.md」とか「pythonで日付時刻を扱うスニペット.md」といったトピックで分けてつくるのがトピック指向である。こうすればファイル名検索で探しやすくなって便利である。

## トピック指向を行うのに必要なこと
- 参加者全員が自由に書き込めること
    - たとえばページの新規追加もできること
- 何でも書き込んでもいい雰囲気であること
    - たとえば雑談的なページをつくってもいい（「好きな食べ物」、「行ったことのある観光地」、「エディタは何派？」）
- 1日1h、できれば数時間以上は自由に読む・書くができるゆとりがあること
    - たとえば日中ミーティングづくし、のような慌ただしさだとこれができない
    - 書くことや考えることがメインになるので、ある程度の時間的精神的ゆとりが必要
- 少人数であること
    - まずは気心知れた数人、新人とメンターの二人、普段のチーム内など小さな範囲が良い

## Q: DITAのトピック指向のこと？
Ans: そうです（それも含みます）。

DITA という文書作成規格(XML) にもトピック指向という言葉がある。曰く、

> 1つの目的を達成するために必要十分な情報を提供する、タイトルと本文から成る情報の単位

とのことで、「汎用的な文章部品」をつくって組み合わせることで本をつくるコンセプトとなっている。たとえば「吉良野すた」という自己紹介文章を部品化しておけば、書籍B1でも書籍B2でも使い回すことができる。プログラミングでも汎用的な処理はライブラリの形で整備・共有されるが、これの文章版と言えるだろう。

さて、本ページにおけるトピック指向という概念は、この DITA のトピック指向も含む。

参考: [ブック指向からトピック指向へ](https://dita-jp.org/webhelp-feedback/about_dita/from_book_to_map.html)、[トピックとは](https://dita-jp.org/webhelp-feedback/about_dita/whatis_topic.html)

# 例

## 日記の例
日記エリアをつくって時系列にぶら下げるのではなく、話題ごとにエリアをつくって話題ごとに時系列にぶら下げる。

### Before: 今までのやり方（時系列指向）
diary.md

```
# 2022/06/15
- Aは今日も難しかった
- Cを始めた

# 2022/06/14
- Aは～～だった
- Bは～～だった
```

### After: トピック指向
A.md

```
# 2022/06/15
- 今日も難しかった

# 2022/06/14
- ～～だった
```

B.md

```
# 2022/06/14
- ～～だった
```

C.md

```
# 2022/06/15
- 始めた
```

## Wikiの例
大きなページに色んな話題を書き込むのではなく、話題は何でもページ化してそっちに書き込む。

※文法は GitLab Wiki を想定する（≒Markdown）

### Before: 毎週の定例会議の議事メモを書く場合
ページ「定例会議」

```
# 2022/06/14
- 今週の一言
    - Aさん: ……
    - Bさん: ……
- オフィスの移転について
- ……

# 2022/06/07
- 今週の一言
    - Aさん: ……
    - Bさん: ……
- 書籍の購入について
    - ……
- ……
```

### After: トピック指向
ページ「定例会議」

```
# 2022/06/14
- 今週の一言
    - Aさん: ……
    - Bさん: ……
- [オフィスの移転について](オフィスの移転について)
- ……

# 2022/06/07
- 今週の一言
    - Aさん: ……
    - Bさん: ……
- [2022年度書籍購入](2022年度書籍購入)
- ……
```

ページ「オフィスの移転について」

```
……
```

ページ「2022年度書籍購入」

```
……
```

※今週の一言も別ページにしてもいいかもしれない。ここでは「定例会議ページからシームレスに流し読みできるから」という理由であえてそのままにしている。

## チャットにおいて実現している例
[Zulip](https://zulip.com/) はトピック指向と言える。

このチャットツールは、投稿前に必ずトピックを指定する（or 新規する）必要がある。他のチャットのように「とりあえずこのチャンネルに投げるか」といったことができず、必ず何らかの話題を指定して投稿するような動線になっている。

## おわりに
トピック指向の概要、メリット、例、導入時のコツなどを紹介した。

この概念は Scrapbox のヘビーユーザー達によって実践されてきたものを、筆者の言葉で説明したものである。よって、可能ならば Scrapbox を使うのが良い。Scrapbox については、拙作だが [Scrapboxing(スクラップボクシング)](https://www.amazon.co.jp/gp/product/B09YLFQZ29) という電子書籍も書いたので、よろしければぜひ。