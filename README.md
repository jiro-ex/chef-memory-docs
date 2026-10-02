# chef-memory-docs

ChefMemory アプリの利用規約・プライバシーポリシーを GitHub Pages で公開するリポジトリ。
アプリ（cook-memo-app）は以下の URL を WebView で表示している（`src/constants/legal.ts`）。

- 利用規約: https://jiro-ex.github.io/chef-memory-docs/terms.html
- プライバシーポリシー: https://jiro-ex.github.io/chef-memory-docs/privacy.html

## 構成

- `terms.html` / `privacy.html` — 本文（素の HTML。Jekyll は `.nojekyll` で無効化）
- `style.css` — 共通スタイル
- `index.html` — 各ページへのリンク

## 本文を更新するとき

- 該当 HTML を直接編集し、`main` に push すると数分で Pages に反映される
- 内容を変更した場合は「制定日」の下に「改定日：YYYY年M月D日」を追記する
- ファイル名（URL）を変えるとアプリ側のリンクが切れるため変更しない
- 外部スクリプトやアクセス解析は入れない（プライバシーポリシー「6. Cookie等の取扱い」と整合させるため）
