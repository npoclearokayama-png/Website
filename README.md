# Website

GitHub Pages向けのシンプルな1ページ構成のコーポレートサイトです。

## 構成

- `index.html`
- `assets/style.css`
- `assets/app.js`

## GitHub Pages 公開手順

1. このリポジトリをGitHubにpushする。
2. GitHubのリポジトリページで **Settings** を開く。
3. 左メニューの **Pages** を開く。
4. **Build and deployment** の **Source** で `Deploy from a branch` を選択する。
5. Branchを `main`（または公開したいブランチ）/ `/(root)` に設定して **Save**。
6. 数分待つと公開URL（`https://<username>.github.io/<repository>/`）が表示される。

## ローカル確認

```bash
python3 -m http.server 8000
```

ブラウザで `http://localhost:8000` を開いて表示を確認できます。
