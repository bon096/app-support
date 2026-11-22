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
- BatteryWatch：https://bon096.github.io/app-support/batterywatch/（privacy.html）
- おくすりシートカレンダー：https://bon096.github.io/app-support/photodiary/（privacy.html）
- チンチロ：https://bon096.github.io/app-support/chinchiro/（privacy.html）
- ルーレット：https://bon096.github.io/app-support/roulette/（privacy.html）
- スイスドロー：https://bon096.github.io/app-support/swissdraw/（privacy.html）

## 移行メモ

- 旧 `XXX-support` リポジトリ（habitboard-support／batterywatch-support／photodiary-support／chinchiro-support／roulette-support／swissdraw-support）から移行した。
- 旧リポジトリの `privacy-policy.html` は、集約後は `privacy.html` に統一した。
- `app-ads.txt` は全アプリ同一内容（同じAdMobパブリッシャーID）のため、ルートに1部置き、各アプリフォルダにも控えを置いている。

## 新しいアプリを追加するとき

1. アプリ名（小文字英字）のフォルダを作り、`index.html`／`privacy.html`／`terms.html` を置く
2. 各ページのスタイルシート参照は `../style.css`（共通スタイル）にする
3. ルートの `index.html` のアプリ一覧にリンクを追加する

お問い合わせ先：kuboshunsuke0906@gmail.com
