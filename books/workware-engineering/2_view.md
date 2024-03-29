---
title: ワークウェアを眺める
---

本章ではワークウェアの例を紹介しつつ、ワークウェアを俯瞰するための枠組み――いくつかの性質や分類も取り上げます。これらによってワークウェアを眺めることで、さらに理解を深めていただくことを意図しています。


★利用レベル、権威レベルで見出しつくった方がいい
★レベル1とかも見出し一つつくって解説するか？


# ワークウェアの分類
例を挙げていく前に、まずはワークウェアを分類する切り口をいくつか述べます。

前章と同樣、小難しい説明も交えますが、あくまでワークウェア全体を俯瞰するために整理したものにすぎないため、無理して理解する必要はありません。ただ、これらの分類を頭に入れておくと、この先ワークウェアを扱う際にも「これはこの辺の話だな」「今はここの段階だな」と把握できて便利です。ワークウェア・エンジニアリングは概念を相手にするので、ともすると現在地を見失いがちです。自分が今どのあたりに居るのかを捉えるために、こういう切り口を知っておくと便利なのです。

## 利用レベル
ワークウェアは「どのように扱うものか」という切り口で分けることができます。

| レベル | 分類名 | 動詞で | 必要な能力 |
| ---- | ---- | ---- | ---- | 
| 1 | Name      | 捉える | 語彙力、教養、連想などが必要 |
| 2 | Principle | 生かす | 応用が必要 |
| 3 | Protocol  | まわす   | 能動的使用が必要 |
| 4 | Tool      | 使う   | 適応的使用が必要 |

### 各レベルの解説
レベル1、Name は **言及するワークウェア** です。命名、あだ名、たとえなどが当てはまります。名付けることで（その名前が指す概念の）理解が容易になったり、言及してコミュニケーションを行ったりできます。

レベル2、Principle は **心がけるワークウェア** です。原理、原則、格言、モットー、心構え、傾向、心理といったものがこれにあたります。道具は使うものですが、心がけるワークウェアを使うのはかんたんではありません。というのも、然るべきときに忘れず思い浮かべて、かつ何らかの適切な行動を（たいていはその場ですぐに）起こさなければならないからです。このような行いをワークウェア・エンジニアリングでは **応用** と呼びます。

レベル3、Protocol は **まわす（回す）ワークウェア** です。プロセス、メソッド、手順、プラクティス、ルールなどが当てはまります。まわすワークウェアを使うためには、それについて理解した上で、自らそのとおりに頭手足を動かす必要があります。また、どれだけ厳密に従うかはワークウェアと状況次第です。たとえば手順には厳密なものもあればいいかげんなものもありますし、厳密な手順であっても状況が許せばサボったり端折ったりすることもあるでしょう。いずれにせよ、基本的には面倒くさい営みになります。このような行いを、能動的に行動して使っていくということで **能動的使用** と呼びます。

レベル4、Tool は **使うワークウェア** です。ソフトウェア、装置、器具など「道具」として思い浮かべるものはこれにあたります。たとえば何らかのメソッドを誰でもかんたんにこなせるようにしたWebサービスはレベル4です。使うワークウェアを使うには、それが想定するとおりに使うことです。まわすワークウェアほどの融通は利きませんが、使いさえすればいいので小難しい理解や手続きが少ない傾向にあります。これをその想定に適応する形で使っていくということで **適応的使用** と呼びます。

### ワークウェアの例
各レベルごとにいくつか例を挙げていきます。例自体は無数にありますので、端的に数個ほどピックアップします。

レベル1、言及するワークウェアとして、たとえば以下があります。

