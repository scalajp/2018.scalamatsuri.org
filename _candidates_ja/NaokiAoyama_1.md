---
name: Naoki Aoyama - @aoiroaoino
title: "Purely Functional Play Framework Application"
length: 40
audience: Advanced
language: Japanese
twitter: AoiroAoino
github: aoiroaoino
icon: https://pbs.twimg.com/profile_images/556312366862708736/jmQUaeoW_400x400.jpeg
organization: 株式会社セプテーニ・オリジナル
tags:
  - Functional Programming
  - Software Design and Architecture
suggestions:
  - 関数型プログラミングの実用に興味のある人
  - 実行時 DI に不満のある人
slide_url: https://www.slideshare.net/AoiroAoino/purelyfunctionalplayframeworkapplication
youtube:
---
PlayFramework はとても素晴らしい Web フレームワークです。  高機能であり、小規模な書き捨てのアプリケーションから大規模なものまで使うことができ、まさに Scalable を体現しています。  
歴史もあり、公式もサポートする、Scala における Web フレームワークのデファクトスタンダードといっても過言ではありません。

しかし、私にはいくつか不満点があります。その一つが Google Guice を用いた実行時 DI です。  
これは大規模なアプリケーションを開発する際にとても効果的なものとなりますが、  
本当に今 Scala を書いているのだろうか？と思ってしまう場面に何度も遭遇します。  
そして、テスト時に Mock ライブラリを組み合わせたら最後、恐らく型安全の恩恵よりもぬるぽの遭遇率の方が高いでしょう。

本セッションでは Cats, doobie, Monix, Monocle などの関数型プログラミングライブラリを用いて、  
型安全に純粋なロジックのみを構築し、どの角度で切ってもテストできるような実装方法を提案します。

これは残念ながら万人に受け入れられるベストプラクティス、特効薬ではありませんが、  
まぁ、退屈なアプリケーションの実装に疲れた時の栄養ドリンク程度にはなるでしょう。