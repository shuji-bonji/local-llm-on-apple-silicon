---
title: "第10章 LiteLLM を建てる：gemma-fast / gemma-smart"
---

:::message
**この章でできるようになること**: LiteLLM を LaunchDaemon で建て、用途別エイリアス（gemma-fast / gemma-smart）でハブ API を提供できる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第9章

## アウトライン（見出し候補）

- venv + LaunchDaemon 構成
- config.yaml とモデルエイリアス設計
- 用途別にサイズを振る（タスク=軽量 / 主力=smart）

## 出典 md（private: localllm-construction-practice）

- macbookprom1pro/litellm-langgraph-setup.md（Phase 1）
