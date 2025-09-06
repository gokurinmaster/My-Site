# My Site (GitHub Pages)

## 公開までの手順

1. このリポジトリを GitHub に push する
   ```bash
   git add .
   git commit -m "Add static site (OGP, dark mode, sitemap, etc.)"
   git push origin main
   ```
2. GitHub のリポジトリページを開く
3. Settings -> Pages へ移動
4. Build and deployment の Source を "Deploy from a branch" に設定
5. Branch を `main` / `/ (root)` に設定して Save
6. 数分後、"Your site is live at ..." の URL が表示
7. 表示された URL にアクセスして動作確認

## 機能一覧
- OGP / Twitter カード meta タグ
- ダークモード (システム + 手動切替)
- 独自 404 ページ
- サイトマップ (sitemap.xml) & robots.txt
- Jekyll 無視化 (.nojekyll)
- SVG favicon
- MIT License
- About ページ (複数ページ構成サンプル)

## ファイル構成
```
.
├── index.html
├── about.html
├── 404.html
├── favicon.svg
├── sitemap.xml
├── robots.txt
├── .nojekyll
├── assets
│  ├── style.css
│  └── main.js
├── LICENSE
└── README.md
```

## カスタマイズポイント
| 項目 | 説明 |
|------|------|
| タイトル/説明 | index.html / about.html の &lt;title&gt;, meta description |
| OGP画像 | og:image の URL を実際ファイルに変更 (1200x630 推奨) |
| ダークモード初期値 | main.js の保存ロジックで調整可能 |
| カラーテーマ | assets/style.css のグラデーション & 色定義 |
| ページ追加 | 新しい .html を作成＋ナビゲーションリンク追加 |
| ライセンス | LICENSE を適宜変更 |

## 追加アイデア
- GitHub Actions で HTML Lint / Link Check
- 画像最適化 (webp, avif)
- PWA (manifest.json + Service Worker)
- アクセス解析 (Analytics / Plausible / Umami)

## ライセンス
MIT License
