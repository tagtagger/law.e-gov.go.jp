# 法令HTMLファイル

総務省e-govの「[法令データ提供システム][lawjp]」にある法令のHTMLファイル（廃止・未施行含む）とそれに付随する画像ファイルを全取得してそのままアップロードしました。
ディレクトリ構造も一部（最終改正までの未施行法令のディレクトリ）を除いて「[法令データ提供システム][lawjp]」と同じになっていると思います。

## 注意点

そのままファイルを利用するときには以下の点に注意してください。

* HTMLファイルのエンコードがUTF-8ではなく、Shift-JISかEUC-JPのどちらかになっています。
* リンクが絶対パスのままになっているので画像がうまく表示されませんし、リンクをクリックしても他のページに飛ぶことができません。
* 元々フレームでのページレイアウトを想定しているため、ファイル内リンクをクリックしても新規ウィンドウが開きます。

## 更新履歴

* 2015/04/05 : 更新
* 2015/01/06 : 更新
* 2014/11/25 : 更新 + htmldataに「登録略称法令名一覧」追加
* 2014/11/08 : 作成

[lawjp]:http://law.e-gov.go.jp/cgi-bin/idxsearch.cgi
