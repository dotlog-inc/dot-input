# .input() エンジニア育成フロー

## 目次

1. [はじめに](#はじめに)
2. [不明点・詰まった点の報告方法](/docs/issue.md)
3. [基礎学習](#1-基礎学習)
4. [応用学習](#2-応用学習)
5. [Git/GitHub](#3-gitgithub)
6. [実践](#4-実践)
7. [チーム開発](#5-チーム開発)
8. [留意点](#留意点)
9. [よくある Q&A](#よくあるqa)
10. [おすすめ追加リソース](#おすすめ追加リソース)

- [自社開発への就職を目指す場合](#自社開発への就職を目指す場合)
- [おすすめの書籍](#おすすめの書籍)

11. [最終ゴール](#最終ゴール)

---

## はじめに

このフローでは、学習者がエンジニアとして必要なスキルを段階的に習得できるように設計されています。それぞれのフェーズには終了目安が設定されており、学習の進捗状況を確認しながら進めることができます。不明点や詰まった箇所は、以下のテンプレートに記録してください。

### **各フェーズの終了目安**

| フェーズ       | 終了目安             | 最低値 | 最高値 |
| -------------- | -------------------- | ------ | ------ |
| **基礎学習**   | 開始後 **1〜2 週間** | 7 日   | 14 日  |
| **応用学習**   | 開始後 **1〜2 週間** | 7 日   | 14 日  |
| **Git/GitHub** | 開始後 **1〜2 週間** | 7 日   | 14 日  |
| **実践**       | 開始後 **4〜8 週間** | 28 日  | 56 日  |
| **チーム開発** | 開始後 **1〜2 週間** | 7 日   | 14 日  |

### **合計**

| **合計** | **最低値**         | **最高値**          |
| -------- | ------------------ | ------------------- |
| **合計** | 63 日（約 2 か月） | 112 日（約 4 か月） |

---

## 不明点・詰まった点の報告方法

[別ページへ](/docs/issue.md)

---

## 2. 応用学習

- **目標**: React と Next.js の実践スキルを習得する。
- **チェックリスト**:
  - React:
    - [ ] [React ハンズオン教材](https://mosya.dev/react) を完了する
    - [ ] [React 動画教材](https://www.youtube.com/watch?v=15WLMqnkPsE&list=PLwM1-TnN_NN6fUhOoZyU4iZiwhLyISopO) を視聴する
  - Next.js:
    - [ ] [Next.js 動画教材](https://www.youtube.com/watch?v=eEP7CLqnRr0&list=PLT5klp7W4r8T0sf5EbgOtkna44hHgVxae) を視聴する

---

## 3. Git/GitHub

- **目標**: Git の基本操作を習得する。
- **チェックリスト**:
  - [ ] [Git 動画教材](https://www.youtube.com/watch?v=WHwuNP4kalU) を視聴する
  - [ ] [team-dev-learn リポジトリ](https://github.com/junjun-1345/team-dev-learn) を利用してハンズオンを行う

---

## 4. 実践

- **目標**: アプリを開発し、デプロイまで行う。
- **チェックリスト**:
  - [ ] 作成したいアプリを決定する
  - [ ] 要件を定義する
  - [ ] ワイヤーフレームを作成する（紙、Miro、Figma など）
  - [ ] リポジトリを作成する
  - [ ] コーディングを完了する
  - [ ] アプリをデプロイする

---

## 5. チーム開発

- **目標**: チーム開発を経験する。
- **チェックリスト**:
  - [ ] [team-dev-learn リポジトリ](https://github.com/junjun-1345/team-dev-learn) の Issue を取り開発する
  - [ ] レビューを受け、マージされるまでを完了する

---

## 留意点

1. **進捗管理**:
   - 不明点や詰まった箇所を簡単にメモする習慣をつける。
2. **LLM の使い方**:
   - **フェーズ 1**: 使用禁止（自力で解決力を養う）
   - **フェーズ 2 以降**: 使用可（ただし、生成されたコードを完全に理解すること）

---

## よくある Q&A

### Q1. どれくらい時間がかかりますか？

- **目安**: 約 2〜4 ヶ月で基礎から実践まで進め、実務に参加できるスキルを目指します。

### Q2. エラーが出て解決できません。どうすればいいですか？

- **解決方法**:
  1. エラー文を検索する。
  2. フェーズ 2 以降で LLM を活用する。
  3. メンターに質問する際は、[不明点・詰まった点の報告方法](#不明点・詰まった点の報告方法)を使って報告をする。

### Q3. 書籍は買うべきですか？

- **判断基準**:
  - **おすすめ**: 普遍的な知識（コンピューター構造、ネットワーク、設計）
  - **おすすめしない**: 言語やフレームワークなど（情報が古くなるため）

### Q4. LLM（大規模言語モデル）はどのように使えばよいですか？

- **フェーズ 1（基礎学習）**:
  - **使用しない**: エラー解決力やリサーチスキルを養うことが目的です。自分で解決する力を身につけましょう。
- **フェーズ 2（応用学習）以降**:

  1. **バグ解決の補助**: エラー文やコードの改善方法を尋ねる際に使用してよい。
  2. **コード生成**: プロジェクト内のコードを生成する際に活用可能。ただし、以下を守ること：
     - 出力されたコードを**必ず理解する**。
     - **理解とは**: コードがどのような機能を実現し、なぜそのように動くのかを詳細に説明できる状態。
  3. **学習リソースの補完**: 概念の説明や疑問点の簡単な解説に活用する。

- **注意点**:
  - **鵜呑みにしない**: 出力結果が誤っている場合があるため、自分で検証する。
  - **質問力を磨く**: 明確かつ具体的な質問をすることで、有用な回答が得られやすくなります。

---

## おすすめ追加リソース

### 自社開発への就職を目指す場合

- [HackerRank](https://www.hackerrank.com/) を利用する
- [AtCoder](https://atcoder.jp/) を利用する

### おすすめの書籍

- [プリンシプルオブプログラミング](https://amzn.to/3VgvKDx)
- [世界で闘うプログラミング力を鍛える本](https://amzn.to/3ZuxTOq)
- [ネットワークはなぜ繋がるのか](https://amzn.to/4eWhDtU)
- [良いコード/悪いコードで学ぶ設計入門](https://amzn.to/4157qZ3)
- [Good Code, Bad Code](https://amzn.to/3COeBup)
- [Web API: The Good Parts](https://amzn.to/4ga6IOt)
- [達人に学ぶ DB 設計 徹底指南書](https://amzn.to/49bdVvr)
- [SQL 第 2 版 ゼロからはじめるデータベース操作](https://amzn.to/4fQsbvV)

---

## 最終ゴール

- [ ] 個人開発を完了する（独自アプリの開発・公開）。
- [ ] チーム開発で Issue 管理からレビューまでを経験する。
