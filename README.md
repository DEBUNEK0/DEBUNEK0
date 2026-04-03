<h1 align="center">Hi, I'm Tomo</h1>

<p align="center">
  京都大学大学院 工学研究科 / AIシステム / RAG / LLMインフラ / 分散システム
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Kyoto%20University-Graduate%20School-4B6BFB" />
  <img src="https://img.shields.io/badge/Python-ML%20%26%20Backend-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-Systems-black?logo=rust" />
  <img src="https://img.shields.io/badge/TypeScript-Web%20%26%20App-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-Delivery-FF9900?logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-Deployment-0078D4?logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-Production%20Oriented-0A7EA4" />
  <img src="https://img.shields.io/badge/AI%20Workflow-Build%20%26%20Delivery-4C8BF5" />
  <img src="https://img.shields.io/badge/LLM%20Infra-vLLM%20%2F%20Ray-6A5ACD" />
  <img src="https://img.shields.io/badge/Workflow-Mastra-1F9D55" />
  <img src="https://img.shields.io/badge/Role-Tech%20Lead-222222" />
</p>

---

## About

京都大学 工学部 物理工学科を卒業し、現在は京都大学大学院 工学研究科 マイクロエンジニアリング専攻 修士課程に所属しています。  
Python / Rust / TypeScript を中心に、**AIシステム・RAG・LLMインフラ・分散システム**に取り組んでいます。

これまでは主に、**AWS上でのAIワークフロー構築、RAGシステムの設計・実装・納品、AIアバター開発**など、  
「AIを実際に業務で使える形にする」ための設計と実装を進めてきました。

最近は、**DGX Spark / vLLM / Ray を用いたローカルLLM基盤や分散推論環境**の構築にも取り組んでいます。

研究では、**数理モデリングや Markov Decision Process (MDP)** に関心があり、Rust での実装も進めています。

---

## Featured Projects

### 1. Rust MDP Library
Rust で **拡張性を重視した MDP 実装**を進めています。  
研究用途だけでなく、再利用しやすいライブラリとして整備していく予定です。

- 汎用的な状態・行動・報酬表現
- policy iteration / value iteration などの基本実装
- 実験しやすい設計
- テストとドキュメントを重視

- Repository: https://github.com/DEBUNEK0/mdp_rust

### 2. Engineer Guild Hackathon Project
Engineer Guild Hackathon 2025 で開発した公開プロジェクトです。  
短期間でも、**実装だけでなく、設計や公開可能な完成度**を意識して開発しました。

- Repository: https://github.com/Engineer-Guild-Hackathon/team-3-app
- Article: <!-- 後でZenn記事リンクを追加 -->

---

## Experience

約2年間のエンジニアインターンの中で、主に **AIを業務で使える形にするための設計・実装** に取り組んできました。

### これまで主に取り組んできたこと
- AWS上での AI ワークフロー実装
- RAG システムの設計・実装・納品
- TTS / STT / RAG を組み込んだ AI アバター開発
- クライアント要件に応じた AI プロダクト実装
- テックリードとしての設計・実装推進

### 最近取り組んでいること
- DGX Spark を用いたローカルLLM環境のセットアップ
- vLLM + Ray による分散推論環境の構築
- オンプレミス / スタンドアロンで動作する LLM 基盤の整備
- Mastra を用いた AI ワークフロー設計・構築

### 強み
- 実験用の仕組みではなく、**実際に使われるシステム**として設計すること
- 要件に応じて、**ワークフロー / アプリ / 推論基盤**をつなげて実装できること
- 新しい技術を導入するだけでなく、**運用や拡張を見据えて構成を考えること**

- Interview: https://note.com/athenatech/n/n076d36f4ea1b

---

## Hackathon

### Engineer Guild Hackathon 2025
Engineer Guild Hackathon 2025 の Finalist として開発したプロジェクトです。  
短期間での開発でしたが、**AIアプリを実際に公開できる形まで持っていくこと**を重視して取り組みました。

**主な担当**
- Azure 上への Web アプリのデプロイ
- AI 機能まわりの設定と統合
- プロンプトインジェクション対策
- Figma を用いた UI 設計
- 実装・設計・公開までを通した開発推進

**この経験で特に出た強み**
- 短期間での設計判断
- AI 機能を含む Web アプリの実装と統合
- セキュリティを意識した AI アプリ開発
- UI からデプロイまで横断して進める力

- Repository: https://github.com/Engineer-Guild-Hackathon/team-3-app
- Article: <!-- 後でZenn記事リンクを追加 -->

---

## 関わった公開事例・記事

以下は、**会社で担当してきた業務の一部として公開されている事例・記事**です。  
実際にはこれらに限らず、AIワークフロー設計、RAG実装、ローカルLLM基盤整備など、複数の案件で設計・実装を担当してきました。

### 1. AI-OCR / 業務システム連携
Athena Technologies の公開事例として、**FAX経由の請求書を自動読み取りしてデータ化するシステム**が紹介されています。  
公開情報では、OCR、多様なレイアウト対応、自動データ検証、既存システム連携、処理効率化が示されています。

**自分の担当**
- AWS 上で、FAX の OCR と後続処理を行うワークフローの設計・実装を担当
- 複数コンテナを立ち上げて処理を分担し、結果の格納やメール送信まで含めた一連の処理フローを構築
- 業務要件に合わせて、AI処理を実運用可能な形に落とし込む部分を担当

- Case: https://athenatech.jp/case/20231015

### 2. ローカルLLM活用事例
Athena Technologies の公開記事として、**常陽銀行向けのローカルLLM活用事例**が掲載されています。  
公開情報では、閉域環境上のローカルLLM、共通運用基盤、翻訳・マスキング機能、および追加ユースケースの検証が紹介されています。

**自分の担当**
- Mastra を用いたワークフロー設計を担当
- ログ処理や RAG 処理など、開発を進めるためのテンプレートや基盤をテックリードとして整備
- DGX Spark 上で利用する LLM の選定、環境整備、デプロイ、Mastra からの呼び出しまでを担当
- 個別機能の実装だけでなく、チーム開発を進めやすくするための開発基盤づくりにも取り組んだ

- News: https://athenatech.jp/news/2026-0326

---

## Writing

実装だけでなく、**設計判断や運用知見を言語化すること**も大事にしています。

### Articles
- Hackathon / Azure / AI Web App: <!-- 後でZenn記事リンクを追加 -->
- DGX Spark / vLLM / ローカルLLM基盤: <!-- 後で技術記事リンクを追加 -->
- Interview: https://note.com/athenatech/n/n076d36f4ea1b
---

## Interests

- AI ワークフロー
- RAG システム
- AI アプリケーションの実装
- LLM インフラ
- 分散推論
- GPU クラスタ
- オンプレミス AI
- 数理モデリング
- Markov Decision Processes
