# AI Workspace Index

> AIはまずここを見る。話題に応じて該当ファイルへ辿る。

---

## 最初に読むもの

| 目的 | ファイル |
|---|---|
| 全体の入口 | `INDEX.md` |
| AIとの共通ルール | `AI_COLLAB_RULES.md` |
| 自分の判断基準 | `OS.md` |
| よく使う依頼 | `COMMAND.md` |
| Wiki目次 | `wiki/index.md` |

---

## 話題別ナビゲーション

| 話題 | 行く場所 | 最初に読むファイル |
|---|---|---|
| 経営・売上・現在地 | `wiki/pages/business/` | `wiki/pages/business/current_status.md` |
| 思考・価値観・OS | `wiki/pages/thinking/` | `wiki/pages/thinking/os.md` |
| AI運用・ルール | `wiki/pages/ai/` | `wiki/pages/ai/collab_rules.md` |
| 商品・サービス | `wiki/pages/business/` | 商品ページを作成する |
| 雑談ログ・思考ログ | `logs/casual/` | `logs/casual/casual_logs.example.json` |
| 資料・講座・研修 | `docs/` | 該当テーマのフォルダ |

---

## 判断軸（迷ったら）

| ファイル | 内容 |
|---|---|
| `OS.md` | 最上位の判断基準 |
| `AI_COLLAB_RULES.md` | AIとの会話品質ルール |
| `wiki/pages/thinking/os.md` | Wiki化したOS |

---

## 実行環境メモ

- Pythonを使える環境では、データ整形・ログ検証・集計にPythonを使ってよい。
- `python` や `conda` がPATHで見つからない場合でも、すぐに「Pythonなし」と判断しない。
- Python実行が必要な場合は、conda環境、同梱Python、利用可能なランチャーを順に確認する。

---

## 運用方針

- チャットで終わらせず、重要な会話はログに残す。
- 再利用できる知識はWikiへ昇格する。
- AIの提案は材料であり、最終判断は人間が行う。
- 個人や顧客の判断権を奪う設計にしない。
