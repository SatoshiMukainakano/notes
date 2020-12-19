# 「シンプルなマークアップ」 の 「意味レイアウト」

## (1) 基本

`body` タグの中を走査したとき、次に掲げるタグが、「一発で」かつ「ただ一つ」ヒットするようにする

```
<header>webサイトのヘッダ。コンテンツ本体に対する「前談」を示す</header>
<main>そのページにおける、「コンテンツ本体」そのもの</main>
<footer>webサイトのフッタ。コンテンツ本体に対する「補足情報」を示す</footer>
```

### 解説

* 「そのページの【主旨】は何か」を探したときに `main` タグを探すことで一発で探し当てられる
  * もちろん、 `main` タグの中に「主旨に含まれないもの」は入っていないことが望ましい
* 「そのページの 主旨 を伝える上での 【前談】 は何か」 を探したときに一発で探し当てられる
  * このとき、前談には 主に以下のようなものが含められる
    * そのページを備えている webサイト のタイトル
    * そのwebサイトを備えている 著者・企業、もしくはその 著作品・webサイトのタイトル・ロゴ
    * そのページにたどりつくためのナビゲーション類
  * ちなみに `section` `article` などの セクショニング系のタグ（後述） の中にある `header` タグは、意味が変わってしまうので注意
* 「そのページの 主旨 に付随する 【補足情報】 は何か」 を探したときに一発で探し当てられる
  * このとき、補足情報には 主に以下のようなものが含められる
    * そのページ・記事の主旨 そのものの著作権情報
    * そのコンテンツの プライバシー情報
    * 前談 にあるものと並ぶ ナビゲーション類
  * ちなみに `section` `article` などの セクショニング系のタグ（後述） の中にある `footer` タグは、意味が変わってしまうので注意
* 以下のものは 主旨・前談・補足情報 に含めない
  * 検索フォーム
  * ナビゲーション
  * `aside` タグでくくることが望ましい情報
    * 主旨 に対する 「余談」
    * 主旨 に対して 間接的な関係しかない 部分
    * 広告
    * コンテンツのスポンサー に関する情報
    * webページ において 主旨部 に並ぶ サイドバー・別カラム
    * お問い合わせ先、連絡先
    * webサイトに関する情報

### 「セクショニング系のタグ」

以下に列挙するタグの中にある `header` `footer` タグは 【そうでないタグとは意味が異なり】、「そのwebコンテンツ」における 前談・補足情報 としてはとらえられない

* `article`
* `main`
* `section`
* `aside`
* `nav`

## (2) タグが意図するところで使えないとき

<div role="banner">headerタグの代わり</div>
<div role="main">そのページにおける、mainタグの代わり</div>
<div role="contentinfo">footerタグの代わり</div>

### 解説

* このとき、
  * `role="banner"` を帯びたタグは、`body` 以外のどのセクションにも属していない
  * `role="contentinfo"` を帯びたタグは、`body` 以外のどのセクションにも属していない