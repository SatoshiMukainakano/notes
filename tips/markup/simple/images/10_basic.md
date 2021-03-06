# 「シンプルなHTMLマークアップ」 の 「画像」

## (0) まずはここ

[Webアクセシビリティ 逆引きガイドライン - 画像](https://weba11y.jp/know-how/guidelines/guidelines_index/#category06)

## (1) 基本

```
<img src="(uri)" width="幅" height="高さ" alt="代替テキスト" />
```

### 解説

* 「その画像を、代わりに `alt` 属性のテキストで置き換えたときに、意味意義情報が成立する」ようにする
  * ※このとき、「意味意義情報が成立する」ようなテキストがない（＝ `alt` 属性の内容が空で成立する）場合、その画像は「装飾のための画像」ともいえる*
* 原則的に `width`, `height` は指定するようにする
  * たとえ指定されていなくても、少なくとも画像のロード完了前後でレイアウトがずれないようにする

## (2) 「画像1点」に複数のリソースがある

```
<picture>
  <source srcset="(uri)" media="適用条件" />
  <source srcset="(uri)" media="適用条件" />
  <img src="(uri)" width="幅" height="高さ" alt="代替テキスト" />
</picture>
```

### 解説

* （1）項における解説も併せて参照のこと
  * 当項目の `img` でも同じように考える

## (番外) 装飾の性質をもった「画像」について

* まずは [Webアクセシビリティ 逆引きガイドライン - 装飾画像](https://weba11y.jp/know-how/guidelines/decorative-image/) を参照されたい
* 画像を使わずに成立する デザイン を検討されたい
* 画像を使わず、CSS で表現できる デザイン・コード を検討されたい
* 画像の受信をなるべく軽くすむよう 画像をユーザーフレンドリー に加工されたい
