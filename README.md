# Grimoire.js 勉強会 @ LIFULL資料置き場

## 共通

* [公式サイト](https://grimoire.gl)
* [Githubレポジトリ(コア)](https://github.com/GrimoireGL/GrimoireJS)
* [Devtool](https://chrome.google.com/webstore/detail/grimoirejs-devtool/omimnfbmgdcigbdpehonlfbjhdajakhn?hl=ja)
* [スライド置き場](https://drive.google.com/drive/u/1/folders/0Bx1zL-xVze-GVmZzNDV2TlhUTUk)

# Grimoire.jsとは

* [スライド(とても重いので注意!)](https://kyasbal-1994.github.io/wejs/)

# 基礎編

* [レポジトリ](https://github.com/GrimoireGL/tutorial2)

# 応用編

* [サンプルコードレポジトリ](https://github.com/GrimoireGL/tutorial3)
* [解説記事](http://qiita.com/moajo/items/ca1b1de7bffbe3b591c7)

# その他参考になる記事など

* [寿司](https://pnlybubbles.github.io/custom-sushi-3d/)
* [Grimoire.jsでシェーダーを書く](http://qiita.com/kyasbal_1994/items/cff1466719934f461ca8)
* [今回の勉強会の内容に近い動画(DeNA勉強会での動画)](https://crash.academy/class/92/)

# トラブルシューティング

## ローカルサーバーの建て方がわからない

Macの場合はターミナルから簡単に起動する方法があるが、どの環境でも動くChromeプラグインを使うのが一番おすすめ。
[Chrome Web Server](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=ja)

### ファイルスキームでテスト用にアクセスしたい場合

`file://`でアクセスされるとブラウザはセキュリティ上の理由からAjaxリクエストをすることができません。
そのため、もし必要な場合は解説する`goml`ファイルなどをHTMLに埋め込むことによって一時しのぎができます。この場合でも画像ファイルなどは外部から読み込むことはできますが、モデルファイルなどはAjaxリクエストを内部で飛ばしてコンテンツを取得するためできません。

## `git command was not found`などと表示される(応用編でcauldronを使用時)

gitへPATHが通っていないと利用することができない。PATHを通してください。
