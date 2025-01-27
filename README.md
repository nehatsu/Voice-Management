# Voice-Management
サーバーメンバーが通話時間によって役職の付与・解除を自動化ができるbotです。
サーバーの管理者がこのbotを利用してコマンドを作成し、メンバーは設定に応じて通話時間が付与・剥奪がされます。
## 入れる前にしてほしいこと
discordの使用上付与させたいロールがbotのロールの下にあるとロールが付与できない仕組みになっているので  
付与させたいロールとユーザーにもともとついている(メンバーロールなど)より上に設定してあげてください。
![image](https://github.com/user-attachments/assets/e639d4df-c56e-4e54-9359-09c66fdb5d26)

## 招待リンク
https://discord.com/oauth2/authorize?client_id=1285114704670228513&permissions=8&integration_type=0&scope=bot+applications.commands
## サポートサーバー
https://discord.gg/vz5GGc2uWC
## プライバシーポリシー
https://gist.github.com/nehatsu/031e68c0f3891005631e032b5fecdba7
# 使い方
/add_role　付与させたいロール　付与するのに必要な時間(hour)  
/remove_role 剝奪させたいロール　剥奪するのに必要な時間(hour)  
/sakujyo_add_role ロール名  
/sakujo_remove_role ロール名  
/list_roles | 登録されているロールの設定を表示できます。  
/sakujyo_setting | 通話時間を削除します。  
/rtuwa | サーバーでの通話時間のランキングを表示します。  
/ktwa | 指定したユーザーの通話時間を確認することができます。  
/vclog 指定したいチャンネル| vcの参加状況をログに残せます  
/deletevclog | vcの参加状況のログ設定を削除できます。  
/vcranking | vcの参加回数のランキングが見れます。  
