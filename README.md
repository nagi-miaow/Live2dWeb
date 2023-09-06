# CubismSdkForWeb を使ったデモ

## セットアップ
- CubismSdkForWebの中身からCore,Framework,Samplesディレクトリをコピペ
- もともとあった、Demoフォルダ内にコンソールで入ってyarn install及びyarn build

## 起動
- なぜかyarn serveが失敗するのでVSCodeのGo Liveなど使って起動
- localhost:xxxx/Demo/ にアクセスすればモデル表示されるはず

## ちょっといじったとこ
- HTML側に制御書きたかったのでGlobalに制御モデルをエクスポート
- デフォではランダムにモーションが表示されるが、ボタンでモーションを切り替えられるように変更
- 色々いじったので、ほかにもデフォから変わってるところがあるかも
