---
title: "第9章 LiteLLM とは何か（LLM Gateway）"
---

:::message
**この章でできるようになること**: LiteLLM が I/F を双方向に吸収する『LLM Gateway』である理由と、MCP 前段に置く設計判断を理解できる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第2章

## アウトライン（見出し候補）

- プロバイダ I/F の差分を吸収する
- なぜ MCP Layer の前段に Gateway を置くか（L3 接続）
- OpenAI 互換 I/F に揃える価値

## 出典 md（private: localllm-construction-practice）

- litellm/what-is-litellm.md
