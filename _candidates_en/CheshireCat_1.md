---
name: Cheshire Cat
title: "Operation Haskell + Scala Hybrid Development"
length: 40
audience: Beginner
language: Japanese
twitter: y_taka_23
github: y-taka-23
icon: https://avatars2.githubusercontent.com/u/2419525
organization: ProofCafe
tags:
  - Functional Programming
  - Others
suggestions:
  - Scala/Java programmers who consider Haskell to be a big hurdle
slide_url: https://speakerdeck.com/ytaka23/operation-haskell-plus-scala
youtube: 
---
In this sesssion, I will show seamless integration between Haskell and Scala using a Haskell implementation on JVM, called Eta.

Eta guarantees near-perfect compatibility with modern Haskell code, but it simultaneously supports calling out to Scala/Java libraries that are semantically foreign in an ingenious way. Furthermore, since the compiled result becomes JVM bytecode, you can now easily embed the Haskell part into a Scala project. You can now have the cake from both languages and eat it too.

I will start with the basics of Haskell, explain Haskell-Scala interoperation, and show how an actual hybrid project might be structured. The session does not require any prior knowledge, so if you are intimidated by Haskell, this session is actually for you.
