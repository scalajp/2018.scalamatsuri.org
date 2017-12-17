---
name: Ratan Sebastian
title: "Recursion Schemesによる動的計画法"
length: 40
audience: Advanced
language: English
twitter: ratansebastian
github: rjsvaljean
icon: https://pbs.twimg.com/profile_images/1749512839/ratcomic_400x400.jpg
organization: commercetools
tags:
  - Functional Programming
  - Tools
suggestions:
  - Recursion Schemesについて多少の知識があり、より深く知りたいという人々
---
動的計画法には例えば最短経路探索、ナップサック問題を含む多くの有用なアルゴリズムが含まれ、
それらは分割統治とメモ化を行うことによって解を求めます。

これらのアルゴリズムは通常きれいな再起的実装を用い、また再帰的実装が用いられる場合には(典型的には直接的な再帰実装を行う場合)、
Recursion Schemeを用いて抽象化を行い、プログラムをより宣言的なものにすることができます。

このトークではHistomorphismsとDynamorphismsという2つのRecursion Schemesについてお話し、
それらがどのようにScalaで実装され、それらをつかってよくある動的計画法の解法をどのように実装するかをお教えします。
