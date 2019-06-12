# アクセシビリティ - 工程・着眼点・素材ごとの早引き一覧 （HTML・CSS・script類


## HTML

### 全般的に・広範的に・各タグで細やかに

* [1.3.1 (A)] 機械でも可読な、情報、構造、関係性を保ったコードを書く
* [1.3.2 (A)] コンテンツにおいて「順序」が意味を持っている場合、読み上げさせてもその意味を損なわないように書く
* [1.3.2 (A)] 表示の順序とDOMの順序を一致させる
* [1.3.2 (A)] 文字間の空白、改行を、表示の整形に使わない
* [1.3.3 (A)] 形、大きさ、視覚的な位置、方向、音のような、感覚的な特徴だけに依存する誘導・利用方法は使わないようにする
* [1.4.1 (A)] 色に意味を持たせる場合、色が識別できない場合でも意味がつかめるようにする
* [1.4.1 (A)] 色が識別できなくても、機能を見つけ、利用することができるようにする
* [2.2.2 (A)] 情報更新を自動で行う箇所は、動きを止められるようにする
* [2.3.1 (A)] 「閃光」「点滅」は規定値以下にとどめる
* [3.2.3 (AA)] 共通のナビゲーションを、常に、相対的に同じ順序で出現させる
* [3.2.3 (AA)] 位置や、項目の順序が、ウェブページによって違うといった状況にしない
* [4.1.2 (A)] 支援技術との互換性を保つべく、name・role・valueを活用して、プログラムによる解釈ができるコードにする

### title

* [2.4.2 (A)] ウェブサイト全体で一意の内容で `<title>` で各ページの主題もしくは目的を説明する

### meta

* [2.2.1 (A)] クライアントサイドでの自動リダイレクト、情報更新のための自動更新は避ける
* [3.1.1 (A)] そのページがどの言語でできているか、文章を解析せずとも機械的に判別できるよう、コード上で明示する

### article / section / aside / div

* [2.1.1 (A)] キーストロークの特定のタイミングに依存させない or 代わりの方法で補う
* [2.1.2 (A)] フォーカスをコンポーネントに閉じ込めない or 閉じ込めても外せるようにする
* [2.1.2 (A)] コンポーネントに閉じ込めたフォーカスの外し方が標準的でない場合、方法を明示する
* [2.4.3 (A)] 意味・操作性を損なわない順序でフォーカスがあたるコードにする
* [2.4.1 (A)] ある程度の「情報のまとまり」ごとに見出しを充てる
* [2.4.1 (A)] そのページにある、「このページならでは」の情報を扱っているブロックへ、素早く移動できるようにする
* [2.4.6 (AA)] 使うなら、セクションの主題を的確に示してない「見出し」は使わない

### form

* [2.1.1 (A)] キーストロークの特定のタイミングに依存させない or 代わりの方法で補う
* [2.1.2 (A)] フォーカスをコンポーネントに閉じ込めない or 閉じ込めても外せるようにする
* [2.1.2 (A)] コンポーネントに閉じ込めたフォーカスの外し方が標準的でない場合、方法を明示する
* [2.2.1 (A)] 制限時間・タイミングで制限しない
* [2.4.3 (A)] 意味および操作性を損なわない順序でフォーカスがあたるようにする
* [2.4.6 (AA)] 目的が明確な「ラベル」を充てる
* [2.4.7 (AA)] フォーカス表示を無効にせず、必ず表示されるようにする
* [3.2.1 (A)] フォーカスを移しただけでコンテキストを変えないようにする
* [3.2.2 (A)] フォームの値を変えたり、フォーカスを充てたりしただけではコンテキストを変えないようにする
* [3.3.1 (A)] 具体的なメッセージテキストで、利用者がエラーに気が付け、利用者が何を誤っていたのか知ることができるようにする
* [3.3.2 (A)] フォームのコントロール に「ラベル」「説明」を補い、的確な利用を可能にする
* [3.3.3 (AA)] 利用者の認識したエラー箇所で、どうすれば解決となるか修正方法を提案する
* [3.3.4 (AA)] 利用者が「元の状態に戻すことのできない動作を実行する」ときのミスによる深刻な結果を回避するのを助ける
* [4.1.2 (A)] 支援技術との互換性を保つべく、name・role・valueを活用して、プログラムによる解釈ができるコードにする

### h1-6

* [2.4.1 (A)] ある程度の「情報のまとまり」ごとに見出しを充てる
* [2.4.1 (A)] そのページにある、「このページならでは」の情報を扱っているブロックへ、素早く移動できるようにする
* [2.4.6 (AA)] 使うなら、セクションの主題を的確に示してない「見出し」は使わない

### a / button

* [1.4.1 (A)] 色に意味を持たせる場合、色が識別できない場合でも意味がつかめるようにする
* [1.4.1 (A)] 色が識別できなくても、機能を見つけ、利用することができるようにする
* [2.4.3 (A)] 意味・操作性を損なわない順序でフォーカスがあたるコードにする
* [2.4.4 (A)] コンテキストを踏まえて、目的が明解なラベルを使う(※19)
* [2.4.6 (AA)] 充てるなら、インターフェイスコンポーネントの目的を示してない「ラベル」は充てない
* [2.4.7 (AA)] フォーカスが当たっているときは、そのことが識別できる程度に表示されるようにする
* [3.2.4 (AA)] 同じ機能をもつUIコンポーネントには、同じラベルを充てる
* [3.2.4 (AA)] 同じラベルが充てられていて、行先や目的が異なるようなリンクラベルにはしない
* [4.1.2 (A)] 支援技術との互換性を保つべく、name・role・valueを活用して、プログラムによる解釈ができるコードにする

