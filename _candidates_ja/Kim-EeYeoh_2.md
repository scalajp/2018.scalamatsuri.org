---
name: Kim-Ee Yeoh
title: "圏論による美しきロギング: なぜ Writer モナドはロギングに向かないか、どのモナドに置き換えるか"
length: 40
audience: Intermediate
language: English
twitter: ky3atamo
github: 
icon: http://ruby.id/images/conf/2017/abdullah-pic.jpg
organization: 
tags:
  - Functional Programming
  - Best Practices
  - Microservices
suggestions:
  - Scala を書く際に、誤った抽象化を使って皆の前で恥をかきたくない人
---
圏論の導師たちは、Writer モナドを説明する時にロギングを例に出します。しかし、ロギングは悪い例です。なぜなら、Writer モナドの定義は、その名前に反してログ全体を読んだり変更したりできます。これは二つの理由で正しくありません。一つはコストが非常に高くつくこと。もう一つは、ログは典型的には書かれるだけのもので、読んだり、ましてや絶対に変更してはいけないからです。

では、圏論的に正しいロギングの方法は何でしょうか？

このトークでは三つのメリットを提供し、解答を提示します。あなたは Free モナドの実践を目にし、その理論をよりよく理解できるでしょう。
