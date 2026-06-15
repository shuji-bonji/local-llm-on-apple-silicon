---
title: "第7章 チャット1回の裏側を観察する"
---

:::message
**この章でできるようになること**: 『チャット1回＝推論4回』の実態を GPU モニタ + DevTools で観測し、GPU が30秒回る正体を特定できる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第3章

## アウトライン（見出し候補）

- SSE（本文）と WebSocket（状態 push）の分担
- 応答後も GPU が回る正体（title/tags/follow-up）
- タスクモデル分離で後処理を軽くする

## 出典 md（private: localllm-construction-practice）

- openwebui/observing-chat-internals.md
