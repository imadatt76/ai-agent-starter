# AI Agent Starter

個人・小商売・チームの情報をAIが読める形で蓄積し、AI参謀、AI分身、AI会議室の土台を作るためのスターターキットです。

このリポジトリは、特定の個人データを含まない「器だけ」のテンプレートです。自分のOS、事業情報、ログ、判断基準を入れて育ててください。

---

## できること

- 自分専用のAI参謀を作る
- 事業・商品・顧客・ログをAIが参照できるようにする
- 雑談や壁打ちをログとして残し、後から知識化する
- 自分やチームメンバーのOSを整理し、育成・配置・戦略会議に使う
- Claude Code、Codex、ChatGPTなど複数AIで同じ情報を参照する

---

## 最初に読むファイル

1. `INDEX.md` - AIが最初に見る入口
2. `AI_COLLAB_RULES.md` - AIとの共通ルール
3. `OS.md` - 自分の判断基準を書く場所
4. `wiki/index.md` - Wikiの目次

---

## 基本構成

```text
ai-agent-starter/
├── INDEX.md                  # AI用ナビゲーション
├── AI_COLLAB_RULES.md         # AIとの共通ルール
├── CLAUDE.md                  # Claude Code用入口
├── AGENTS.md                  # Codex等のAIエージェント用入口
├── OS.md                      # 自分のOSを書くテンプレート
├── COMMAND.md                 # よく使う依頼・運用コマンド
├── wiki/                      # 知識ベース
│   ├── index.md
│   ├── SCHEMA.md
│   ├── log.md
│   └── pages/
├── logs/                      # 会話ログ・日報など
│   └── casual/
└── docs/                      # 資料・講座・メモ
```

---

## 使い方

1. このリポジトリをコピーする
2. `OS.md` を自分用に書く
3. `wiki/pages/` に事業・商品・考え方を追加する
4. AIに「まず `INDEX.md` を読んで」と伝える
5. 重要な会話は `logs/casual/` に残す
6. 再利用できる知識は `wiki/pages/` に昇格する

---

## AIへの依頼例

```text
まず INDEX.md と AI_COLLAB_RULES.md を読んで、このワークスペースの前提を把握して。
```

```text
OS.md と wiki/pages/business/current_status.md を読んで、今月の優先順位を整理して。
```

```text
この会話を casual log として残して。後でWiki化できる粒度で要約して。
```

```text
AさんのOSメモと商品情報を読んで、この商品をどう売るか戦略会議して。
```

---

## 注意

- 個人情報、顧客情報、APIキー、認証情報はGitHubに入れないでください。
- 公開リポジトリで使う場合は、必ずサンプルデータだけにしてください。
- AIの出力は最終判断ではありません。本人・運営者が判断してください。
