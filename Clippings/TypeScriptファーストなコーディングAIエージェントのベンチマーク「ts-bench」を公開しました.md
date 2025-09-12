---
title: "TypeScriptファーストなコーディングAIエージェントのベンチマーク「ts-bench」を公開しました"
source: "https://blog.lai.so/ts-bench/"
created: 2025-09-06
description: "AIコーディングエージェントのTypeScriptコード編集能力を評価するための、手軽に再現可能なベンチマークプロジェクト「ts-bench」を公開しました。この記事では、筆者がなぜ ts-bench を作ったのか、今後どうしていきたいかについてお話しします。GitHub - laiso/ts-benchContribute to laiso/ts-bench development by creating an account on GitHub.GitHublaisots-benchの仕組みts-benchは、プログラミング学習プラットフォーム Exercism のTypeScript問題セットを利用します。各問題には、仕様を説明するドキュメント、エージェントが編集すべきソースコードのひな形、そして正解判定に使うテストコードが含まれています。ベンチマークタスクは、各問題に対して以下の4つのステップを順番に実行します。 1. AIエージェントの実行: 問題の指示書をプロンプトとしてAIエージェントに渡し、ソースコードを編集させます。 2. テストファイルの復元"
tags:
  - "clippings"
read: false
---
