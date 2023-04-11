## 自己紹介
エンジニアのcalmandhelp（かむ）です。  
金融系のプロジェクトを3年、営業系のプロジェクトを半年経験しました。  
主に扱う技術はJava(Spring framework)、React.js（Next.js）、AWSなどです。  

このページの情報は随時追加していきます。

## ポートフォリオ
植物の生育を記録するサービス「ボータピア」というSNSを開発しました。 （ボータピアは植物のボタニカルと仲間という意味のピアーズとユートピアを合わせた造語）  
なるべく市場で求められる技術を使いながら、徐々に大きくしていった個人プロジェクトになります。  
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

## 開発環境
- MacBook Pro（Intelチップ）
- IntelliJ
- GitHub Copilot
