# My Site (GitHub Pages)

## 公開までの手順

1. このリポジトリを GitHub に push する
   ```bash
   git add .
   git commit -m "Add initial static site"
   git push origin main
   ```
2. GitHub のリポジトリページを開く
3. Settings -> Pages へ移動
4. Build and deployment で Source を "Deploy from a branch" に設定
5. Branch を `main` / `/ (root)` に設定して Save
6. 数十秒?数分後、"Your site is live at ..." の URL が表示
7. 表示された URL へアクセスし動作確認

## カスタマイズ
- `index.html` を編集してコンテンツを変更
- `assets/style.css` でデザイン調整
- `assets/main.js` に JavaScript を追加

## ディレクトリ構成
```
.
├─ index.html
└─ assets
   ├─ style.css
   └─ main.js
```

## 追加 Tips
- `favicon.ico` を置けばブラウザアイコンを変更可能
- カスタムドメイン: Settings -> Pages -> Custom domain で設定 (DNS に A / CNAME 追加)
- 404 ページ: `404.html` を追加すると独自404が利用される
- Jekyll 無効化: 生成を避けたい場合は `.nojekyll` ファイルを追加

## ライセンス
必要に応じて `LICENSE` を追加してください。
