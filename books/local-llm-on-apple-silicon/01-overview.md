---
title: "第1章 全体像とメモリ予算（完全ヘッドレス方針）"
---

:::message
**この章でできるようになること**: neko8 の全体構成と 32GB ユニファイドメモリの予算配分、完全ヘッドレス運用の方針を掴む。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- なし（本書の入口）

## アウトライン（見出し候補）

- 構成図（Ollama / Open WebUI / SearXNG / NFS）
- メモリ予算表（macOS + 26B + 周辺）
- FileVault と自動ログインの関係
- 方式A（LaunchAgent）vs 方式B（LaunchDaemon・完全ヘッドレス）

## 出典 md（private: localllm-construction-practice）

- macbookprom1pro/llm-server-setup.md §0, §2.5, §11
- macbookprom1pro/llm-server-architecture.md
