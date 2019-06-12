# アクセシビリティ 関連 - 基本方針

## 前提： ユーザの利用条件付けについて

* 何よりまず、利用に必要な「条件」を整理されたい
  * 可能な限り、無条件で利用できるのが望ましい
  * 正当な理由なく「健常者による利用」を前提にすることはできない
    * 一例として、「障害者を差別する行為」には、法令・都条例に照らし合わせるとリスクと問題が生じる
      * 法令・都条例、制度などは最新のものを確認されたい
  * だからといって、無条件に全員を利用できるようにすることも現実的ではない
* その「条件」を満たせない方向けの補助・代案を別途、検討されたい


### 参考： 条件になりえるものの一例

* 視覚障害をもっていても使える or 使えない
  * 例） 全盲、ロービジョン
* 色覚特性をもっていても使える or 使えない
  * 例） P型、D型、T型、A型
* 聴覚障害をもっていても使える or 使えない
  * 例） 音が聴こえない、聴こえにくい
* 運動障害をもっていても使える or 使えない
  * 例） マウスのクリック、画面のタップができない、発話できない、など
  * 例） 補助デバイスに頼る必要がある
    * PCのキーボード、マウススティック、ボタン、音声認識ソフト、視線入力装置 など
  * 例） デバイスの持ち替えが難しい
* 認知・学習障害をもっていても使える or 使えない
  * 例） 外的な刺激により集中が妨げられる
* 高齢でも使える or 使えない
  * 例） 精緻なポインティングができない
  * 例） 老眼、耳が遠い、情報の認知や記憶が難しい
  * 例） 思い込みで判断する
* 場所を問わない or 問う
  * 例） 限られた空間でしか利用できない、設備に条件が伴う


### 備考

* 当事者が利用に十分なアクション・アウトプットが行えない場合、代理・介添えの方が利用するなどの方策も考えられる


## 方針： 対象とするコンテンツ

* （適宜、選定されたい）

## 方針： 対象に設定するガイドライン

* 次のガイドラインを採用する
  * WCAG2.0（JIS X 8341-3:2016、ISO/IEC 40500:2012）
    * レベルA を完全準拠
    * レベルAA を完全準拠
      * ただし、動画・音声メディアにおいては レベルA適合 までにとどめる（※禁止する意図はなく、ボーダー下げる狙い）
    * レベルAAA も認識に入れる

## 例外

ただし、後述する「例外の例外」を除き、以下のいずれかに該当するものは対象から免れられる

* 自社内にコードを編集する権限がないもの
  * 「権限がない」とは、
    * 主管が自社外にあり、自社外の都合で、コードを改変されうるもの
    * 自社内の都合で、好きに、自由に、柔軟に、構成と値を変えられる権限が 【常ではない】 もの
  * 例）
    * 広告部品 （外部から配信されていて、配信元にのみコードを編集する権限がある
    * SAP領域 （何を配信したいか、を外部に切り分けている
    * 利用者・情報ソースの提供者から直接入力された、改変できない「コード」「記事」「画像」「文字列」の類
      * ユーザによる投稿
      * アウトソースによる記事入稿
* リリースされたのが 2015年内 か、それより古いもの
* 改変すると事業継続の脅威となりえて、他の解決方法も見いだせないもの

## 例外の例外

これら「例外の例外」は、前述の「例外」に含まれているものであっても、対象を免れられない

* 【個人情報】 の 表示・編集・消去 に関わる画面
* 利用者の 【金融】 に関する 手続き・変更・キャンセル・解約・取り消し に関わる画面
* 利用者が 【放置すると法令順守を達成できない】 性質を帯びている画面
* 関連省庁から指導を受け、【改善を命令されたもの】 や 【改善を約束したもの】

## 業務上の拘束力、強制力、優先度、罰則

* 当ガイドラインに反しても、ペナルティは課さない
* 部として、もしくは事業要件としての対応は、各事案で検討されたい
* 参考とするまでとする
