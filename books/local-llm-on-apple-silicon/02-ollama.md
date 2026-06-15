---
title: "第2章 Ollama：モデルを引く・選ぶ"
---

:::message
**この章でできるようになること**: Ollama を導入してモデルを pull し、選定方針とパラメータ（num_ctx / keep_alive）を決められる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第1章

## アウトライン（見出し候補）

- install と LAN 公開（OLLAMA_HOST 等）
- モデル選定方針（西側 OSS を候補に）
- num_ctx / keep_alive の意味とメモリ影響
- OLLAMA_MAX_LOADED_MODELS で同時ロード制限

## 出典 md（private: localllm-construction-practice）

- ollama/what-is-ollama.md
- models/about-llm-models.md
- macbookprom1pro/llm-server-setup.md §1-2
