# app-support

iOSアプリのサポートページ・プライバシーポリシー・利用規約を、アプリごとにフォルダを分けて1つのリポジトリで管理し、GitHub Pagesで公開するためのリポジトリです。

## 構成

- `index.html` — アプリ一覧ポータル
- `style.css` — 全アプリ共通スタイル
- `<アプリ名>/index.html` — サポートページ（よくある質問・お問い合わせ）
- `<アプリ名>/privacy.html` — プライバシーポリシー
- `<アプリ名>/terms.html` — 利用規約

## 公開URL（GitHub Pages有効化後）

- ポータル：https://bon096.github.io/app-support/
- HabitBoard：https://bon096.github.io/app-support/habitboard/
  - プライバシーポリシー：https://bon096.github.io/app-support/habitboard/privacy.html
  - 利用規約：https://bon096.github.io/app-support/habitboard/terms.html

## 新しいアプリを追加するとき

1. アプリ名（小文字英字）のフォルダを作り、`index.html`／`privacy.html`／`terms.html` を置く
2. 各ページのスタイルシート参照は `../style.css`（共通スタイル）にする
3. ルートの `index.html` のアプリ一覧にリンクを追加する

お問い合わせ先：kuboshunsuke0906@gmail.com
