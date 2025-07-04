---
title: Welcome to Slidev
drawings:
  persist: false
transition: slide-left
mdc: true
theme: apple-basic
layout: intro-image
image: 'https://cover.sli.dev'
---

<style>
  .azureColor {
    background-color: rgb(0, 109, 193);
    color: white;
  }

  table {
    border-top: 4px double black;
    border-bottom: 4px double black;
    table-layout: fixed;
    width: 100%;
  }

  th {
    font-weight: bold !important;
    text-align: center !important;
  }

  td:nth-child(1) {
    font-size: xx-large;
    font-weight: bold;
  }

  td:nth-child(2) {
    font-size: large;
    font-weight: bold;
  }

  td:nth-child(3) {
    font-size: x-small;
  }

  th:nth-child(1),
  td:nth-child(1) {
    width: 10%;
  }

  th:nth-child(2),
  td:nth-child(2) {
    width: 50%;
  }

  th:nth-child(3),
  td:nth-child(3) {
    width: 40%;
  }

  p {
    color: gray;
  }
</style>

# Microsoft Azure AI Fundamentals

Study guide for Exam AI-900

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

---
layout: default
---

# 試験概要

試験概要を押さえて試験本番当日に備えましょう。

- ✅ **スコア700以上で通過** - AI-900試験は、合格には700点（1000点満点）以上が必要です。
- ⏱ **試験時間は45分** - 試験はコンピュータ上で実施されるCBT（Computer Based Testing）形式です。
- 🔄 **プール方式** - 試験ごとに数百問単位の問題が用意されており、その中からランダムに出題されます。
- 🌐 **試験内容のバージョン差異** - 英語版の更新が先に行われ、他言語版は最大約8週間遅れます。  
- 🈳 **例外的言語対応** - 受験者の主言語がサポートされていない場合、試験時間の延長の申請が可能です。
<br>
<br>
Read more about [Study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-900)


 

---

# 出題範囲と割合

| | 出題範囲とその割合 | 説明 |
|------|------------------------------------|------|
| 1 | AI ワークロードと倫理 - 15%-20% | AIの代表的なタスク（画像認識、自然言語、ドキュメント処理など）を理解。公平性・安全性・プライバシー・透明性・説明責任など「責任あるAI」の原則を把握。 |
| 2 | 機械学習の基本 - 15%-20% | 機械学習の種類（回帰、分類、クラスタリング、深層学習、Transformer）。トレーニングデータと検証データの違い。Azure Machine Learningの自動化、モデルの管理・デプロイ方法。 |
| 3 | コンピュータビジョン - 15%-20% | CVの主なユースケース：画像分類、物体検出、OCR、顔分析など。対応サービス：Azure AI Vision、Azure AI Faceなど。 |
| 4 | 自然言語処理（NLP） - 15%-20% | キーフレーズ抽出、感情分析、固有表現認識、言語モデル、音声認識・合成、翻訳。対応サービス：Azure AI Language、Azure AI Speechなど。 |
| 5 | 生成AI（GenAI） - 20%-25% | 生成AIとは？そのユースケース（テキスト生成、会話AI、コード生成など）。Azure OpenAIやAzure AI FoundryなどのGenAIサービスの特徴。生成AIにおける倫理的懸念（偽情報、偏りなど）も問われる。 |

---

# 変更点まとめ（2025年5月以降）

| 項目 | 説明 | 備考 |
|------|------|------|
| 1 | 生成AI - ↗️ 増加傾向 | 出題割合が増加。Azure OpenAIやFoundryの理解が重要。 |
| 2 | OpenAI関連 - ↗️ 増加傾向 | Azure OpenAIやChatGPT APIに関する項目が拡張。 |
| 3 | 機械学習 - ↘️ 減少傾向 | 全体の割合がわずかに減少。ただし基礎理解は必要。 |
| 4 | AIワークロード - 🔄 内容刷新 | ワークロードの分類や責任あるAIの観点で大きく更新。 |

---

## 学習のすすめ方

- Microsoft Learn（無料教材）を活用
- Azure無料枠でのハンズオン実践
- 模擬問題で出題形式に慣れる
- AI倫理の考え方に注目する

---

## この資格の価値

- Azure AI/Data系資格の基礎固め
- 非技術職でもAI/DXの理解促進に◎
- 生成AI時代の教養として重要

---

## 最後に

🎯 基本を押さえ、Azureの実務感覚を身につけよう！

🧠 「AIの文脈を理解できる人材」は今後ますます貴重に。

---

## 参考リンク

- Microsoft Learn（公式教材）
  https://learn.microsoft.com/ja-jp/certifications/exams/ai-900/ 


---