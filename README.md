# Pure JavaScript jQuery slideToggle

jQuery を抜けるために slideToggle を実装した。

1. CSS で opacity: 0, visibility: hidden にしておく
2. JS で高さを offsetHeight で測って 0 にしておく
3. -open というクラスで高さ以外のスタイルを制御する
4. 構成的には.toggle の下にコンテンツ(class 名はなんでもいい)状態にしておく
