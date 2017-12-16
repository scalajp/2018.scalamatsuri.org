---
name: Loic Knuchel
title: "ミューテーション解析は良いテストの品質測定の決定打、かな？"
length: 40
audience: Beginner
language: English
twitter: loicknuchel
github: loicknuchel
icon: https://avatars0.githubusercontent.com/u/653009?s=460&v=4
organization: Software engineer at Criteo
tags:
  - Tools
suggestions:
  - Scalaのコードのテストを改善したい人
---
私達は全部にテスト書いている(本当に？)。けど、テストが有益なのかどうやって分かるのかな？

- テストの数が多いから？違う。たくさんのテストは、アプリケーションが正しく動くことを保証してはくれない。
- コードのカバレッジの高さ？違う違う。いいけど、まだ足りない。

私達が本当に必要だったものは、テストが本当に問題(TDDのテストは、何らかのテストを成功する前には *必ず* 失敗する)を見つけてくれるかどうかだ。

だからこそ、ミューテーション解析を提案したい！

このテクニックは、あなたのコードを変更してテストを動かすとテストが失敗するのを期待します。そうでないと、あなたのテストに何らかのミスが有るはずだ。

このトークでは、ミューテーション解析のより詳しい技術を紹介したり、Scalaのプロジェクトへの適用の仕方を説明したり、実際のプロジェクトでの幾つかの結果をお見せするつもりだ。
