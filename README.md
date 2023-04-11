## 自己紹介
エンジニアのcalmandhelp（かむ）です。  
金融系のプロジェクトを3年、営業系のプロジェクトを半年を程経験しました。  
主に扱う技術はJava(Spring framework)、React.js（Next.js）、AWSなどです。  

技術の詳細については追加していきます。

## ポートフォリオ
植物の生育を記録するサービス「ボータピア」というSNSを開発しました。 （ボータピアは植物のボタニカルと仲間という意味のピアーズとユートピアを合わせた造語）  
なるべく市場で求められる技術を使いながら、徐々に大きくしていった個人プロジェクトになります。  
リポジトリは4つに分かれております。  

- [botapeer-core](https://github.com/calmandhelp/botapeer-core)  
  - バックエンドリポジトリ
    - Spring boot
      - Spring MVC
      - Spring Security
    - クリーンアーキテクチャ
    - JUnit5（単体テスト）
    - Docker（開発環境、デバッグ環境、テスト環境などをdocker-composeしております。コマンドはmakeで叩きます）
    - MySQL、MyBatis, Flyway
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
  - インフラプリポジトリ
    - Terraform
    - AWS(VPC, VPC endpoint,EC2, ECS, ESR S3, RDS, ALB, SSM Parameter Store, CloudFront, App Runner, CloudWatch, Route53, ACM)
- [botapeer-openapi](https://github.com/calmandhelp/botapeer-openapi)
  - OpenAPIリポジトリ
    - GitHub Actions
