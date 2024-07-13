# commit-hook-check

GUIからコミットフックの動作を確認するためのリポジトリ

https://blog.yuzu441.com/posts/2024-07-13-vscode-commit-hook/

## how to use

1. このリポジトリをクローンする
2. 依存パッケージをインストール

```sh
npm i
```

3. [記事](https://blog.yuzu441.com/posts/2024-07-13-vscode-commit-hook/)に沿って`husky/init.sh`の設定を行う
4. `src/index.js`を編集する（フォーマット後に元のコードと差分がある必要があります）
5. vscodeやsourcetreeなどからコミットする
