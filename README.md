# AI活用研修 — NotebookLM演習用サイト

NotebookLMのソースインポート演習（第3回：まめまめ珈琲Webサイト企画）で使用するダミーサイトです。

## ファイル一覧

| ファイル | 内容 | 役割 |
|---|---|---|
| `harenohicoffee.html` | ハレノヒ珈琲（代官山） | 競合サイトA |
| `sakuracoffee.html` | さくら珈琲（吉祥寺） | 競合サイトB |
| `cafe-success-article.html` | 地域に根差すカフェ経営の秘訣5選 | 成功事例記事 |
| `index.html` | リンク一覧ページ | — |

## GitHub Pages で公開する手順

```bash
# 1. GitHubで新しいリポジトリを作成（例：cafe-training-sites）
# 2. ローカルでgit初期化してpush
git init
git add .
git commit -m "Add cafe training sites"
git remote add origin https://github.com/YOUR_USERNAME/cafe-training-sites.git
git push -u origin main

# 3. GitHub → Settings → Pages → Source を「main / (root)」に設定
# 4. 数分後に以下のURLでアクセス可能
# https://YOUR_USERNAME.github.io/cafe-training-sites/
```

## 研修での使用URL（GitHub Pages公開後）

スライドのURL欄に以下を記入してください：

- **競合サイトA：** `https://YOUR_USERNAME.github.io/cafe-training-sites/harenohicoffee.html`
- **競合サイトB：** `https://YOUR_USERNAME.github.io/cafe-training-sites/sakuracoffee.html`
- **成功事例記事：** `https://YOUR_USERNAME.github.io/cafe-training-sites/cafe-success-article.html`
