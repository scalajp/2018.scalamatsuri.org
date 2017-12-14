---
name: Michael Slinn
title: "web3j-scala, 軽量でこなれたEthereum(仮想通貨)用のweb3j Scalaラッパー"
length: 40
audience: Beginner
language: English
twitter: mslinn
github: mslinn
icon: https://www.micronauticsresearch.com/images/_DSC1094_600.jpg
organization: Distinguished Engineer, Micronautics Research
tags:
  - Functional Programming
  - Best Practices
  - Software Design and Architecture
suggestions:
  - ステートフルなJVMライブラリであるweb3jをどのようにして関数型言語的なAPIにするかをお見せします
  - 実行時のオーバーヘッドなしに、どのようにして型安全なAPIをScalaの値オブジェクトを使って実現するかをお見せします
  - ScalaからどのようにEthereumを扱うかをお見せします
---
web3j-scalaは、私が書いた、web3.jsのJava 8版ライブらいであるweb3jをラップしたこなれたScalaライブラリです。
これら3つのライブラリは全て、EthereumクライアントがサポートしなければならないjsonRPCのプロトコルに適合しています。
web3jは、Ethereumのブロックチェーン上のNodeと接続するための、軽量でリアクティブで概ね型安全なJavaとAndoroid向けのライブラリです。
web3j-scalaは、Java版、JavaScript版よりも型安全かつスケーラビリティに優れ、さらにソリューションをScalaで書く楽しさを提供しています。

このトークでは、どのようにJVMライブラリをパッケージするScalaライブラリを開発し、利用者がライブラリから最大限の利益を享受するためにJVMエコシステムとどのように向き合えばよいかの洞察を加えます。
EthereumとJSON-RPCのデモンストレーションをします。

こちらも是非見て下さい http://blog.mslinn.com/blog/2017/11/29/web3j-scala