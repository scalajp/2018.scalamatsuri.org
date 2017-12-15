---
name: awekuit
title: "Akka Streams と Kubernetes による、重要でデリケートな無停止オペレーションをこなすためのアプローチ"
length: 40
audience: Intermediate
language: Japanese
twitter: awekuit
github: awekuit
icon: https://pbs.twimg.com/profile_images/590112328756015104/kcSN89Am_400x400.jpg
organization: Chat Work 株式会社
tags:
  - Tools
  - Best Practices
suggestions:
  - 無停止で本番DBに何かしなくてはならない人
  - Akkaとモダンなコンテナオーケストレーションツールに興味のある人
---
ChatWorkは2016年末にチャットメッセージング処理をPHPからScalaへ移行すると共に、データベースをAuroraからHBaseへ移行しました。  
データ移行後に本番データを無停止に補正する必要がありましたが、そこではデータマイグレーションで使ったSparkではなくAkka Streamsを採用しました。  
このトークでは、RDBMSからNoSQLへの大きな変化を経験し新しくDB運用を開始したばかりの状況で、全20億の本番データを無停止で補正しなくてはならないという課題を如何に安全にこなすか？ という問いの解決策として、高スループットだけではないAkka Streamsの柔軟性と拡張性が役立った話と、Kubernetesとの組合せによる動的なスロットリング制御によって我々がデリケートなオペレーションを安心安全に行えたこと、そのために必要だった準備や知見をお話しします。