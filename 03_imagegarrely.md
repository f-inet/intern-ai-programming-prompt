以下の条件でWEBアプリのGASコードを書いてください。

# 概要
画像ギャラリーアプリ

# 表示するもの
- 画像をドラッグ・アンド・ドロップでアップロードするエリア
- 画像リスト

# 仕様
- 画像をドラッグ・アンド・ドロップすると、画像がGoogleDriveにアップロードされ、画像のパスはGoogleスプレッドシートに保存される
- Googleスプレッドシートに保存された画像パスに従って、画像のリストが表示される
- 画像リストの画像をクリックすると、拡大画像がポップアップ表示される
- 拡大画像ポップアップの右上には削除ボタン（×ボタン）が表示され、クリックすると選択した画像が削除される
- 拡大画像ポップアップの枠外をクリックすると、拡大表示が消える

# 必須条件
- index.html と code.gs ファイルのコードを書く
- css、JavaScriptはindex.htmlに書く
- code.gs に doGet() を記載する
- モバイル表示に適したデザインにしてください
- GoogleDriveのフォルダIDおよびGoogleスプレッドシートIDは、GASのプロパティサービスから読み込む