- 蛙化現象
    - [Z世代が選ぶ流行語ランキング](https://www.tokyo-np.co.jp/article/264372) にも入った言葉で、好意を抱いている相手への熱が急速に冷めること
    - 元ネタはグリム童話の「かえるの王さま」とされる（人間になったりカエルになったりする王子への姫さまの態度）
    - 「名前のついていない」あるある現象に、既存作品の作品名や人物名などを充てる形のネーミングです
- 礼儀1.0
    - 自分を犠牲にして相手のために時間を使うというメンタルモデル
    - 元ネタは[GOROmanさんのツイート](https://twitter.com/GOROman/status/984872963655680000)と思われる
    - 版管理における版の付け方、特に性質がガラリと一新されるメジャーなアップデートは1.x → 2.x と一の位を更新していきますが、ここから取ってきていると思われます（Web2.0などこの手のネーミングもよく見かけます）
- [コミュニケーション1.0](https://scrapbox.io/workware/%E3%82%B3%E3%83%9F%E3%83%A5%E3%83%8B%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B31.0)
    - 筆者のワークウェアで、常に特定の相手を想定するというコミュニケーションのメンタルモデル
    - これも上記と同じネーミングを使って名付けました

例を見てもわかるとおり、言及するワークウェアはたいてい「ある程度の人が薄々勘付いていること」が対象になります。もっと言えばあるある～と共感できるほど「よく知られていて」、かつ知られているということは「わかりやすい」ものであるとも言えます。このような性質を **あるある性** と呼ばせてください。

あるある性の高いものは言及する機会が多いです、なのに名前がついてないので、じゃあつけようというわけですね。SNS やメディアから身内まで、この手の営みは至るところで発生します。きわめて自然で身近な営みです。そういう意味では、ワークウェア・エンジニアリングは、この自然な営みをもっと真面目に積極的に使っていくことを勧めるものだ、とも言えるでしょう。

次にレベル2、心がけるワークウェアの例をいくつか挙げます。

- 早寝早起き
    - 早く寝ることと、早く起きること（特に「深夜まで起きない」「早朝に起きる」「この二つを両立できる睡眠時間」のニュアンスがあると思います）
    - 健康的な生活をおくる原則として言わずと知れた言葉ですが、これを「使う」のは難しいでしょう
    - 早く寝るためには？早く起きるためには？自分の体質は？など、考えること・やることはたくさんあります
- VUCA
    - 先の読めない世の中を表現した言葉で、Volatility（変動性）、Uncertainty（不確実性）、Complexity（複雑性）、Ambiguity（曖昧性）の略
    - これも同樣に「使う」のは難しいと思います
    - 先が読めないから何？どうすればいいの？組織はともかく個人にできることなんてあるの？など疑問は尽きません
- 返報性の原理
    - 施しを受けた際にお返しをしなければならないと感じる心理
    - これも「使う」となるとピンと来ませんが、参考にすることはできそうです
    - 試食（タダで食べちゃったし、ちょっとなら買おうか……）やドア・イン・ザ・フェイス（最初断っちゃったからその程度ならまあ契約してもいいかな……）など商業的にはよく使われます



原理、原則、格言、モットー、心構え、傾向、心理




### Q&A
いくつか紛らわしい話題を Q&A の形でまとめます。

- Q: プラクティスやルールはレベル2ではないですか？レベル3なのですか？
    - Ans: はい、レベル3です
    - 上記の定義だとレベル2（心がけるワークウェア）なのかレベル3（まわすワークウェア）なのかわかりづらい、というよりどちらにも入りそうですが、レベル2は「原理原則や格言くらいのもの」と捉えてください。
    - 表現に必要な情報量も目安になります。レベル2は、一言二言で簡潔に表現できるのが特徴です（内容が難しくて前提知識が多く要求されることはあります）。一方、レベル3は用語を多数導入したりn個の列挙をしたりと情報量が増えます。
- Q: レベル1（言及するワークウェア）とレベル2（心がけるワークウェア）の違いがわかりません
    - レベル1はあくまで「名付けただけ」です。
    - なので、「まだ名前のついてない "心がけるもの"」や「まだ名前のついてない "まわすもの"」があったとして、それに名前がついたら、それはレベル1の言及するワークウェアとなります。ただし、前述したように、あるある性が高いものを対象とするのも特徴です。すでに多数の人に共感されるものだからこそ、名前をつけるだけで共有できるようになります。この「名前をつけるだけ」といういちばん手間の少ない段階がレベル1です。
    - 一方、レベル2は、何らかの研究や実践を行っている人（人達）が扱っているものを、その人達自身が名前をつけて、かつ一言二言で言えるようにうまく蒸留したというニュアンスが強いです。あるある性が高いとは限りませんし、たいていは高くありません。高くないから言及するワークウェアがつくられることも期待できず、したがって熱意のある専門家や物好きが時間をかけてつくりあげていくことになります。
    - ★この辺の区別難しいなー🐰  ことわざのような歴史の重みがあるやつもここなんだが。あるいは現象傾向特徴性質をレベル1、にするのが良い気がする……うん、たぶんこれや🐰🐰 いったん寝かせる
    - ...
- Q: 世の中に存在するソフトウェアなどの道具はすべてワークウェアですか？
    - Ans: いいえ
    - ワークウェアは「ある単一の何か」を概念として表現したものです。その単一の概念を愚直にツール化したものはワークウェアと言えます。
    - しかし、一般的に（ソフトウェア含め）道具と呼ばれるものは、複数の（下手すれば無数の）ワークウェアを実装していることが多いです。あるいは、そもそも実装していない（ワークウェアを意識せずに実装している）ことはもっと多いです。

## 権威レベル
前章にて「権威」という言葉を取り上げましたが、この権威の程度（権威性の程度）でも分類できます。

| レベル | 分類名 | 解説 |
| ---- | ---- | ---- |
| 1 | ソロ | 自分が扱っているだけ |
| 2 | ファミリー | 一人以上に通じて扱ってもらえた |
| 3 | クラスター | 特定の集団単位で当たり前に扱われている |
| 4 | コミュニティ | 権威の発露。特定の界隈では当たり前に使われている、経営者やアーリーアダプターその他意識の高い人は知っている |
| 5 | スタンダード | 権威の浸透。標準と呼ばれるレベルで浸透している、ビジネスの文脈では一般的に扱われている |

### 各レベルの解説
レベル1、ソロはワークウェアを自分一人で扱っている段階です。単につくっただけなのもそうですし、自分のために自分でつくって使い続けているのもそうです。自分にしか通じないので、 **権威性は無いに等しい** でしょう。しかし、ワークウェアではあるので、他者に伝えることはできます。

レベル2、ファミリーは他者一人以上に通じて扱ってもらえている段階です。一人でも数人でも十数人でも構いませんが、とにかく自分以外の他者に通じたこと、そして何らかの行動をしてもらえた（一度でも使ってもらえた、ノートにメモされた、他の人と話すときに取り上げたもらった、本人に何らかのフィードバックをくれた等）が必要です。通じただけでは意味がありません。新規事業時によく登場する[リーンスタートアップの MVP](ref#12) の概念もそうですが、「理解しました」「良さそうですね」といった感想に価値はありません。実際にお金を出してもらえたかどうかがすべてです。ワークウェアの場合は「扱ってもらえた（何らかの行動をしてもらえた）かどうか」です。もっとも、実際に他者の行動を観測できるとは限りませんが、目安としてそこまで必要だという点は意識してください。このレベル2でもまだまだ権威は無いに等しいですが、他者に通じたことで **ありそう（権威性は増やせそう）** という感触は持てます。

レベル3、クラスターはチームやプロジェクトといった集団単位で当たり前に使われている段階です。チーム独自の取り組みは世の中、数え切れないほどあると思いますが、そういったものはレベル3のワークウェアである事が多いです。実際、メンバーに伝えるためにある程度の言語化も行われているからです。一方で、言語化が行われず OJT や実践を通じて各自が悟っていく、あるいは出来る人を見て盗んでいくといった形での洗練・継承もありふれており、こちらはワークウェアとは言えません。このようなものを言語化して捉えられると、一気にレベル3のワークウェアとなります。いずれにせよ、レベル3のワークウェアは、特定の集団では通用しているため **権威性は少しはある** と言えます。ただし、これをこの先どこまで広げられるかはわかりません。新規事業ネタにも市場規模などボリューム（稼げる限界）がありますが、ワークウェアにも同樣、権威性がどこまで広がるかというボリューム、**権威ボリューム** があります。レベル3は、いわばその入口に立っているようなものです。

レベル4、コミュニティは界隈の単位で当たり前に使われている、ないしは知られている段階です。大半のワークウェアはここまでのボリュームしかありません。具体的には「学術的にはしっかり証明されたが実践的にはさほど価値がない」とか「実用的であると十分知れ渡ったがニッチすぎて活用範囲が限られている」などです。ここまでくると、そのワークウェアでご飯を食べることができることもあります。また、界隈以外の、意識の高い人に伝わることもあります。汎用性もそれなりにあるため、複数の界隈に刺さるポテンシャルもあります。 **権威性はそれなりに高い** と言えるでしょう。

レベル5、スタンダードは標準と呼ばれるレベルで浸透している段階です。といってもビジネスの文脈で、と補足しておきます。この文脈とは離れた存在――たとえば子供や学生を含む被扶養者、自営業、ボランティア、その他特殊な仕事や立場の人などへの浸透は想定していません。このワークウェアにもいくつか種類がありますが、少なくとも知名度の高さを備えています。逆を言えば、有名人の言葉がバズったり、何らかの意図や政治等によりメディアによってブームに仕立て上げられたりしただけでもここに至ることがあります。 **権威性はかなり高い** と言えますが、その中身には注意が必要です。知名度に振り切っていて実用性や学術性が乏しいこともあります。

### ワークウェアの例
「心理的安全性」はご存知でしょうか。本書での解説は割愛しますが、おそらく読者の大半はご存知かと思います。この心理的安全性は権威性がかなり高いです。というのも、まず論文が存在しており、[大元は 1999 年のもの](ref#5)で、これを参照した論文も多数存在します。学術的に研究されてきたというわけです。加えて、[2015 年には Google による啓蒙](ref#6)が開始され、巷にも広く知られたのはここからだと思われます。その Google も単にバズワード的に使ったのではなく、きちんと専用チームをつくって研究を重ねています。実践的にも裏打ちされているのですね。学術的にも実践的にも検証されており、かつ現在ではビジネスの領域ではほぼ誰もが知っているほどの言葉となっています。権威性はかなり高いと言えるでしょう。レベルで言えば少なくとも 4（コミュニティ）ですし、5（スタンダード）といわれてもしっくり来ます。

次に「GTD(Getting Things Done)」を取り上げます。これもご存知の方が多いかもしれません。仕事術の中ではトップを争うほど有名なものだと思います。[有償のメソッドですが、20 年以上の歴史](ref#7)があり、国内（の一部界隈）でブームになったこともあります。学術性はありませんが、実践的な裏打ちと知名度は高く、権威性はそれなりに高いと言えるでしょう。レベルで言えば 4（コミュニティ）でしょうか。

さらに「[バレットジャーナル](ref#8)」と「[PARAメソッド](ref#9)」を取り上げます。これらは仕事術やライフハックの界隈を見ている方ならご存知だと思います。前者は手帳術、後者は情報管理術とでも言えますが、どちらも GTD に触発されており、人生管理全般を行えるほどのポテンシャルもあります。GTD ほどの権威性はありませんが、（特に前者のバレットジャーナルは）開発者がそれでご飯を食べることができ（ていると思われ）、界隈と呼べるほどのコミュニティも出来ています。権威性はそこそこあると言えるでしょう。レベルでいえば 3（クラスター）です。バレットジャーナルは 4（コミュニティ）に近いかもしれません。少なくとも国内では PARA メソッドよりは知られていると思います。

最後に「[JECTsメソッド](https://scrapbox.io/workware/JECTs%E3%83%A1%E3%82%BD%E3%83%83%E3%83%89)」を取り上げます。これをご存知の方はいないと思います。というのも、筆者がつくったワークウェアにすぎないからです。GTD、バレットジャーナル、PARAメソッドなど人生管理術レベルのメソッドの、情報の扱い方の本質を端的にまとめたものですが、学術的にも実践的にも検証はされていないですし、知名度や利用例もありません。権威性は無いに等しいでしょう。レベルで言えば 1（ソロ）だと思います。[Zenn に書いた記事](https://zenn.dev/sta/articles/2022-07-04-jects) にコメントがついている、という意味では 2（ファミリー）と言えるかもしれません。

### どこを目指すか
最悪個人でもいい。

身近な人や周囲な人を助けることもできる（ファミリー）。あるいは個人的な依頼に応える形でワークウェアをつくるのもこれ（現状このようなあり方はほぼないと思いますが、筆者は今後ありえると思います。たとえばワークウェア・エンジニアなる専門職にお願いするなど）。

組織内改善がしたければひとまずレベル3。ただしこのレベルのワークウェアであっても、外に向けて発信していけばビジネスに繋がります。サイボウズの例？うまくいけば売り物にもできるでしょう（サイボウズでいうとメソッド事業）。

ビジネスにしたいならレベル4。ここまでくると権威性をどうやって担保するかが重要。学術的に検証していくか、宣伝や啓蒙を重ねて知名度をあげていくか。Googleのような体力のある組織だと両方できます。

レベル5。

### Q&A


### .
これもレベル化したい
 lv1 自分がつくっただけ
 lv2 一人以上に通じて扱ってもらえた 筆者の「トピック指向」や「コミュニケーション1.0」はここ
 lv3 本格的な道具（チーム以上の集団単位で当たり前に扱われている） gitlabのcoffee chatやサイボウズのザツダン、ソニックガーデンのザッソウなどはここ
 lv4 巷である程度の知名度や実績がある（権威の発露） 経営者その他意識高い人、界隈の人（タスク管理に関するネタならタスク管理界隈）、アーリーアダプターその他マニアやオタクは知っている
 lv5 標準のレベルで浸透している（権威の浸透） ビジネスパーソンなら割と誰でも知っている
 GTD®はlv4。心理的安全性はlv5かlv5よりの4でもいいかも。「TODOリスト」はlv5。
あくまでもワークウェアのレベルであることに注意。
ワークウェアを実装したソフトウェアのレベルではない。たとえば筆者がつくった「シングルエントランス」はせいぜいlv2だが、シングルエントランスが使われているTwitterは（このレベル体系で言えば）lv5だろう


あるいは一章の言葉使うなら権威性。権威レベル。……これでいいか？

- ※
    - 1 分類名は検討中です。

# ワークウェアの例
ここも色んな見せ方をしますって感じで。で、抽象的な見せ方の一つにMPRSが入る。

## ワークウェアは幅広く包含する(MPRS)
ワークウェアは、たとえば以下のようなものも包含します。

- M
    - メソッド(Method)
    - モデル(Model)
    - マインド(Mind)
    - マトリクス(Matrix)
- P
    - プロセス(Process)
    - プラクティス(Practice)
    - プリンシプル(Principle)
    - パターン(Pattern)
- R
    - ルール(Rule)
    - ロール(Role)
    - ランク(Rank)
    - レート(Rate)
- S
    - ストラクチャー(Structure)
    - ストラテジー(Strategy)
    - スタンダード(Standard)
    - スタンス(Stance)

~~名前つけたい。MPRS？ちょっと響き微妙だなぁ、4ってのも。5個にしたい。あるいはMをもう一つ追加して4→4~~ 4x4おｋ

System や Theory はでかすぎるから含めない（含めてもいいが筆者個人は微妙かな）、も。

# ワークウェアの例

どう紹介していこうか……？
 既存のもの/筆者がつくったもの
 レベル軸で一つずつ
 MPRSで一つずつ

