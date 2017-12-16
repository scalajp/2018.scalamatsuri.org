---
name: 下村 朋之
title: "compile time DIのススメ"
length: 10
audience: Beginner
language: Japanese
twitter: s10myk47
github: 
icon: https://pbs.twimg.com/profile_images/794027848122044416/84gSnh0o_400x400.jpg
organization: 株式会社セプテーニ・オリジナル
tags:
  - Best Practices
  - Software Design and Architecture
suggestions:
  - typesafeな人
  - GuiceでのDIに疑問や不満を持っている人
---
Play Frameworkでは、JSR330に準規したruntime DIとcompile time DIの両方をサポートしていますが、PlayはGoogle Guiceを標準で利用しています。
しかし、@Injectや @Singleton などのアノテーションがたくさん出てきてJavaを書いてるのか？と感じることがあります。
僕の以前のプロジェクトでは巨大なModuleクラスが出来上がってしまいました。テストもつらみがありますよね。

このセッションでは、MacWireを使ってのcompile time DIのメリット(GuiceでのDIと比較)と実装方法などを紹介する予定です。
Love typesafe!
