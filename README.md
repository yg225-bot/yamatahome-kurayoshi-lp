# なんでもやまた LP

Vercelで公開するための静的LPです。

## 公開ファイル

- `index.html`
- `styles.css`
- `assets/lp-01.png`
- `assets/lp-02.png`
- `assets/lp-03.png`

## 開発

```sh
npm install
npm run dev
```

## ビルド

```sh
npm run build
```

Vercelでは以下を設定します。

- Framework Preset: Vite
- Build Command: `npm run build`
- Output Directory: `dist`
- Root Directory: repository root

## Supabase設定

VercelのEnvironment Variablesに以下を登録します。

```sh
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=
```

ローカル開発では `.env.local` に同じ値を設定できます。`.env.local` はコミットしません。

接続確認ページ:

```txt
/debug/supabase/
```

このページではURLやキーの全文は表示しません。`service_role` keyはフロントエンド、Vercel公開環境変数、READMEに保存しないでください。

## 問い合わせリンク

各画像内のボタンは以下のフォームへ遷移します。

https://forms.gle/nvrckKxxC1wyfp976
