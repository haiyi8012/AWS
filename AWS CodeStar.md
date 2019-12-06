## eclipse 不能导入codestar问题
https://docs.aws.amazon.com/ja_jp/codecommit/latest/userguide/setting-up-gc.html#setting-up-gc-iam

# codestar Action 权限添加


##  AWS CodeCommit 
https://docs.aws.amazon.com/zh_cn/codecommit/latest/userguide/setting-up-https-unixes.html

## Eclipse に接続する
選択した内容は、プロジェクトの作成後にいつでも変更できます。
プロジェクトをインポートする前に、以下を行う必要があります。

IAM アクセスキー (アクセスキーとシークレットアクセスキー)
Git 認証情報 - ルートアカウントで Git を使用するには、AWS 認証情報ヘルパーを設定する必要があります。これは AWS CLI に含まれています。
ステップ 1: AWS Toolkit for Eclipse を取得する
「こちら」より、ダウンロードおよびインストールできます。
ステップ 2: AWS CodeStar プロジェクトをインポートする
Eclipse を開いて、AWS ツールバーボタンを選択し、[Import AWS CodeStar Project] を選択します。ウィザードに従って、プロジェクトをインポートします。
ステップ 3: Eclipse でコードを開始する
Package Explorer で、ツリーを展開してプロジェクトとそのファイルを表示します。コード作業を開始します。
ステップ 4: 変更をコミットしてプッシュする
Git Staging を開いて [Staged Changes] にファイルを移動し、コミットメッセージを入力したら、[Commit and Push] を選択します。
