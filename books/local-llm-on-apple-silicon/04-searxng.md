---
title: "第4章 SearXNG で Web 検索を統合する"
---

:::message
**この章でできるようになること**: SearXNG を pip 構成で建て、Open WebUI から Web 検索つき回答を出せる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第3章

## アウトライン（見出し候補）

- pip + venv + LaunchDaemon 構成
- settings.yml（json formats / limiter:false）
- Open WebUI 連携と『バイパス』設定
- 403 / 429 のトラブルシュート

## 出典 md（private: localllm-construction-practice）

- searxng/what-is-searxng.md
- macbookprom1pro/llm-server-setup.md §4.6
