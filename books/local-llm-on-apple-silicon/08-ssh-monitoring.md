---
title: "第8章 SSH 越しに計測する：GPU・メモリ・電力・tok/s"
---

:::message
**この章でできるようになること**: ヘッドレスな neko8 を SSH 越しに計測し、観測値から疑うべき設定・選定の当たりを付けられる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第6章

## アウトライン（見出し候補）

- 計測スタックを sudo 要否で整理（macmon / mactop / powermetrics）
- ollama ps の GPU/CPU split を読む
- ollama run --verbose で実効 tok/s
- 『この数値を見たらこの選定を疑え』対応表

## 出典 md（private: localllm-construction-practice）

- macbookprom1pro/llm-server-monitoring.md
