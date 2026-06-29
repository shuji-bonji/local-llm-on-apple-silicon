---
title: "付録G エージェント監督：VS Code Remote-SSH という査読レンズ"
---

:::message
**この章でできるようになること**: neko8 上で自律作業するローカルエージェントの出力を、生のワーキングツリーのまま VS Code(Remote-SSH) で査読・操舵できる。tmux+Neovim の「操縦レンズ」と使い分けられる。
:::

:::message alert
本章は構成のみの**スタブ**です。本文は private リポジトリ `localllm-construction-practice` の出典 md から蒸留して執筆します。
状態: 🚧 構想 / 要検証（実機での監督ワークフロー検証はこれから）
:::

## 前提

- 第8章（SSH 越し運用）/ 付録F（tmux + Neovim の操縦レンズ）
- neko8 上でエージェント（OpenCode 等）がリポジトリを改変できる状態

## アウトライン（見出し候補）

- 役割の転換：自律エージェントが書き始めると人間は「著者」から「査読者/監督」へ
- 同一ワーキングツリーへの2レンズ：tmux+Neovim（操縦）/ VS Code Remote-SSH（査読）
- なぜ Remote-SSH か：VS Code Server が neko8 側で動く ＝ NFS マウントとの本質差
- 査読で効く4機能：多ファイル diff 一望 / hunk 単位 stage / neko8 側 LSP / 統合ターミナル
- 落とし穴：生ツリー査読の競合（file-on-disk / git index レース）と緩和3パターン（ターン制 / git worktree / PR 査読）
- 役割分担：GUI 監督（人間レイヤー）は `accept.mjs`（機械ゲート, clean-room）を置き換えない
- リセット：neko8 の `~/.vscode-server` 撤去

## 出典 md（private: localllm-construction-practice）

- macbookprom1pro/vscode-remote-ssh-supervision.md
- opencode/uc6-acceptance-gate.md（accept.mjs との役割分担）
- vim/remote-dev.md / tmux/pair-programming-with-agents.md（操縦レンズ側）
