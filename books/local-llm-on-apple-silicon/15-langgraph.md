---
title: "第15章 LangGraph.js への昇格判断"
---

:::message
**この章でできるようになること**: 単発 tool calling では過剰になる局面を見極め、LangGraph.js（状態機械）へ昇格する判断ができる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: 🚧 未着手 / 構想（本書の検証ループ対象）
:::

## 前提

- 第14章

## アウトライン（見出し候補）

- 単発 tool calling の限界
- 連鎖・分岐・再試行が要る時
- 状態機械としての設計（L4: Instruction Decay 対処）

## 出典 md（private: localllm-construction-practice）

- langgraph/what-is-langgraphjs.md
