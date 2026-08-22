# farst-support

**配信は [farst.me](https://farst.me) に移りました。このリポジトリは旧URLの受け皿です。**

- 現在のページ: <https://farst.me/support/>
- 中身の原本: [`benihisago88/farst`](https://github.com/benihisago88/farst) の `web/support/`

`index.html` はリダイレクトだけを行うページで、内容は持ちません。
**ここを編集しても公開ページは変わりません。** 内容を直すときは統合先のリポジトリで。

GitHub Pages は任意の 301 を返せないため、`meta refresh` + `canonical` で
新URLへ寄せています（`noindex` は付けていません。付けると評価が新URLへ
渡る前に旧URLが落ちるため）。

App Store Connect に登録された URL を新ドメインへ入れ替えたあとも、
外部からの被リンクがあるうちはこのリポジトリを消さないこと。