### input / label / select / textarea

* [1.4.1 (A)] 色に意味を持たせる場合、色が識別できない場合でも意味がつかめるようにする
* [1.4.1 (A)] 色が識別できなくても、機能を見つけ、利用することができるようにする
* [2.4.3 (A)] 意味・操作性を損なわない順序でフォーカスがあたるコードにする
* [2.4.4 (A)] コンテキストを踏まえて、目的が明解なラベルを使う(※19)
* [2.4.6 (AA)] 充てるなら、インターフェイスコンポーネントの目的を示してない「ラベル」は充てない
* [2.4.7 (AA)] フォーカスが当たっているときは、そのことが識別できる程度に表示されるようにする
* [3.2.4 (AA)] 同じ機能をもつUIコンポーネントには、同じラベルを充てる
* [3.2.4 (AA)] 同じラベルが充てられていて、行先や目的が異なるようなリンクラベルにはしない
* [4.1.2 (A)] 支援技術との互換性を保つべく、name・role・valueを活用して、プログラムによる解釈ができるコードにする

### インライン画像

* [1.1.1 (A)] テキスト成分・情報成分として意味や価値のある内容をまとめたテキストを別に提供する
* [1.4.5 (AA)] 意図があって「画像化した文字」を使う場合でも、画像が見られない利用者に配慮したコードを補い、備える
* [3.1.2 (AA)] そのページがどの言語でできているか明示されていてもいなくても、複数の言語が使われているページでは、異なる言語ごとに識別できるようにする（※レベルA への適合であっても [3.1.1 (A)] との同時達成が強く推奨される）

### テキストを含むノード

* [1.3.3 (A)] コンテンツの説明で、形、大きさ、視覚的な位置、方向、音のような、感覚的な特徴だけに依存しないようにする
* [1.4.5 (AA)] 意図があって「画像化した文字」を使う場合でも、画像が見られない利用者に配慮したコードを補い、備える
* [3.1.2 (AA)] そのページがどの言語でできているか明示されていてもいなくても、複数の言語が使われているページでは、異なる言語ごとに識別できるようにする（※レベルA への適合であっても [3.1.1 (A)] との同時達成が強く推奨される）
* [3.3.1 (A)] エラーを示すメッセージテキストでは、利用者が何を誤っていたのか知ることができるように具体的に説明する

### audio / video / object / embed

* [1.1.1 (A)] 音声・動画などで示すコンテンツのうち、テキスト成分・情報成分として意味や価値のある内容をまとめたテキストを別添えで提供する
* [1.2.1 (A)] 再生したときに得られるものと同等の目的が果たせるテキストを提供する
* [1.2.2 (A)] 収録済メディアであれば、メディアに含まれているすべての収録済の音声に対して、キャプションを提供する
* [1.2.3 (A)]＋[1.2.5 (AA)] メディアが示す視覚的な情報へ、全盲または視覚障害のある利用者がアクセスできるようにする
* [1.4.2 (A)] 自動再生するメディアには、停止に関するコード・挙動も盛り込まれているか確認する
* [2.2.1 (A)] タイミングで制約をかけない or かけても回避できるメカニズムを備える

### onclick / ondblclick / onmousedown / onmouseup / onmouseover / onmouseout / onmousemove

* [2.1.1 (A)] キーボードだと機能が利用できないコード・記述・ハンドラは採用しない or キーボードで使えるように補う

### onfocus / onblur / onchange / oninput / onresize / onresize / onselect

* [3.2.1 (A)] 「フォーカスを充てただけでコンテキストを変える」は避ける

### 空白文字（改行、半角SP、タブ

* [1.3.2 (A)] 文字間の空白、改行を、表示の整形に使わない


## CSS

### 全体の表示

* [1.4.1 (A)] 色に意味を持たせる場合、色が識別できない場合でも意味がつかめるようにする
* [1.4.1 (A)] 色が識別できなくても、機能を見つけ、利用することができるようにする
* [1.4.4 (AA)] 200％に表示を拡大しても、テキスト、画像、コントロールの表示が欠けたり、切り取られたり、覆い隠されたりしないようにする

### 境界（border、shadowなど）

* [1.4.3 (AA)] 識別を促す場合は、背景との間で十分なコントラストをつけた配色にする

### テキストの表示

* [1.3.2 (A)] 文字間の空白、改行を、表示の整形に使わない
* [1.4.5 (AA)] 重要な意図があってテキストでは表現できない場合を除き、画像化した文字は使わない

### 画像の表示

* [1.1.1 (A)] 画像の中で、テキスト成分・情報成分として意味や価値のある内容をまとめたテキストを別に利用者に伝わるようにする
* [1.4.3 (AA)] テキストと背景に十分なコントラストをつけた配色にする

### 表示のON/OFF

* [2.4.7 (AA)] 操作可能なコンポーネントのフォーカス表示を無効にせず、必ず表示されるようにする

### 色使い

* [1.4.1 (A)] 色に意味を持たせる場合、色が識別できない場合でも意味がつかめるようにする
* [1.4.1 (A)] 色が識別できなくても、機能を見つけ、利用することができるようにする
* [1.4.3 (AA)] テキストと背景に十分なコントラストをつけた配色にする
