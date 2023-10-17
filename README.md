## 自己紹介
広告代理店でマークアップエンジニアとして2年、プログラミングを行うエンジニアとしては4年ほどの経験があります。

React.js（Next.js）、Typescript、Java(Spring framework)、AWSなどがメインで活動しております。 
ポートフォリオは現在停止しているためソースコードのみご確認いただけます。

## ポートフォリオ
植物の生育を記録するアプリケーションを開発しました。  
技術用にキャッチアップしてきた個人プロジェクトになります。
リポジトリは4つに分かれております。詳細につきましてはそれぞれのリポジトリにまとめております。

- [botapeer-core](https://github.com/calmandhelp/botapeer-core)  
  - バックエンドリポジトリ
   - Spring boot
    - Spring MVC
    - Spring Security
   - クリーンアーキテクチャ
   - JUnit5（単体テスト）
   - Docker（開発環境、デバッグ環境、テスト環境などをdocker-composeしております。コマンドはmakeで叩きます）
   - MySQL、MyBatis、Flyway
   - GitHub Packages（openapi）
   - 本番環境はECS
- [botapeer-front](https://github.com/calmandhelp/botapeer-front)
  - フロントエンドリポジトリ
   - Next.js(React)
   - Material UI
   - emotion
   - サブモジュール（openapi）
   - 本番環境はApp Runner
- [botapeer-infra](https://github.com/calmandhelp/botapeer-infra)
  - インフラリポジトリ
   - Terraform
   - AWS(VPC, VPC endpoint,EC2, ECS, ESR S3, RDS, ALB, SSM Parameter Store, CloudFront, App Runner, CloudWatch, Route53, ACM)
- [botapeer-openapi](https://github.com/calmandhelp/botapeer-openapi)
  - OpenAPIリポジトリ
   - GitHub Actions
   - GitHub Packages

以下が現在公開されているポートフォリオです。（現在停止中）
[https://botapeer.com/](https://botapeer.com)

### ポートフォリオの使い方（現在停止中）
1.会員登録を行います（ユーザー名やメールアドレスは適当なものをお使いください。メールアドレスはEmail形式であれば通ります）  
2.ログインを行います  
3.編集→プロフィールを入れていただきます。（画像などは適当な画像をお使いください）  
4.生育記録作成→適当な花や植物の名前と場所を入力し、作成をします。  
5.アカウント画面に戻ると持っている植物にデフォルト画像が追加されています。  
6.デフォルト画像をクリックします。  
7.投稿を追加します  
8.生育記録が投稿できます。写真、タイトル、投稿内容は適当なものを入力します。  
9.アカウント画面の生育記録のデフォルトが画像が8.で投稿した画像に変わります。  
10.生育記録を選択し、8.で投稿された画像をクリックします。  
11.投稿記事をいいねしたり、削除したりできます。  

※開発中のため実装されていない機能等あります。

## 開発環境
- MacBook Pro（Intelチップ）
- IntelliJ
- GitHub Copilot
