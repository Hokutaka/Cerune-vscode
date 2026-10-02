# Cerune Language Support

[日本語](README.md)

VS Code language support for Cerune (`.ceru`).

## Features

- `.ceru` language registration
- TextMate syntax highlighting
- `//` line comments
- bracket and quote auto-closing
- brace-based indentation
- basic Cerune snippets
- highlighting for keywords, primitive types, literals, built-ins, declarations, function calls, enum variants, and field access

The syntax definition follows Cerune's current lexer and language reference.

## Try it locally

1. Open this folder in VS Code.
2. Press `F5`.
3. In the Extension Development Host, open `examples/syntax-sample.ceru`.

No build step or `npm install` is required.

## Before publishing

Update `publisher` in `package.json` to the VS Code Marketplace Publisher ID you want to use.
