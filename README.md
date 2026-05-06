# ASO VOLCANO ペース計算ツール

Google Apps Script 版の計算ロジックを、Vercel にそのままデプロイできる静的 Web アプリにしたものです。

## ローカル確認

```bash
python3 -m http.server 4173
```

ブラウザで `http://localhost:4173` を開きます。

## Vercel デプロイ

このフォルダを GitHub に置いて Vercel に Import すれば動きます。ビルドコマンドは不要です。

Vercel CLI を使う場合:

```bash
vercel
```

## 構成

- `index.html`: UI、スタイル、計算ロジックを含む本体
- `vercel.json`: 静的サイトとして配信するための設定
