---
title: "第16章 翻訳専用 LLM として使う（書式保持・品質ゲート・ベンチ）"
---

:::message
**この章でできるようになること**: ローカル LLM を docx 書式保持の翻訳エンジンとして使い、品質ゲートとモデルベンチで運用できる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第2章（Ollama 直 :11434）

## アウトライン（見出し候補）

- docx 書式保持翻訳（runs モード）
- xCOMET 品質ゲートと自動再翻訳
- モデルベンチ（Tower+ 等）
- DeepL を品質基準線に

## 出典 md（private: localllm-construction-practice）

- macbookprom1pro/translation-llm-usage.md
