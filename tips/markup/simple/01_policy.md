# 「シンプルなHTMLマークアップ」 のための ポリシー

当資料では、これらをもとに コードパターン を掲げます。

* HTML/CSS など、【策定された規格・文法】 を遵守する
  * あくまで記事編集時点
* 【最低限のアクセシビリティ確保】 のため、次に掲げる条件を満たすようにする
  * マシンリーダブルである
    * ... マークアップ文書だけで企図が成立し、認識できる
    * ... 検索エンジン、支援技術（読み上げソフトや、代替入力デバイス）を円滑に利用できる
  * webブラウザなどでのレンダリング にかなっている
    * ... 規格にのっとっていても、レンダリングする環境が普及していないコードの利用は避ける
  * 利用者のハンディキャップ を考慮し、複数の方法・経路 が用意されている
    * ... ハンディキャップの例：
      * 目が見えない、視野が欠けている、色が識別できない
      * 動くものを目で追いきれない
      * 小さい表示を識別・判読できない
      * 画像を見られない、音を聞けない
      * 記憶ができない
      * マウスが使えない、携帯端末からアクセスしている
      * 指が1本しか使えない
      * 早い動きや、緻密な動きができない、指がぶれる
* 「意味・文書・文章・情報のマークアップ」 を重要視し、「見た目・装飾のマークアップ」 よりも優先する
  * ... マークアップ文書はプログラムのソースファイルではない
  * ... 「挙動している状態」であっても、「文書の意味、情報が通じないもの」は NG

## 記号・凡例

* `【isTemporary・やむなし＝】` ... 他に良策はあるものの、なんらかの事情で選ぶのも仕方ない項目 である事柄を示す
* `【isBad・非推奨＝】` ... お勧めできないこと、回避が望ましいこと である事柄を示す
* `【isInvalid・禁忌＝】` ... 利用できないこと、規格の遵守未達な項目、避けるべきこと である事柄を示す
