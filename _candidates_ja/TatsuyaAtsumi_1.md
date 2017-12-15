---
name: 渥美達也
title: "実践 Play2+kubernetes"
length: 10
audience: Beginner
language: Japanese
twitter: __Attsun__
github: Attsun1031
icon: https://avatars3.githubusercontent.com/u/1175560?s=80
organization: 株式会社ブレインパッド
tags:
  - Tools
  - Best Practices
  - DevOps
suggestions:
  - ・Scala + Play2でkuberentesで動くアプリケーションの開発を予定している方
  - kuberentesで動くアプリケーションの実際の開発フローを知りたい方
---
kubernetes（GKE）上で動くScala（play2）アプリケーションについての実践的な内容をご紹介します。

具体的には、以下のような内容を想定しています。（10分なので、サクサクとやっていく予定です）  
  - 開発〜自動テスト〜検証環境テスト〜リリースまでの一連の流れ  
  - kubernetes上で動かす際のplay2、sbtの設定  
  - kubernetesのconfig  
  - モニタリング、ロギング  

去年末より始めた新規サービスの開発をPlay2+GKEで行なっており、クラウドインフラ設計から実装まですべてをメインに担当していうるため、経験をもとに実践的なお話ができると考えています。