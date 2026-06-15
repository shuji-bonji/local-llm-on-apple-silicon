---
title: "第5章 NFS で LAN 内ファイル共有"
---

:::message
**この章でできるようになること**: macOS nfsd（v3）で LAN 内ファイル共有を建て、クライアントから autofs で自動マウントできる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: ✅ 検証済み（実機で構築・確認済）
:::

## 前提

- 第1章

## アウトライン（見出し候補）

- /etc/exports と nfsd
- クライアント autofs（~/mnt 配下）
- UID/GID 一致と権限
- v4 非対応の注意

## 出典 md（private: localllm-construction-practice）

- macbookprom1pro/llm-server-setup.md §5-6
