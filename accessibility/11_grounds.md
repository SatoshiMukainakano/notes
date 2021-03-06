# アクセシビリティ 関連 - 根拠・背景

## 根拠

### 「ゴール」を満たせないことで帯びる「バリア」

#### ブラウザやスクリーンに表示させない、もしくは モノクロ表示 で意味が通じなくなる

* 視覚に頼る利用者が、情報・機能・サービスを受けられない
* 色の識別ができない利用者が、情報・機能・サービスを受けられない
* 加齢、白内障などで、情報・機能・サービスを受けにくくなる
* 屋外などの光が強い状況で、表示を識別しにくくなる
* グレースケールでの印刷により、内容を識別しにくくなる
* 公共の場など、音の出せない状況（ヘッドフォンのバッテリー切れなど）で利用できない
* 母語でなかったり、耳が遠くなったりしたユーザは、音声の聞き取りを正しく行えない


#### 充分に広い視野が必要、もしくは 利用中のズームが無効

* 緻密なポインティングが必要になり、
* ロービジョンを負う利用者が、情報・機能・サービスを受けられない
* 加齢、老眼、緑内障などで、情報・機能・サービスを受けにくくなる


#### スクリーンリーダによる音声読み上げ、もしくは点字出力 で受け取れる内容は必要充分を満たせていない

* 聴覚に頼る利用者が、情報・機能・サービスを受けられない
* 画面に視線を向けられない状況で、情報・機能・サービスを受けられない


#### デバイスを動かさせることを強いる

* デバイスを固定する利用者が、情報・機能・サービスを受けにくくなる


#### 緻密なポインティングを必要とする

* 障害、加齢、怪我などで手指の動きに制約を持つ利用者が、情報・機能・サービスを受けられない


#### 「非・利き手の、小指1本だけ」しか使えない

* 障害、怪我などで使える手指に制約を持つ利用者が、情報・機能・サービスを受けられない
* 代わりになる支援技術などで、1本指での操作で利用できるようにされたい


### 「前提」の根拠

* 「いま使えてるんだから、それでいい」は、もちろん、それでいい
* 「いま使えてる」方法・器官が使えなくなっても、まだ【別の選択肢をもって操作できうるか】に着眼
* 「いま使えてる機能について、いまより使いやすくなるか（＝ユーザビリティ）」とは、基準が異なる
  * 「別の方法で使えるようになる」なら、「いま使ってる方法が よくなる・ならない」 は無関係
  * 「いま使ってる方法が 使えなくなる」 は、慎重に検討されたい
  * 参考） https://ferret-plus.com/1725
* 「障害者のための施策」と考えるのではなく、「今日使ってくださっていたユーザがハンディを背負っても明日のユーザのための施策」

### 利用者の条件整理について

* 下記資料「インクルーシブなペルソナ拡張」を参考とした
  * https://github.com/caztcha/Inclusive-Persona-Extension
  * 「ターゲットユーザー像をペルソナして定義しますが、プロジェクト内の暗黙の共通認識として、たいていの場合そのペルソナは健常者である」の一文にヒントを得た

### 対象の選定について

#### 対象にするコンテンツの条件

* 自社が自社で責任をもって提供している「機能」「情報」であるか
* 自社内で融通のきくコード領域であるか
  * 融通のきかないコンポーネントであっても、そのコンポーネントを採用する決定を下したのが自社なら、採用した責任は免れられない

#### 設定した基準について

* WCAG2.0（JIS X 8341-3:2016、ISO/IEC 40500:2012） について
  * JIS規格として公示されており、世界的にも同様に取り扱われている
  * 総務省の「[みんなの公共サイト 運用ガイドライン](http://www.soumu.go.jp/main_content/000439213.pdf)」でも、望ましい対応基準のよりどころに採用している
  * より周知性の得られるものを基準に採用し、ノウハウの往来を活発にするメリットに期待
* 「レベルA の完全準拠」について
  * WCAG策定陣が「必要最低限のもの」として設定している
  * 「これを満たせないもの」に一定のマイナス評価があり、「最低限の目標」としても採用しやすい
* 「レベルAA の完全準拠」について
  * WCAG策定陣が「公共のものとして達成が望まれるのもの」として設定している
  * サービスを利用するときに「ハンディ持ちを排除する」意図・必然性がないなら、このレベルも「ひとつの理想」として目指せる

#### 例外

* 事業そのものが違法でない限り、事業継続を脅かすのは 本末転倒
* 

#### 例外の例外

* 継続する「それ」が、一個人・いち利用者を「不法な侵犯の脅威」から守れない場合、それは「改善」が強く期待される


## 背景

### 国内

* アクセシビリティの策定・注目が進められてきたのは「ここ数年」のことではない
* webサイト・コンテンツを作る技術者として、「アクセシビリティのための技術」が認められる動機が増えている
  * 日本国内でも2013年に「障害者差別解消法」が制定され、2016年に施行された
    * https://www8.cao.go.jp/shougai/suishin/sabekai.html
  * 東京都下では個別に条例で、民間企業の対応義務を強化している
* 具体的に従うべき基準、違反すると罰則を伴う基準 は設定されていない
  * が、義務に反しているか否かで処分が設定されている

### 国外

* 国連で2006年に「障害者の権利に関する条約」が採択され、各国で条約署名が相次いでいる
  * https://www.mofa.go.jp/mofaj/fp/hr_ha/page22_002110.html
  * 日本国も署名していて、効力は発生している
  * 判決に損害賠償が伴った判例もある（国内外問わず

