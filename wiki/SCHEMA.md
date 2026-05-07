# Wiki Schema

## フォルダ構造

```text
wiki/
├── index.md
├── SCHEMA.md
├── log.md
└── pages/
    ├── ai/
    ├── business/
    └── thinking/
```

---

## ページの基本形

```markdown
# ページタイトル

> 1行説明。

## 概要

## 詳細

## 関連ページ

## ソース

## 最終更新
YYYY-MM-DD
```

---

## ログとWikiの違い

- `logs/` は会話・素材・一次情報。
- `wiki/pages/` は再利用する知識。
- ログをそのままWikiに貼らず、要約・整理して昇格する。

---

## 更新ルール

1. 関連ページを確認する。
2. 新規または既存ページを更新する。
3. `wiki/index.md` にリンクを追加する。
4. `wiki/log.md` に操作ログを書く。
