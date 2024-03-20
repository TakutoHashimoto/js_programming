# 第3章 変数の書き方
## `let` を使った変数の書き方
* JavaScriptでは、以下のように変数を宣言する。
    ```js
    let 変数名 = 値;
    ```

> [!TIP]
> VSCodeでスクリプトを書いて実行しようとすると `zsh: command not found: node` と出てくるので、その場合は `brew install node` でNode.jsをインストールする。

> [!TIP]
> MacのターミナルでJSのスクリプトを実行するときは、`node <ファイルパス>` と入力することで実行できる。

* 初期値を設定しない変数を表示すると、`undefined` と表示される。
```js
let a;
console.log(a);
// => undefined
```

## `const` を使った変数の書き方
`let` のほかに `const` を使った変数の宣言方法がある。

|  | `let` | `const` |
| -- | -- | -- |
| 初期値ありの変数宣言 | o | o |
| 再代入 | o | x |
| 初期値なしの変数宣言 | o | x |
