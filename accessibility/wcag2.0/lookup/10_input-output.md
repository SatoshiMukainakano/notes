# アクセシビリティ - 開発工程ごとの早引き一覧 （入出力


## 入力

### マウス・スタイラスペン

* ピクセル単位での操作を求めない
* [2.1.1 (A)] マウスがなくても使えるようにする

### キーボード

* [1.4.2 (A)] 自動で動き始めるものを「止める」メカニズムを入れる
* [2.1.1 (A)] 全機能を操作・利用できるようにする
* [2.1.2 (A)] フォーカスの外し方が標準的なキーでない場合は、方法を明示・通知する
* [2.2.2 (A)] 動いてるものを「止める」止めるメカニズムを入れる
* [2.4.3 (A)] フォーカスの充てる順序は、意味・コンテキストに準じている
* [2.4.7 (AA)] 充てられているフォーカスは、かならず識別できるように表示させる
* [3.2.3 (AA)] 位置、項目の順序は、「ページによって異なる」ようにはしない

### 入力に至るまででの制約

* [2.1.1 (A)] 特定のタイミングに依存させない
* [2.2.1 (A)] 制限時間・タイミングで制限しない
* [3.3.4 (AA)] 利用者が「元の状態に戻すことのできない動作を実行する」ときのミスによる深刻な結果を回避するのを助ける


## 出力（デバイス・メディアごとに

### モニター・スクリーン全般

* [1.4.4 (AA)] 200％に拡大しても、テキスト、画像、コントロールの表示が欠けたり、切り取られたり、覆い隠されたりしないようにする

### 画像素材（静止画

* [1.1.1 (A)] テキスト成分・情報成分として意味や価値のある内容をまとめたテキストを提供する
* [1.4.1 (A)] 色が識別できなくても利用・識別できるようにする
* [1.4.3 (AA)] テキストと背景に十分なコントラストをつける
* [1.4.5 (AA)] テキストで表現できない場合を除いて、画像化した文字は使わない
* [1.4.5 (AA)] 画像化した文字を使ったら、画像が見られない利用者向けのコードを補い、備える

### 音声素材（映像ある・なし関わらず

* [1.1.1 (A)] テキスト成分・情報成分として意味や価値のある内容をまとめたテキストを提供する
* [1.2.1 (A)] 再生したときに得られるものと同等の目的が果たせるテキストを提供する
* [1.4.2 (A)] 自動で動き始めるものには「止める」メカニズムを入れる
* [1.4.2 (A)] デバイス本体の音量レベルに影響を与えずに音量レベルを調整できるメカニズムを入れる
* [2.2.1 (A)] 制限時間・タイミングで制限しない
* [2.2.2 (A)] 止めるメカニズムを入れる

### 動画素材、アニメーションする部品

* [1.1.1 (A)] テキスト成分・情報成分として意味や価値のある内容をまとめたテキストを提供する
* [1.2.1 (A)] 再生したときに得られるものと同等の目的が果たせるテキストを提供する
* [1.2.2 (A)] キャプションを入れる
* [1.2.3 (A)] 全盲または視覚障害のある利用者でも情報へアクセスできるようにする
* [1.2.4 (AA)] リアルタイム動画であれば、リアルタイムでキャプションを提供する
* [1.2.5 (AA)] 映像情報が持っている、必要とする情報を「音声解説」ですべて補う
* [1.4.2 (A)] 自動で動き始めるものには「止める」メカニズムを入れる
* [2.2.1 (A)] 制限時間・タイミングで制限しない
* [2.2.2 (A)] 止めるメカニズムを入れる

### 自動で動き始めるもの（：再生、アニメ、スクロール、自動更新、時限リダイレクト

* [1.4.2 (A)] 止めるメカニズムを入れる
* [2.2.2 (A)] 止めるメカニズムを入れる

