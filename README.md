# Cerune Language Support

[English](README.en.md)

Cerune（`.ceru`）向けの VS Code 言語拡張です。

## 対応機能

- `.ceru` ファイルの言語登録
- TextMate grammar によるシンタックスハイライト
- `//` 行コメント
- 括弧・引用符の自動補完
- `{ ... }` に合わせたインデント
- Cerune 向けの基本 snippets
- キーワード、プリミティブ型、リテラル、組み込み関数、宣言、関数呼び出し、enum variant、フィールドアクセスのハイライト

シンタックス定義は、Cerune 本体の現在の lexer と言語リファレンスに合わせています。

## ローカルで試す

1. このフォルダを VS Code で開きます。
2. `F5` を押します。
3. 起動した Extension Development Host で `examples/syntax-sample.ceru` を開きます。

ビルドや `npm install` は不要です。

## 公開前に

`package.json` の `publisher` を、使用する VS Code Marketplace の Publisher ID に変更してください。
