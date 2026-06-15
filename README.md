# local-llm-on-apple-silicon

> Zenn book **「Apple Silicon Mac でローカル LLM を建てる」** のソースリポジトリ。

MacBook Pro M1 Pro 32GB を OpenAI 互換 API・MCP・自律エージェント開発の基盤として**完全ヘッドレス**で建て、運用・計測・拡張までを一気通貫で扱うハンズオン本です。

## 位置づけ（AI駆動開発情報の半減期 / 4 レイヤーモデル）

本書は **L1（Tips）/ L2（プロダクト）** レイヤー。半減期が短い（3〜18ヶ月）ため、**書いた時点で封じるスナップショット**として Zenn book で出します。長半減期の L3/L4 が維持され続ける VitePress サイトなのと対照的に、**媒体を半減期に合わせています**。

| レイヤー | 半減期 | リポジトリ | 媒体 |
| --- | --- | --- | --- |
| L1 Tips / L2 プロダクト | 3〜18ヶ月 | 👈 本書 | Zenn book（封じる） |
| L3 アーキテクチャ | 3〜5年 | [ai-agent-architecture](https://github.com/shuji-bonji/ai-agent-architecture) | VitePress（維持） |
| L4 原理 | 10年+ | [understanding-llm-through-claude-code](https://github.com/shuji-bonji/understanding-llm-through-claude-code) | VitePress（維持） |

出典: [Discussion #80「AI駆動開発」情報の半減期](https://github.com/shuji-bonji/ai-agent-architecture/discussions/80)

## 状態

🚧 **WIP（構成スタブ段階）**。`config.yaml` は `published: false`。各章は構成のみのスタブで、本文は private リポジトリ `localllm-construction-practice`（作業台）の手順書から**蒸留（distill）**して順次執筆します。全体を実機で再構築検証してから公開する方針です。

## ローカルプレビュー

```bash
npm install
npm run preview   # → http://localhost:8000
```

## 構成

```
books/local-llm-on-apple-silicon/
  config.yaml          # タイトル / topics / published:false / chapters 順序
  00-intro.md          # はじめに（本文済み）
  01-overview.md 〜     # 各章（スタブ）
articles/              # （未使用）
```

章の状態マーク: ✅ 検証済み / 🟡 実験的に確認 / 🚧 未着手・構想

## ライセンス

TBD（公開前に決定）。
