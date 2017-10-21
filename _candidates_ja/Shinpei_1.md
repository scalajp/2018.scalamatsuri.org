---
name: しんぺい a.k.a. 猫型蓄音機
title: "Building native apps with Scala.js"
length: 40
audience: Intermediate
language: Japanese
twitter: neko_gata_s
github: Shinpeim
icon: https://pbs.twimg.com/profile_images/665564007474946048/xQADoQ5B_400x400.jpg 
organization: 株式会社メディロム プログラマ
tags:
  - Best Practices
  - Software Design and Architecture
suggestions:
  - ScalaでGUIアプリケーションを開発したいひと
  - Scala.jsの実用例に興味のあるひと
  - JSに疲れているひと
---
ここ数年以上、良いユーザー体験を提供するために、デスクトップアプリケーションやモバイルアプリケーションをラピッドに開発する必要性が高まり続けています。ElectronやReactNativeのような、JavaScriptでネイティブGUIアプリケーションを開発するツールキットは、そのような背景にマッチし、日に日に存在感を強めていると言えるでしょう。

一方で、複雑な状態管理を動的型付け言語によって行うのは、かなり難しく、辛いものです。特に、レイヤードアーキテクチャのような「きっちりとした」作りのアプリケーションをJavaScriptで書くのは、SwiftやKotlinを利用して書くのに比べるとかなり開発者体験が悪いと言えそうです。

そのような考えから、Scala.jsとElectronやReactNativeを併用しながら、ラピッドにUIを作りつつも、コア部分は静的型付けとScalaの強力な言語機能に守られながらネイティブアプリを作るという試みを行ってきました。その成果物としては以下のようなものが挙げられます。

- [猫型ドラムシーケンサー](https://shinpeim.github.io/ScalaJsDrumSequencer/web/build/) (web app)
- [Backlog](https://www.backlog.jp/)クライアント (desktop app powered by Vue.js)
- コード譜エディタ(WIP) (iOS app powered by ReactNative)

このセッションでは、それらのアプリケーションをScala.jsで書いていくにあたって得てきた知見を共有します。以下のような内容が含まれる予定です。

- Scala.jsで開発していて嬉しい部分
- Scala.jsで開発していて辛い部分
- Scala.jsとJavaScriptの使い分けについての私案
- JSの良さもScalaの良さも活かすためのアプリケーション・アーキテクチャ

応募者の参考リンク:[ブログ](http://nekogata.hatenablog.com/)

