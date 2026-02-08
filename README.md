# NPO法人くりあー Webサイト

NPO法人くりあーの公式サイトを想定した、GitHub Pages向けのレスポンシブな1ページ構成です。
目的は「信頼形成」「参加導線」「継続支援（寄付・参画）」を明確に伝えることです。

## ページ構成（1ページ内セクション）

- Hero
- 目的別導線（事業内容 / 団体紹介 / 参加支援 / 活動報告）
- 事業サマリー（療育支援・啓発/社会教育・相談支援・地域食堂/交流）
- 団体について（理念・設立趣旨・団体概要）
- 活動報告・お知らせ
- 参加・支援する
- 情報公開（Transparency）
- お問い合わせ

## ファイル構成

- `index.html`
- `assets/style.css`
- `assets/app.js`

## GitHub Pages 公開手順

1. このリポジトリを GitHub に push する。
2. GitHub のリポジトリページで **Settings** を開く。
3. 左メニューの **Pages** を開く。
4. **Build and deployment** の **Source** で `Deploy from a branch` を選択する。
5. Branch を `main`（または公開したいブランチ）/ `/(root)` に設定して **Save** する。
6. 数分待つと公開 URL（`https://<username>.github.io/<repository>/`）が表示される。

## 補足: データ保存について

GitHub Pages は静的ホスティングのため、フォーム送信内容を直接保存する仕組みは持ちません。
問い合わせや申込の保存が必要な場合は、外部フォームサービスまたは API（サーバーレス含む）を連携してください。

## ローカル確認

```bash
python3 -m http.server 8000
```

ブラウザで `http://localhost:8000` を開いて表示を確認できます。
