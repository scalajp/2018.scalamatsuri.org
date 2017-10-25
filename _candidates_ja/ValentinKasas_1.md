---
name: Valentin Kasas
title: "私が書いたこともなかった10000ものcase class"
length: 40
audience: Intermediate
language: English
twitter: ValentinKasas
github: vil1
icon: https://pbs.twimg.com/profile_images/832263608830668800/Sc3gPzek_400x400.jpg
organization: Freelance developer @ Kanaka
tags:
  - Big Data / Fast Data
  - Functional Programming
  - Software Design and Architecture
suggestions:
 - 数多くの型のデータを安全に処理する必要のある人
 - 実務的な問題に対する関数型の解決方法を知りたい人
 - 再帰的な方法論に興味のある人
---
Sparkでデータのバリデーションを行うとき、またはKafkaトピックに対して読み込み/書き込みをおこなうとき、一般的にはScalaのcase classやJava Beanを使うことになると思います。
しかし、もしあなたのチームに5人の開発者しかおらず、10000以上のデータ型を処理するプロジェクトを数ヶ月以内に終わらせなくてはならないとしたらどうでしょう？
hylomorphismsと宣言的な方法論を組み合わせることで、たとえ100もの異なるデータ元の数十の異なるテーブルからデータのバリデーションと変換を行う必要があっても、
定められた期間と予算内で正しく動作するコードを書くことが出来ます。
