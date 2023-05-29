# Browse with regular expression

指定したURL先のソースコードをダウンロードして、指定した正規表現と一致する文字列を抽出するアプリです。

更新通知機能、ループ機能付きです。

https://play.google.com/store/apps/details?id=com.browsewithregularexpression.regularexpressionbrowsing1&hl=ja

# 実行例

実行結果1

Google検索にアクセスしてタイトルを抽出

<img src="https://raw.githubusercontent.com/ShiraoTakuya/Browse-with-regular-expression/main/cap1.png" width="25%">

実行結果2

Google検索でGoogleと検索した結果から検索結果のURLとタイトルを抽出

<img src="https://raw.githubusercontent.com/ShiraoTakuya/Browse-with-regular-expression/main/cap2.png" width="25%">

# Usage

以下の手順を行う
* アプリをインストールして起動する
* Title欄に任意の文字列を入れる

　入力した文字列は通知の際に表示される
* URL欄に監視したいURLを入れる
* ソースコードから抽出したい文字列を正規表現で指定する

　該当する正規表現がない場合はSETTINGSタブで正規表現を設定する
* RUNボタンを押して待機する
* 結果が表示される

必要に応じて、以下のボタンをON/OFFしてください。
* Repeatボタン: 指定した時間おきにURL先を自動で確認します
* Update Notificationボタン: 結果に変更があったときに通知されます
* Error Notificationボタン: Errorが発生したときに通知されます

ダウンロードしたソースコードを見たい場合は、結果が表示された後に"Open source"をクリックすると表示されます。

# Note
 
* 開発言語はKotlinです。
* 本アプリのコードは非公開です。気になった方は連絡ください。
 
# Author
  
* ShiraoTakuya
