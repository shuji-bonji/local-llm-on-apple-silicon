---
title: "第14章 LangChain.js × MCP アダプタ"
---

:::message
**この章でできるようになること**: @langchain/mcp-adapters で自作 MCP をエージェントから実行し、複数サーバ・多ツールを束ねられる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: 🟡 実験的に確認済み（本文蒸留前・要再検証）
:::

## 前提

- 第13章

## アウトライン（見出し候補）

- @langchain/mcp-adapters の構成
- epsg + rxjs の2サーバ15ツール実行
- gemma-smart 実用合格（正答5/5）の実測

## 出典 md（private: localllm-construction-practice）

- macbookprom1pro/litellm-langgraph-setup.md（Phase 3）
- （実測ログ）neko8 次フェーズ検証
