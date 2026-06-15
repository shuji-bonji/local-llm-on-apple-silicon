---
title: "第3章 Open WebUI（pip 版）を LaunchDaemon で常駐させる"
---

:::message
**この章でできるようになること**: Docker を使わず pip 版 Open WebUI を LaunchDaemon で常駐させ、管理者設定まで通せる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第2章

## アウトライン（見出し候補）

- venv とインストール
- フォアグラウンド起動と初期ユーザ
- LaunchDaemon 化
- 『3つの紛らわしいモデル』の整理
- 設定深掘り（タスクモデル分離）

## 出典 md（private: localllm-construction-practice）

- openwebui/what-is-openwebui.md
- openwebui/the-three-confusing-models.md
- openwebui/settings-deep-dive.md
- macbookprom1pro/llm-server-setup.md §3-4
