# 職務経歴書

## 基本情報
|||
|---|-----|
|Name|阿部俊幸(Abe Toshiyuki)|
|性別|男|

## 3年後の目標や野望
SREとして改善活動をやっていきたい

レガシーインフラ環境のAWS移行や自動化、コンテナ移行等

マネジメントを経験しプロダクトマネジャー、スクラムマスターとして力をつけたい


## 心がけていること

* 自動化できそうなところは積極的に自動化し手作業でのヒューマンエラーを無くし効率を向上させる

## スキルなど

### 言語
* 日本語
    * ネイティブ
* 英語
    * あやしい

### 経験言語 / IT
* Java
* Kotlin
* PHP
* Android
* JavaScript
* Go(REST API Server作る程度)
* Python(数ファイル構成のスクリプトを書く程度＋Djangoチュートリアル程度)
* Ruby(数ファイル構成のスクリプトを書く程度＋Ruby on Railsチュートリアル程度)
* TypeScript(JS使うプロジェクトで使った程度)

### フレームワーク使用経験
* PHP
    * Fuel PHP
        * 宅配買取サイトを構築時に経験。
        * 環境構築から管理画面・フロント画面等一通り担当し作成
    * Laravel(独学)
* Android
    * 古臭いMVC(Android 4.xの頃の開発)
        * 先輩エンジニアと2人でアプリ作成。
        * ベース部分以外の画面作成・リリース対応・バージョンアップ対応など
    * Flux[こちらを参考にしたパターン](https://github.com/oldergod/android-architecture/tree/todo-mvi-rxjava)
        * 業務で1人で1つのアプリ作り切る程度
        * 配車アプリであったのでログインやAPIとの通信、json取得しての画面表示等全て
    * ReactNative
        * 業務で複数画面の作成担当
        * CIで自動ビルド行える環境の作成
    * Android Architecture Components、 JetPack(独学)
* JS
    * React
        * 顧客要望である特定の画面のみSPA的にリッチな動きが必要になったので環境構築(Webpack)から対応
    * Vue(独学)
    * jQuery
* CSS
    * bootstrap
* Python
    * Django(独学)
* Ruby
    * Ruby on Rails(独学)

### OS
* Windows
    * 95、98、ME、XP、Vista、8、8.1、10、2003server、2008server、2013server
* Linux
    * Ubuntu(自宅サーバー・WSL等で利用)
        * 8.04 ~ 21.04
    * CentOS
        * 6 ~ 8
    * Kali Linux
        * 脆弱性診断時に使用
        
## 資格
* ネットワークスペシャリスト(2019年10月) 
* 情報処理安全確保支援士(2018年4月)
* 情報セキュリティスペシャリスト(2015年10月) 
* 応用情報技術者(2012年10月)
* ITIL V3 Foundation(2010年9月)
* 基本情報技術者(2008年4月)

***

# 職務経歴
## GMOペイメントゲートウェイ株式会社
|||
|---|-----|
|会社名|[GMOペイメントゲートウェイ株式会社](https://www.gmo-pg.com/)|
|待遇：期間|正社員： 2020年8月〜在職中|
|職種|インフラエンジニア、SREエンジニア|
|使用技術 サーバー|RHEL、Docker、Terraform、Ansible、Jenkins、ElasticSearch、LogStash、Kibana、filebeat|
|使用技術 クラウド|AWS(Cloudformation)<br>NewRelic、Statuspage、OpsGenie|
|使用技術 言語|Python、NodeJs|

### SREとしての業務概要
* NewRelicの導入・管理・運用・改善(ansibleで構成管理・Terraformでダッシュボード等のコード管理)
    * SLO・SLA等の計測や見える化・アラート設定で早期対応化など。
* OpsGenieの導入・管理・運用・改善（競合調査～選定から対応）
* Statuspageの導入・改善・運用（APIGW-Lambda-DynamoDBでアラート中継API構築）
* ElasticStackでのSIME基盤の管理・運用・改善(filebeat、LogStash、ElasticSearch、Kibana)
    * ログ量月間数TBのログ基盤でした。リソース問題の解決など。
### AWS運用管理担当としての業務概要
* 既存の社内ID管理基盤と連携してのAWS権限の自動付与
* 社内の開発基盤の運用・管理・改善(Git、Confluence、Jira、Jenkinsなど)
* 各サービスのAWSインフラの設計・構築・運用(Cloudformation)|

***

## 株式会社カタリストシステム
|||
|---|-----|
|会社名|[株式会社カタリストシステム](https://catalyst-system.jp/)|
|待遇：期間|正社員： 2013年10月〜2020年7月(6年9ヶ月)|
|職種|Webアプリケーションエンジニア、Android アプリエンジニア、インフラ・ネットワークエンジニア、DevOpsエンジニア、社内SE|
|使用技術 サーバー|CentOS、Debian、Ubuntu|
|使用技術 クラウド|AWS(EC2、RDS、ElastiCache、S3、Lambda、CloudWatch、CloudTrail、VPC、CloudFront、Route 53、AWS Auto Scaling、ELB)<br>GCP（Maps API、Logging、BigQuery、Firebase Real Time Database、Fabric）<br>ConoHa、さくらのクラウド、さくらのVPS|
|使用技術 言語|PHP、Java、Kotlin、JavaScript(jQuery、React.js、React Native|
### Webアプリケーションエンジニアとしての業務概要
主にPHPを使用して受託開発が主。  
後年はSPAの導入でフロントはReact.jsで記述することが多かったです。
デザインは外注であったので、出てきたデザインに合わせてといったパターンが多かったです。

### Androidアプリエンジニアとしての業務概要
社内唯一のAndroidアプリエンジニアとして、ライブラリの選定やアーキテクチャの選定から実装まで行なっていました。  
MVP、Clean Architecture、MVVM等をへてFluxで開発後JetPackへ移行。  
小規模アプリの開発のためにReactNativeでマルチプラットフォームのアプリ開発。  

### インフラ・ネットワークエンジニアとしての業務概要
社内のCisco機器の管理やWifiの管理  
Radius認証の導入やクライアント証明書の発行でセキュリティも考慮するようにしていました。

### DevOpsエンジニアとしての業務概要
下記DevOpsツールの導入・フォロー及びDockerの導入を主導。
* Ansible
* Docker
    * Docker Compose
    * Docker Hub
* Git(私が導入する前は日付付きファイルでした。。。)
    * GitHub
        * 他社との連携用。
        * Docker Hubと連携させDockerImageの自動生成用。
    * GitLab
        * 主にプロジェクト管理で使用。選定・構築・運用まで対応。
        * GitLab CIサーバーを社内に構築しレガシーインフラについてもCI/CDの対象とした。

Infrastructure as Codeを推進。DevOpsの旗振り役として導入推進。  
CI/CDを自分で導入し自動テスト・自動デプロイなどの環境構築などのDevOps環境を作成しました。

### 社内SEとしての業務概要
自社HPの開発やPCなどのIT資産管理、新入社員対応や退職者対応、PCのキッティングなど。

***

## 日本情報産業株式会社
|||
|---|-----|
|会社名|[日本情報産業株式会社](https://www.nii.co.jp/)|
|待遇：期間|正社員： 2008年4月〜2013年9月(5年5ヶ月)|
|職種|サーバーオペレーター、サーバー運営業務|
|役割|チームリーダー、総チーム人数: 18人、1勤務:4人程度|
|使用技術|Excel VBA<br>Access<br>HP-UX<br>Windows Server<br>Linux<br>JP1<br>ITIL|
#### 業務内容
国内大手損害保険会社でその会社様のサーバー(約2,000台)の監視業務。<br>障害発生時の１次切り分け、既知の障害時の対応業務。<br>サーバーの設定変更等の運営業務。<br>Excel VBAとAccessを使用しての業務アプリ作成。

***
# 経験業務詳細
## GMOペイメントゲートウェイ株式会社
### NewRelicの導入・管理・運用・改善
|||
|---|-----|
|期間|2020年10月～|
|職種|SRE|
|チーム|1人|
|使用技術|NewRelic、Terraform、Ansible|
#### 概要
前任より業務を引き継いで対応。  
前任はIaCを特に行っていなかったので、手作業で作成したリソースが多数ありそれをTerraformを用いてコード管理行えるようにしました。  
またオンプレミスサーバー上のNewRelicエージェントの管理のためAnsibleにてIaCしました。
その他NewRelicを導入している主要サービスについて計測したデータの分析、自動化のソースとして活用し、主要サービスの信頼性向上に役立てました。

***
### OpsGenieの導入・管理・運用・改善
#### 概要
|||
|---|-----|
|期間|2020年11月～|
|職種||
|チーム|3人|
|使用技術||

***
### Atlassian Statuspageの導入・改善・運用
|||
|---|-----|
|期間|2021年03月～|
|職種|SRE|
|チーム|1人|
|使用技術|Atlassian Statuspage、Lambda、Amazon API Gateway、Amazon DynamoDB、AWS CodeBuild、Amazon Elastic Container Registry、AWS CloudFormation|
#### 概要
一部顧客より提供主要サービスの障害連絡の迅速化を求められていたため、NewRelicのアラート発報を契機としてAtlassian Statuspageと連携し、障害連絡の迅速化を行いました。  
Atlassian Statuspage用意のAPIをそのままNewRelicと連携するだけでは求める機能が実現できなかったため、AWS環境にLambdaバックのAPI Gateway、state管理はDynamoDBを使用してサーバーレスAPIを構築。

***
### 社内の開発基盤の運用・管理・改善
|||
|---|-----|
|期間|2021年04月～|
|職種|インフラエンジニア|
|チーム|3人|
|使用技術|Amazon WorkSpaces、AWS CodeCommit、AWS CodeBuild、EC2、Lambda|
#### 概要
主にAWS上に構築した社内開発関連サーバー等の運用管理業務。
* 協力会社の社員の作業環境としてWorkSpacesを提供しており、ベースイメージの管理や異常時の対応等を行う。
* Git、Svn、Jenkins、Nexus、Jira、Confluence、Redmine等の開発系サーバーの運用管理
* 各AWSアカウントへ共通環境として提供しているAWSリソースの運用管理


***
### 各サービスのAWSインフラの設計・構築・運用・管理
|||
|---|-----|
|期間|2020年08月～|
|職種|インフラエンジニア|
|チーム|3人|
|使用技術(管理部分)|AWS Organizations、AWS Security Hub、AWS Personal Health Dashboard、AWS CloudFormation、AWS CloudTrail、VPC、AWS Direct Connect、IAM、AWS Key Management Service、AWS Secrets Manager、Amazon Connect、Savings Plans|
|使用技術(サービス部分)|Amazon Elastic Container Service、AWS Fargate、Amazon Elastic Container Registry、Amazon Aurora、Amazon DynamoDB、ElastiCache、Amazon Kinesis、EC2、Lambda、Amazon API Gateway、Amazon CloudFront、Amazon Route 53、Amazon VPC PrivateLink、ACM、AWS WAF、S3、AWS CodeBuild、AWS Backup、SES|
|使用技術(運用部分)|Amazon Athena、AWS Step Functions、SNS、SQS、AWS Systems Manager、AWS CodeDeploy、AWS CodePipeline、AWS CloudShell、EventBridge|
#### 概要
1. プロジェクト毎などに用意する開発用、検証用、本番用など各種社内の全AWSアカウントをAWS Organizationsにて管理し、AWS Security HubやAWS Personal Health Dashboard、AWS Configを利用してセキュアで金融業界に適合したインフラ環境を社内に提供し管理・運用・改善を行いました。
1. 各プロジェクトのAWSでの構築時にAWSインフラについてアカウント作成から各種サービス構成の構築をAWS CloudFormationを用いて自動構築出来るようにし、各アプリ開発チームと共同しインフラの運用を行いました。

***
## 株式会社カタリストシステム

### 社内SE・ITインフラエンジニア業務
|||
|---|-----|
|運用期間|2013年9月～2020年7月|
|職種|社内SE・ネットワークエンジニア・インフラエンジニア|
|チーム|2人|
|使用技術 サーバー|CentOS、KVM、Docker、Docker Compose、Ansible、GitLab、GitLab CI、Cisco、FreeRadius|
|使用技術 クラウド|AWS（）<br>GCP（）<br>さくらのVPS|
#### 概要
先輩社員と2人で業務分担しながら対応。記載しているものは私が対応したもののみとなります。
* 社内開発環境の整備

#### 課題
複数人が1つのサーバで開発し(共有ディスクにSMBでアクセス)、バージョン管理は日付を古いファイルに付ける方式で開発を行っていた。  
サーバには複数のhttpdやPHPをインストールし、ポートによってhttpdやPHPのバージョンなど動作環境を切り替え開発を行っていた。  
ネットワークも1つの/24に社員全員が所属しておりセキュリティ皆無であった。  
開発環境の改善は在職期間中ずっと行っており、概ね下記のように進めました。

1. Gitの導入
    * まず日付管理はバージョン管理が行えていなく、品質に問題を来していたのでGitを導入することにしました。
    * Gitを導入し社員に対して環境移行のコーチング等の他改善・運用を行った。
1. プロジェクト毎に環境分離
    * 1台のサーバーに全ての開発環境が乗っており環境を分離出来ていないことによるバグが頻発していた。
    * 仮想基盤サーバーを新規購入しKVMを利用して各プロジェクト毎にVMを切り分けて再構築。
1. ネットワーク・セキュリティの対応
    * ローカル固定IPはルーター内臓のDHCPにより付与しており、そのIPアドレスで開発環境内の各プロジェクトの参照制限を行っていました。
    * 悪意があれば自分でIPを設定し、担当外プロジェクトにアクセス可能であった。
    * 改善策としてCisco製品を導入しVLANで各ネットワークを分離しアクセス制御を導入した。
    * FreeRadiusを使用してRadiusサーバーを構築。
        * クライアント証明書により各開発者のPCを識別しVLANが固定されるようにした。
            * これにより開発者が自分でIPを付け替えて高権限者になりすますことを防止した。
    * 無線LANは後述するように家庭用機器であったので、ゲストVLAN固定でインターネットのみ利用可能なように。
      開発者は机上に配線したLanケーブルを使用しないと業務が行えない状態でした。
1. Wifi機器リプレース
    * 既にサポートの終了していた家庭用Wifiルーターを使用し社内無線LANを使用していた。
    * Cisco製品の無線LANアクセスポイントを購入し、EAP-TLS認証の無線LAN環境を構築し上記のクライアント証明書を利用して各開発者が無線LANでも自分の所属しているVLANへ参加することが出来るようになり、フリーアドレスで業務が行えるようになりました。
    * 構築後もクライアント証明書の発行・失効対応等が必要となる実装になりましたが、会社が小規模であったためよしとしました。
1. メールサーバ冗長化
    * 社外用メールサーバが1台で運用されている状態であるため、障害時に不通となる問題がありメールサーバの冗長化のためにサーバを新規で1台構築。
    * DNSの優先度設定を調整することにより障害時にはサブメールサーバーが利用され不通とならないようにしました。
1. GitLab導入
    * 1にて導入したGitはローカル及び管理機能のないサーバーの導入であったので権限管理などに課題を抱えていたためGitLabを導入しWeb画面での管理機能の増強を図りました。
    * GitLabの機能により権限を詳細に付与することによりセキュリティも向上させることが出来ました。
    * GitLabを導入することによってMergeRequest(以降MRと呼称)が活用される文化を作ることが出来ました。
        各開発者はMRを作成しレビュー依頼することにより、プルリクエストと同様に変更箇所のみをレビューしてもらうことが可能となり、品質向上に役立てました。
1. GitLab改善
    * 初期はVMにyumで導入。後期はDockerにて構築しました。
        * yumから切り替えた理由は長期間バージョン固定をしていた場合にyumでのバージョンアップが困難になってしまった反省から、Docker化し更新を容易にすることで四半期毎に更新するスキームへと変更し新機能の取り込みとバージョンが離されすぎることを抑止しました。
    * GitLab CI/CDを導入し、別途作成していたAnsibleプレイブックを自動実行することによって構成管理を自動化しました。
          構成管理を自動化することにより各担当はそれぞれのボタンを対応もしくはスケジュールによって自動構成された結果を確認するのみで各種サーバーの管理業務を行うことが出来るようになりました。
    * GitLab CI/CDを使用してテストの自動実行や、検証環境と本番環境へ自動リリースを行える仕組みを整えるなどDevOpsが行えるレベルまで改善を行いました。

***

### IX会社でのNW障害監視サーバー構築の自動化
|||
|---|-----|
|開発期間|2019年9月～2020年5月|
|職種|インフラ・ネットワークエンジニア|
|チーム|2人(開発メンバーとして参加)|
|使用技術 サーバー|CentOS7、Ansible、Nagios、munin、VMware ESXi6|
|使用技術 言語|Python、Shell script|
#### 概要
NW機器の障害監視用のサーバー(約100台)の構築するためのAnsibleプレイブックの整理統合案件（客先常駐）
障害監視用のサーバー構築用のAnsible及びサーバー内ソフトウェアの設定用リポジトリが複数個に分かれており、システム全体の見通しが悪いので1つに纏めるとの案件。<br>かつ更改後のAnsibleプレイブックを用いて既存の監視サーバーを更改する。<br>仮想化基盤がVmwareであったので、Terraform等を使って一度に構築できればよかったが、特殊環境のため動かず、Pythonスクリプトで操作を自動化し再構築しました。<br><br>ただただ顧客の歴史を紐解くのが大変な業務であった。

***

### IX会社でのログ基板の再構築
|||
|---|-----|
|開発期間|2019年5月～8月|
|職種|インフラ・ネットワークエンジニア|
|チーム|2人(開発メンバーとして参加)|
|使用技術 サーバー|CentOS7、Fluentd、Prometheus、Grafana|
|使用技術 クラウド|Google StackDriver Logging|
|使用技術 言語|Ruby、Go、Python|
#### 概要
各ネットワーク機器から出力されるログを収集分類検知を行い適切にアラート発報するためのシステムの改修案件（客先常駐）
syslogやSNMPを用いログをpythonスクリプトで分類検知を長年行ったため、複雑化。<br>PrometheusとAlertManagerを用いて通報、ログ全体はfluentdで収集し、追加で作成したfluentdの独自プラグインで分類後にGoogle StackDriver Loggingへ転送しビックデータ活用も可能なようにしたいという要望があり、対応しました。<br>Google StackDriver Loggingへ蓄積したログをあるパラメータで規定件数取得しSPAの画面上に表示したいという要望もあり、それはGoでAPIサーバーを作成しました。

### 配車アプリの開発・運用
|||
|---|-----|
|開発期間|2017年9月～2018年12月|
|運用期間|2019年10月～2019年3月|
|職種|Android アプリエンジニア、Webアプリケーションエンジニア、インフラ・ネットワークエンジニア|
|役割|Androidアプリリーダー、WEB 管理画面・API開発メンバー、バックエンドリーダー|
|チーム|3人|
|使用技術 サーバー|CentOS7、Postgresql、Apache Http、Redis、Docker、Docker Compose、Ansible、GitLab CI/CD|
|使用技術 クラウド|AWS（EC2、RDS、ElastiCache、CloudWatch、Lambda、S3、Code Deploy）<br>GCP（GCP Maps API、Firebase Real Time Database、Fablic）|
|使用技術 言語|PHP7.2、Fuel PHP、React Native、Kotlin、Swift4.2|
#### 概要
スマホアプリ部分はB2Cでユーザーが車種を選んだ上で配車先、下車先をアプリ内のマップでピンを立て予約を行うような形でした。  
WEBアプリは主にB2Bで管理画面が主となっており、ユーザーが予約した配車予約をオークション形式(時間が経つごとに価格が上がるルール)で落札した予約の管理や配車を行える車両や人員を業者ごとに登録してもらい管理を行うような物でした。  
チーム人数は3人。プロダクトオーナーは別です。  
スクラムで開発を行いスプリントは1週間でした。

#### 私の役割
* スマホアプリ部分
    * クロスプラットフォーム開発として選定したReact Nativeでの開発とAndroid部分の開発です。
　* CI/CDで自動的にアプリをビルドし、テストプラットフォームでのテスト実行やストア公開が自動的に行えるような自動化の対応を行いました。
* WEBアプリ部分
    * 主に車両の管理やスケジュール管理部分を担当しました。
* インフラ部分
    * サービスのスケールアップを考えサーバーはAWSに設置し、負荷状況によりオートスケールされるようにしました。
    * インフラもAnsibleやCI/CDで自動的に構築出来るように構成し、Gitでコード管理を行えるよう作成しました。

***

### 不動産検索サイトのリニューアル開発・運用
|||
|---|-----|
|開発期間|2016年1月～2019年11月（開発一時停止2017年9月～2018年12月）|
|運用期間|2019年8月～2020年7月|
|職種|Webアプリケーションエンジニア、インフラ・ネットワークエンジニア|
|役割|WEB 管理画面開発メンバー、インフラリーダー|
|チーム|外注含め最大時10人|
|使用技術 サーバー|CentOS7、Postgresql、Apache Http、Redis、Docker、Docker Compose、Ansible、GitLab CI/CD、Mysql(旧システムがmysqlで移行用)|
|使用技術 クラウド|AWS（EC2、RDS、ElastiCache、CloudWatch、Lambda、S3）<br>GCP（Maps API）|
|使用技術 言語|PHP7.2、Fuel PHP|
#### 概要
2000年代に他社で特にフレームワークを用いないで開発されたWebのリニューアル案件。  
開発リーダーとして開発に参画当初チーム4人。  
リニューアル案件ということだったが他社が開発したシステムの情報は頂けない中移行計画含め対応。  
2017年9月に管理画面側を作成完了するも、お客様先都合で一時開発ストップ。  
開発再開時には初期メンバーは私しか残っていない状況で新規に外注とインターンが1名ずつ、社員3人が追加されフロント画面および開発停止期間中に既存システム側での変更等について対応等を行い、開発終了まで開発できました。  
開発リーダーとしては主にコードレビューお客様と仕様調整を行いました。  
期間が空いてしまったことによる開発メンバー間の認識相違が発生していたり技術力差の大きい状況であったため、レビューを行いやすくするためにマージリクエスト毎に自動でレビュー環境が立ち上がるように自動デプロイの仕組みを導入したり、自動E2Eテストを実行出来るようにしてデグレが起きにくい環境を構築し自動化によって品質向上しました。

#### 課題
既存のプログラムがPHP1ファイルで6000行あるようなレガシーであり全ての機能を既存踏襲で新規作成する必要がある。  
会員のアクセスコントロールを行いながらGoogle Map上に物件情報をピン立てを行いグラフィカルにしたいという要望がありました。  
最寄り駅までの徒歩時間の計算を自動で行うようにしたいという要望がありました。

#### 成果
レガシープログラムをFuelPHPを用いてモダンな形式にリファクタリングすることが出来ました。  
Google map APIを利用して徒歩時間やマップ上に物件情報を表示することも出来ました。

***

### 自社開発の販促用のアプリ開発・運用
|||
|---|-----|
|開発期間|2016年6月～2016年12月|
|職種|Android アプリエンジニア、Webアプリケーションエンジニア、インフラ・ネットワークエンジニア|
|役割|Androidアプリリーダー、WEBAPI開発メンバー、インフラリーダー|
|チーム|全体で3人<br>WEB専任：1人、iOS、WEB兼任：1人、Android、WEB兼任：1人|
|使用技術 サーバー|CentOS6、postgresql、Apache Http、Redis|
|使用技術 クラウド|AWS|
|使用技術 言語|Java、RxJava、OpenCV、OkHttp-Retrofit、Picasso、PHP、Fuel PHP|
#### 概要
家具の試着アプリのようなものを開発
Androidアプリの開発を1人で担当。<br><br>以前のAndroidプロジェクトの失敗を踏まえ、非同期処理はRxJavaを使用することとし、OSSを積極利用して車輪の再発明をしないようにしました。<br><br>バックエンドAPIサーバのPHPプログラムを3人のチームで開発。  <br><br>サーバの設計・構築  <br>開発環境の開発、検証機の設計・構築、本番機の設計構築を行いました。  <br><br>PHPの開発環境は各自のPC上でVitualboxのVMを立ち上げ、ローカルで開発しGitLabでレビューを行う形式でした。  <br>検証環境は社内の仮想化基盤上に検証サーバーを構築し、検証サーバー内にsshでログインの上git pull等のコマンドで行う手作業方式としていました。  <br>本番環境はAWS EC2でRDSとElastiCacheを使用するオーソドックスな構成を構築しました。  <br><br>結局見込みのお客様に断られたため、プロジェクトは終了となりました。<br>

***

### Webサイトの脆弱性チェックサイト構築・開発・運用
|||
|---|-----|
|開発期間|2016年3月～2016年6月|
|運用期間|2016年6月～現在|
|職種|Webアプリケーションエンジニア、インフラ・ネットワークエンジニア|
|役割|設計～構築～運用|
|チーム|1人|
|使用技術|さくらのクラウド、CentOS、PHP、Fuel PHP、mysql、Apache Http、Redis|
#### 概要
サーバーサイドのセキュリティスキャンを、スキャン対象にアクティベートファイルを設置するだけで、簡単に実行出来るようにするサービスの構築
機能としては難しいところは特に無く、各種脆弱性チェックツールを即時もしくは指定時刻に実行し結果を表示するだけなのでWEB画面の開発は問題ありませんでした。<br><br>時間がかかったのは下記件についてプロダクトオーナーとの調整でした。<br>どの脆弱性チェックツールを使用できるようにするのか  <br>ツール実行時の詳細度についての調整  <br>実行結果の保持期限<br>サーバーのランニングコストなどの調整<br>

***

### 携帯端末の宅配買取アプリ開発・運用
|||
|---|-----|
|開発期間|2015年3月～2016年1月|
|運用期間|2016年1月～2016年10月|
|職種|Android アプリエンジニア、Webアプリケーションエンジニア、インフラ・ネットワークエンジニア|
|役割|開発メンバー|
|チーム|4人|
|使用技術|*&nbsp;Android：MVP(ほぼ自作)<br>*&nbsp;Web：CentOS6、Apache、PHP、Postgresql、Redis|
#### 概要
先行で開発が進んでいたプロジェクトに途中から参加しました。<br><br>その時点で完成度60％程度で2014年6月ごろリリース予定でした。<br>お客様よりビジネスロジックの変更の要望があり要件が大幅に変更され、完成が2016年1月にずれ込みました。<br><br>インフラエンジニア・Androidアプリエンジニアとして参加。<br>私はAndroidアプリの開発、バックエンドAPIサーバの設計・開発・構築・運用を担当しました。<br>サーバはCentOS Apache PHP Postgresqlの構成で構築し、<br>サーバサイドの開発はFuelPHPを使用してAPI部分及び管理画面の開発を行いました。

***

### 宅配買取サイト構築・開発・運用
|||
|---|-----|
|開発期間|2014年10月～2015年2月|
|運用期間|2015年2月～2020年7月|
|職種||
|チーム|人|
|使用技術||
#### 概要
宅配買取のためのHP構築。<br><br>FuelPHPを使用してフロント画面及び管理画面の開発を行いました。<br>サーバ構築 CentOS Apache PHP Postgresql。<br>脆弱性対応等の運用も継続して実施。

***

## 日本情報産業株式会社
|||
|---|-----|
|案件名|損保会社常駐案件|
|期間|2008年04月～2013年09月|
|職種|サーバーオペレーター、サーバー運用|
|チーム|チームリーダー、総チーム人数: 18人 、1勤務:4人程度|
|使用技術|Excel VBA、MS Access、HP-UX、Windows Server、Linux、JP1、ITIL|
#### 業務内容
* システム運用業務等を受託にて客先常駐の形で請負。
    * 常駐総員数は60名程度。
* 私の居たチームは国内大手損害保険会社でその会社様のサーバー(約2,000台)の監視業務。
    * 主にデータセンター内のWindowsサーバー、Linuxサーバー及び日本全国のネットワーク機器など
        * 障害発生時の１次切り分け、障害時の対応業務
            * サービス運営担当者と電話でやり取りしながら様々なOSにログインしての状況確認など
    * サーバーの設定変更等の運営業務
        * セキュリティのためサービス担当者はサーバーへログイン不可であるので運用担当者が代わりにサーバー内のログの収集やコマンド実行を代行する仕組みでした。
    * Excel VBAとAccessを使用しての業務アプリ作成
        * 監視ツールの仕様により監視統計が取得できなかったので監視連絡記録用サーバーのOracleDBに保存されたデータをAccessを使用して取得、Excel VBAで集計するプログラムを作成
        * 金融系データーセンターのためインターネットに出ることが出来ない環境の中、独学で開発し以後のキャリアの礎となれたと自負。

***
# その他
## SNSなど
|||
|---|-----|
|[Blog](https://toshi.click/)|
|[Twitter](https://twitter.com/toshibe_678)|
|[GitHub](https://github.com/toshi-click)|
|[GitLab](https://gitlab.com/toshi-click)|
|[Facebook](https://www.facebook.com/click.toshi.3)|
|[LinkedIn](https://www.linkedin.com/in/toshiyuki-abe-78bb37142/)|
|[Wantedly](https://www.wantedly.com/users/18247131)|
|[Qiita](https://qiita.com/toshi-click)|
|[Lancers](https://www.lancers.jp/profile/toshi1986)|
|[CrowdWorks](https://crowdworks.jp/public/employees/756845/resumes#resumes)|
