# ホワイトリスト更新手順

## 1. PRの作成

1. ホワイトリスト更新用のブランチを作成し、ユーザの追加
2. ブランチをプッシュし、PRを作成
3. レビューを受け承認を得る
4. PRをマージする

## 2. Firebase Realtime Databaseの更新

1. <https://console.firebase.google.com/u/4/project/web-pg/database/web-pg-default-rtdb/data> を開く
   ![firebase-realtime-database](images/firebase-realtime-database-1.png)
2. 三点リーダーから「JSON をインポート」を選択
   ![firebase-realtime-database 三点リーダーメニュー](images/firebase-realtime-database-2.png)
3. whitelist.json のmainブランチ最新版を選択し、「インポート」を選択
   ![firebase-realtime-database インポート](images/firebase-realtime-database-3.png)
   ![firebase-realtime-database インポートファイル選択後](images/firebase-realtime-database-4.png)
4. whitelistを展開し、ユーザが追加されていることを確認
   ![firebase-realtime-database 更新後](images/firebase-realtime-database-5.png)
