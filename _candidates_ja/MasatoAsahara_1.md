---
name: 浅原 理人 (@m_asahara)
title: "(Scala, Apache Spark, TensorFlow, XGBoost) => お手軽機械学習"
length: 40
audience: Beginner
language: Japanese
twitter: m_asahara
icon: https://pbs.twimg.com/profile_images/1263549533/asahara_park_400x400.jpg
organization: NEC システムプラットフォーム研究所
tags:
  - Tools
  - Best Practices
  - Data Science / Machine Learning
suggestions:
  - Scalaでデータ分析システム・アプリを開発する方・開発に興味がある方
  - Apache Sparkでの分散処理システム開発経験がある方・開発に興味がある方
  - TensorFlowやXGBoostといった機械学習ライブラリを使用する方
---
機械学習が大流行しています。Googleの深層学習ライブラリTensorFlowやワシントン大のXGBoostなど機械学習OSSが充実してきており、機械学習が身近な存在になってきました。  
一方で、機械学習で高精度の予測をするにはたくさんの試行錯誤とチューニングを行う必要があります。TensorFlowやXGBoostも数百もの試行パターンがあるため、いちいち手作業で実行するのは大変です。  
私たちはこの手間を軽減するために、Scalaと最もモダンなインメモリ分散処理基盤のひとつであるApache Sparkを活用した機械学習大量実行ツールを開発しました。  
このツールは、Spark上でTensorFlowとXGBoostを同時に多数実行して、何百通りの試行パターンを一気に実行できます。さらにこのツールは、今後新たに登場する機械学習OSSを容易に取り込めるよう拡張性の高い設計となっています。  
本発表では、Scalaの一応用として本ツールを紹介し、またこれを題材としてSparkをScalaから扱う魅力とその難しさ・使いこなすためのノウハウについて語ります！