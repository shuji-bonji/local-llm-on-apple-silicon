---
title: "第6章 ヘッドレス運用：SSH・自動起動・更新"
---

:::message
**この章でできるようになること**: SSH 公開鍵ログイン・自動起動連鎖・更新手順で、neko8 を日常運用に乗せられる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第1章

## アウトライン（見出し候補）

- SSH 公開鍵と ~/.ssh/config 短縮
- 自動ログイン → LaunchAgent 連鎖起動
- 稼働中サービスの更新・再起動・切り分け
- 運用チートシート

## 出典 md（private: localllm-construction-practice）

- macbookprom1pro/llm-server-setup.md §4.5, §7-8
- macbookprom1pro/llm-server-update.md
