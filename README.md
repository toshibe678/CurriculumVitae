# 職務経歴書

## 基本情報
|key|value|
|---|-----|
|Name|阿部俊幸(Abe Toshiyuki)|
|性別|男|

## 心がけていること

自動化できそうなところは積極的に自動化しヒューマンエラーを無くす

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
* Python(数ファイル構成のスクリプトを書く程度＋Django)
* Ruby(数ファイル構成のスクリプトを書く程度＋RoR)
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
    * Android Architecture Components, JetPack(独学)
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
    * 95,98,ME,XP,Vista,8,10
* Linux
    * Ubuntu(自宅サーバー・WSL等で利用)
        * 8.04 ~ 18.04
    * CentOS
        * 6 ~ 8
    * Kali Linux
        * 脆弱性診断時に使用
        
## 資格
* 情報処理安全確保支援士(2018年4月)
* 情報セキュリティスペシャリスト(2015年10月) 
* 応用情報技術者(2012年10月)
* ITIL V3 Foundation(2010年9月)
* 基本情報技術者(2008年4月)

# 職務経歴
## 概要
### 株式会社カタリストシステム
|key|value|
|---|-----|
|会社名|[株式会社カタリストシステム](https://catalyst-system.jp/)|
|待遇：期間|正社員： 2013/10月〜現在|
|職種|Webアプリケーションエンジニア<br>Android アプリエンジニア<br>インフラ・ネットワークエンジニア<br>DevOpsエンジニア<br>社内SE|
|役割|インフラリーダー<br>Androidアプリリーダー|
|開発環境|言語：PHP、Java、Kotlin、JavaScript(jQuery、React.js、React Native）<br>OS：CentOS、Debian、Ubuntu<br>IaaS：Amazon EC2、ConoHa、さくらのクラウド、さくらのVPS<br>AWS：EC2、RDS、ElastiCache、S3、Lambda、CloudWatch、CloudTrail、VPC、CloudFront、Route 53、AWS Auto Scaling、ELB<br>GCP：Maps API、Logging、BigQuery、Firebase Real Time Database、Fabric|
|業務内容|社内唯一のAndroidアプリエンジニアとして、ライブラリの選定やアーキテクチャの選定から実装まで行なっています。<br>MVP、Clean Architecture、MVVM等をへてFluxで開発後JetPackへ移行。<br>小規模アプリの開発のためにReactNativeでマルチプラットフォームのアプリ開発。<br>インフラエンジニアとしては、Ansible及びDockerの導入を主導し、Infrastructure as Codeを推進。DevOpsの旗振り役として導入推進。<br>CI/CDを自分で導入し自動テスト・自動デプロイなどの環境構築などのDevOpsも推進中|

### 日本情報産業株式会社
|key|value|
|---|-----|
|日本情報産業株式会社|正社員: 2008/4月〜2013/9月)(5年5ヶ月)|
|職種|サーバーオペレーター<br>サーバー運営業務|
|役割|チームリーダー<br>総チーム人数: 18人  <br>1勤務:4人程度|
|使用技術|Excel VBA<br>Access<br>HP-UX<br>Windows Server<br>Linux<br>JP1<br>ITIL|
|業務内容|国内大手損害保険会社でその会社様のサーバー(約2,000台)の監視業務。<br>障害発生時の１次切り分け、既知の障害時の対応業務。<br>サーバーの設定変更等の運営業務。<br>Excel VBAとAccessを使用しての業務アプリ作成。|

## 経験業務詳細

### IX会社でのNW障害監視サーバー構築の自動化
|key|value|
|---|-----|
|概要|NW機器の障害監視用のサーバー(約100台)の構築するためのAnsibleプレイブックの整理統合案件（客先常駐）|
|開発期間|2019年9月～現在|
|職種|インフラ・ネットワークエンジニア|
|チーム|2人(開発メンバーとして参加)|
|使用技術|※&nbsp;サーバー：CentOS7,Ansible,Nagios,VMware ESXi6.7<br>※&nbsp;言語：Python|
|詳細|障害監視用のサーバー構築用のAnsible及びサーバー内ソフトウェアの設定用リポジトリが複数個に分かれており、システム全体の見通しが悪いので1つに纏めるとの案件。<br>かつ更改後のAnsibleプレイブックを用いて既存の監視サーバーを更改する。<br>仮想化基盤がVmwareであったので、Terraform等を使って一度に構築できればよかったが、特殊環境のため動かず、Pythonスクリプトで操作を自動化し再構築しました。<br><br>ただただ顧客の歴史を紐解くのが大変な業務であった。|

### IX会社でのログ基板の再構築
|key|value|
|---|-----|
|概要|各ネットワーク機器から出力されるログを収集分類検知を行い適切にアラート発報するためのシステムの改修案件（客先常駐）|
|開発期間|2019年5月～8月|
|職種|インフラ・ネットワークエンジニア|
|チーム|2人(開発メンバーとして参加)|
|使用技術|※&nbsp;サーバー：CentOS7,Fluentd,Prometheus,Grafana<br>※&nbsp;クラウド：Google StackDriver Logging<br>※&nbsp;言語：Ruby,Go,Python|
|詳細|syslogやSNMPを用いログをpythonスクリプトで分類検知を長年行ったため、複雑化。<br>PrometheusとAlertManagerを用いて通報、ログ全体はfluentdで収集し、追加で作成したfluentdの独自プラグインで分類後にGoogle StackDriver Loggingへ転送しビックデータ活用も可能なようにしたいという要望があり、対応しました。<br>Google StackDriver Loggingへ蓄積したログをあるパラメータで規定件数取得しSPAの画面上に表示したいという要望もあり、それはGoでAPIサーバーを作成しました。|

### 配車アプリの開発・運用
|key|value|
|---|-----|
|概要|B2B2Cアプリ<br>アプリ利用者が配車を予約出来る。<br>アプリ・管理画面で業者とマッチングする<br>配車依頼したい業者と配車依頼を受けられる業者のマッチングも行う。|
|開発期間|2017年9月～2018年12月|
|運用期間|2019年10月～2019年3月|
|職種|Android アプリエンジニア<br>Webアプリケーションエンジニア<br>インフラ・ネットワークエンジニア|
|役割|Androidアプリリーダー<br>WEB 管理画面・API開発メンバー<br>バックエンドリーダー|
|チーム|3人|
|使用技術|サーバー<br>CentOS7<br>postgresql<br>Apache Http<br>Redis<br>使用技術<br>Docker<br>Docker Compose<br>Ansible<br>AWS EC2、RDS、ElastiCache、CloudWatch、Lambda、S3、Code Deploy<br>GCP Maps API、Firebase Real Time Database、Fablic<br>GitLab CI/CD<br>言語<br>PHP7.2<br>自社製の独自フレームワーク(非公開) <br>React Native<br>Kotlin<br>Swift4.2|
|詳細|TODO 詳細もっと書く<br>ドライバーアプリリリース済み<br>アプリのリリースは自動化|

### 不動産検索サイトのリニューアル開発・運用
|key|value|
|---|-----|
|概要|2008年に構築したサイトのリニューアル案件<br>上場企業の主力サイトだが重いとの苦情が出てきたため全面更新する<br>仕様書は無く、現在のコードから仕様を読み解く必要がある<br>DBのテーブル構成を改善し現行DBから移行する|
|開発期間|2016年1月～2019年11月（開発一時停止2017年9月～2018年12月）|
|運用期間|2019年8月～現在|
|職種|Webアプリケーションエンジニア<br>インフラ・ネットワークエンジニア|
|役割|WEB 管理画面開発メンバー<br>インフラリーダー|
|チーム|外注含め最大時10人|
|使用技術|Docker<br>Docker Compose<br>Ansible<br>AWS：EC2、RDS、ElastiCache、CloudWatch、Lambda、S3<br>GCP：Maps API<br>GitLab CI/CD<br>サーバー<br>CentOS7<br>PHP7<br>自社製の独自フレームワーク(非公開) <br>Postgresql<br>Mysql(旧システムがmysqlで移行用)<br>Apache Http<br>Redis|
|詳細|TODO 辛かった点や改善した点とか書く|

### 自社開発の販促用のアプリ開発・運用
|key|value|
|---|-----|
|概要|家具の試着アプリのようなものを開発|
|開発期間|2016年6月～2016年12月|
|職種|Android アプリエンジニア    <br>Webアプリケーションエンジニア    <br>インフラ・ネットワークエンジニア|
|役割|Androidアプリリーダー    <br>WEBAPI開発メンバー    <br>インフラリーダー|
|チーム|<br>全体で3人       <br>WEB専任：1人、iOS、WEB兼任：1人、Android、WEB兼任：1人|
|使用技術|<br>Java  <br>RxJava  <br>OpenCV  <br>OkHttp-Retrofit  <br>Picasso<br>AWS<br>CentOS6  <br>PHP7    <br>自社製の独自フレームワーク(非公開)   <br>postgresql  <br>Apache Http  <br>Redis|
|詳細|Androidアプリの開発を1人で担当。<br><br>以前のAndroidプロジェクトの失敗を踏まえ、非同期処理はRxJavaを使用することとし、OSSを積極利用して車輪の再発明をしないようにしました。<br><br>バックエンドAPIサーバのPHPプログラムを3人のチームで開発。  <br><br>サーバの設計・構築  <br>開発環境の開発、検証機の設計・構築、本番機の設計構築を行いました。  <br><br>PHPの開発環境は各自のPC上でVitualboxのVMを立ち上げ、ローカルで開発しGitLabでレビューを行う形式でした。  <br>検証環境は社内の仮想化基盤上に検証サーバーを構築し、検証サーバー内にsshでログインの上git pull等のコマンドで行う手作業方式としていました。  <br>本番環境はAWS EC2でRDSとElastiCacheを使用するオーソドックスな構成を構築しました。  <br><br>結局見込みのお客様に断られたため、プロジェクトは終了となりました。<br>|

### 社内開発環境改善
|key|value|
|---|-----|
|概要|Gitlabを構築・運営<br>レビュー文化の啓蒙<br>Infrastructure as Code推進<br>DevOpsの実践|
|運用期間|2016年3月～現在も改善中|
|職種|インフラ・ネットワークエンジニア<br>社内SE|
|チーム|1人|
|使用技術|CentOS7<br>Docker<br>Docker Compose<br>Ansible<br>GitLab<br>GitLab CI <br>さくらのVPS|
|詳細|Git導入後はただバージョン管理としてのみしか使用していませんでした。  <br>そこでGitの管理していくことを提案し対応することとなりました。  <br>当初はGitHub Enterpriseで管理を提案しましたが、社外にコードを公開したくないという社長の意向もあり、GitLabをオンプレミスで構築し運用することになりました。  <br>その結果Issue管理などを管理出来るようにし、相互レビューの利点を上層部に訴え、採用していただき社内にレビュー文化を根付かせ品質の向上に成功しました。  <br><br>その後の施策としてAnsibleを使用してInfrastructure as Code化し、GitLab CIを使用してテストの自動実行や、検証環境と本番環境へ自動リリースを行える仕組みを整えるなどDevOpsを実践中です。<br>|

### Webサイトの脆弱性チェックサイト構築・開発・運用
|key|value|
|---|-----|
|概要|サーバーサイドのセキュリティスキャンを、スキャン対象にアクティベートファイルを設置するだけで、簡単に実行出来るようにするサービスの構築|
|開発期間|2016年3月～2016年6月|
|運用期間|2016年6月～現在|
|職種|Webアプリケーションエンジニア<br>インフラ・ネットワークエンジニア|
|役割|設計～構築～運用|
|チーム|1人|
|使用技術|さくらのクラウド<br>サーバー　<br>CentOS6　<br>PHP5.6　　<br>自社製の独自フレームワーク(非公開) 　<br>mysql　<br>Apache Http　<br>Redis|
|詳細|機能としては難しいところは特に無く、各種脆弱性チェックツールを即時もしくは指定時刻に実行し結果を表示するだけなのでWEB画面の開発は問題ありませんでした。<br><br>時間がかかったのは下記件についてプロダクトオーナーとの調整でした。<br>どの脆弱性チェックツールを使用できるようにするのか  <br>ツール実行時の詳細度についての調整  <br>実行結果の保持期限<br>サーバーのランニングコストなどの調整<br>|

### 社内無線LAN構築・運用
|key|value|
|---|-----|
|概要|2008年製のWifi機器(家庭用Wifi)のリプレース<br>EAP-TLS認証の無線LAN環境を構築しセキュリティ向上<br>FreeRadiusサーバーも構築し、証明書インストール運用を行い社内機器のセキュリティ向上を果たしました。<br>構築後もクライアント証明書の発行・失効対応等を行っています|
|開発期間|2015年12月～2016年1月|
|運用期間|2016年1月～現在|
|職種|社内SE|
|チーム|1人|
|使用技術|Cisco　<br>FreeRadius|

### 携帯端末の宅配買取アプリ開発・運用
|key|value|
|---|-----|
|概要|先行で開発が進んでいたプロジェクトに途中から参加しました。<br><br>その時点で完成度60％程度で2014年6月ごろリリース予定でした。<br>お客様よりビジネスロジックの変更の要望があり要件が大幅に変更され、完成が2016年1月にずれ込みました。<br><br>インフラエンジニア・Androidアプリエンジニアとして参加。<br>私はAndroidアプリの開発、バックエンドAPIサーバの設計・開発・構築・運用を担当しました。<br>サーバはCentOS Apache PHP Postgresqlの構成で構築し、<br>サーバサイドの開発はFuelPHPを使用してAPI部分及び管理画面の開発を行いました。|
|開発期間|2015年3月～2016年1月|
|運用期間|2016年1月～2016年10月|
|職種|<br>Android アプリエンジニア    <br>Webアプリケーションエンジニア    <br>インフラ・ネットワークエンジニア|
|役割|開発メンバー|
|チーム|4人|
|使用技術|*&nbsp;Android：MVP(ほぼ自作)<br>*&nbsp;Web：CentOS6、Apache、PHP、Postgresql、Redis|

### 宅配買取サイト構築・開発・運用
|key|value|
|---|-----|
|概要|宅配買取のためのHP構築。<br><br>FuelPHPを使用してフロント画面及び管理画面の開発を行いました。<br>サーバ構築 CentOS Apache PHP Postgresql。<br>脆弱性対応等の運用も継続して実施。|
|開発期間|2014年10月～2015年2月|
|運用期間|2015年2月～現在|

### 権威DNSサーバの構築・運用
|key|value|
|---|-----|
|概要|一定時間ごとにDNSの設定を切り替えていきたいという案件により、権威DNSサーバを2台構成で構築。<br><br>脆弱性対応等運用も行いました。|
|開発期間|2014年4月～2014年6月|
|運用期間|2014年6月～現在|

### メールサーバ冗長化
|key|value|
|---|-----|
|概要|メールサーバが1台で運用されている案件にて、メールサーバの冗長化のためにサーバを新規で1台構築。|
|開発期間|2014年2月～2014年3月|
|運用期間|2014年3月～現在|

### 社内開発環境構築・運用
|key|value|
|---|-----|
|概要|複数人が1つのサーバで開発し(共有ディスクにSMBでアクセス)、バージョン管理は日付を古いファイルに付ける方式。<br>サーバには複数のhttpdやPHPをインストールし、ポートによってhttpdやPHPのバージョンなど動作環境を切り替え開発を行っていた。<br>ネットワークも1つの/24に全員が所属していた。<br><br>Gitを導入し、仮想基盤サーバに各プロジェクト毎にVMを切り分けて再構築。<br>ネットワークはcisco製品を導入しVLANでアクセス制御を導入した。<br><br>社員に対して環境移行のコーチング等の他改善・運用も担当した。|
|開発期間|2014年2月～2014年9月|
|運用期間|2014年9月～現在|

# その他
### SNS塔
|key|value|
|---|-----|
|Blog|[toshi.click](https://toshi.click/)|
|Twitter|[@toshi_click](https://twitter.com/toshi_click)|
|GitHub|[toshi_click \(toshi-click\)](https://github.com/toshi-click)|
|GitLab|[toshi-click](https://gitlab.com/toshi-click)|
|Facebook|[click.toshi.3](https://www.facebook.com/click.toshi.3)|
|LinkedIn|[toshiyuki](https://www.linkedin.com/in/toshiyuki-abe-78bb37142/)|
|Wantedly|[阿部俊幸](https://www.wantedly.com/users/18247131)|
|Qiita|[toshi-click](https://qiita.com/toshi-click)|
|Lancers|[ToshiyukiAbe](https://www.lancers.jp/profile/toshi1986)|
|CrowdWorks|[ToshiyukiAbe](https://crowdworks.jp/public/employees/756845/resumes#resumes)|
