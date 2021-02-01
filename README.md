# Den4-Architecture
大学チャットアプリのREST API設計

[![swagger](https://img.shields.io/badge/swagger-docs-brightgreen)](https://den-3.github.io/Den4-Architecture/dist/index.html)

REST API どう作る?

DBの機能とHTTPリクエストの対応
(Create Update Read Delete) -> (POST PUT GET DELETE)

扱うデータの最小単位
- サーバー
 - チャットルーム
  - チャット

- ユーザー

Create:
- サーバーを作る
- チャットルームを作る
- チャットルームを作る
- ユーザーがサーバーに参加する

Update:
- サーバーの情報を更新する
- チャットルームの情報を更新する
- チャットの情報を更新する

Read:
- サーバーの情報を取得する
- チャットルームの情報を取得する
- チャットの情報を取得する

Delete:
- サーバーを削除する
- チャットルームを削除する
- チャットを削除する

Other:
- 連携ログインの入り口
- 連携ログイン後のCallBack
 - 大学アカウントではなければここで追い出す
- ログアウト
- アカウントの削除
