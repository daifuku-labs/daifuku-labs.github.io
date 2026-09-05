# daifuku-labs.github.io（公開 URL は https://daifuku-labs.com/・2026-09-06 に独自ドメイン化）

Daifuku Labs の公開サイト（GitHub Pages）。アプリのサポートページ・プライバシーポリシー・app-ads.txt を置く。

## ファイルツリー

```
.
├── index.html                        # トップ（アプリ一覧・連絡先）
├── melody-eraser/
│   ├── privacy-policy.html           # メロディ消しゴムのプライバシーポリシー（日英）
│   └── support.html                  # メロディ消しゴムのサポートページ（FAQ・連絡先）
├── app-ads.txt                       # AdMob の販売者宣言（IAB app-ads.txt）
├── .nojekyll                         # Jekyll ビルドを無効化（素のHTMLをそのまま配信）
└── README.md                         # 本ファイル
```

## ファイル説明

- **index.html** — サイトの入口。アプリごとのページへのリンクと連絡先（support@daifuku-labs.com・Cloudflare Email Routing で Gmail へ転送）
- **melody-eraser/** — アプリ「メロディ消しゴム」の公開ページ一式。App Store Connect の
  プライバシーポリシーURL・サポートURLはここを指す
- **app-ads.txt** — 広告枠の正規販売者を宣言する IAB 標準ファイル。AdMob が参照する
- **.nojekyll** — GitHub Pages の Jekyll 処理を止め、静的ファイルをそのまま配信させる
