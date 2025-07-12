# BitzParser

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

BitzParserは、BitzLabsエコシステムにおいて、様々なテキストベースの言語を解析するための、再利用可能なコンポーネントとツールを提供するライブラリです。

## 主な機能

-   字句解析器(Lexer/Tokenizer)を実装するための基底クラスやヘルパー
-   再帰下降構文解析などの一般的な手法を実装するためのパーサー基盤
-   エラーハンドリングと報告のための共通メカニズム

## このライブラリの位置づけ

Markdownパーサーや、各DSLのパーサーを実装する`BitzDoc`, `BitzPlot`などのドメインライブラリは、この`BitzParser`が提供するツールを利用して効率的にパーサーを構築します。このライブラリは`BitzBuffer`に依存します。
