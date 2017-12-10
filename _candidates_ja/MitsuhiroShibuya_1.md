---
name: 渋谷 充宏 (@m4buya)
title: "Scalaによるtype-safeなCloudFormation DSL"
length: 40
audience: Intermediate
language: Japanese
twitter: m4buya
github: mshibuya
icon: https://avatars0.githubusercontent.com/u/486678?s=460&v=4
organization: 株式会社オプト　テクノロジー開発部　チームマネージャー
tags:
  - DevOps
suggestions:
  - クラウドインフラに興味のある人
  - Scalaの新たな活用法を模索している人
---
Infrastructure as Codeのプラクティスは広く受け入れられており、クラウドインフラの構成においてもAWS CloudFormationのようなコードによる構成管理ツールを利用することが一般的となっています。一方、CloudFormationはJSON等による記述を採用しており、記述の容易性やメンテナンス性に劣っているため、テンプレートを生成するための様々なDSLが作られてきました。そういったDSLの多くは表現力や可読性を上げる上で大いに役立つのですが、大規模システムに求められるような複雑なロジックの記述に対する支援は必ずしも十分でなかったと考えています。
そこで今回、Scalaの持つ強力な型システムを活かし、複雑なインフラを静的型付けの支援のもと安全に変更してゆけるDSLをOSSとして開発中です。本発表では、その特徴・設計思想・活用方法などについてお話できればと思います。
