●以下を参考にテスト構築
https://qiita.com/shshimamo/items/76db04d5a367aa84ca92#route53%E3%81%AE%E8%A8%AD%E5%AE%9A

●AWS CLIがインストール済み、IAMユーザーが作成済みであることを前提とする。

●コマンド（configure）を使って認証情報を設定する時の注意事項
aws configure --profile [好きな名前]
https://qiita.com/suuungwoo/items/66f39ac1d12c7a800d98

●ECRにdockerをプッシュする時に、credentialsのエラーが出たときの対処
コマンド前半の--region [region]を--profile [profile name]に変更する必要があり
https://qiita.com/noz_mikally/items/970b340caab59e8afb2e