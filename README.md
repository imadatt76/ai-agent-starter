# AI エージェント スターターキット

Claude Code（AIエージェント）を自分のPCで動かすためのテンプレートです。

---

## セットアップ手順

### 1. Node.js をインストール

https://nodejs.org からLTS版をダウンロードしてインストール。

インストール後、確認：
```
node --version
```

### 2. Claude Code をインストール

```
npm install -g @anthropic-ai/claude-code
```

確認：
```
claude --version
```

### 3. このフォルダをVS Codeで開く

VS Codeでこのフォルダを開いて、ターミナルで：

```
claude
```

と打つと起動します。

---

## このテンプレートの構成

```
ai-agent-starter/
├── CLAUDE.md        ← AIへの指示を書くファイル（ここが起点）
├── wiki/
│   └── example.md  ← 自分の情報を入れる場所
└── products/
    └── sample.md   ← 商品・サービス情報を入れる場所
```

---

## 使い方

1. `CLAUDE.md` を自分用に書き換える
2. `wiki/` に自分の情報を追加する
3. `products/` に自分の商品・サービス情報を入れる
4. Claude Codeを起動して話しかける

---

## デモ例

```
「デスクトップにhello.txtを作って、中に"はじめてのAIエージェント"と書いて」
```

```
「products/sample.mdを読んで、おすすめ商品を3つ提案して」
```
