### JSUG 勉強会


<span style="font-size:28px">AWSで作るクラウドネイティブアプリケーションの基本とDevOps</span>


2019.9 @KoheiKawabata

---

### 自己紹介

<p><img src="images/profile.jpg" style="float:left" width="40%"></p>
<ul style="float:right">
  <div style="font-size:18px">
  <li style="margin: 10px 0px 10px">名前：川畑 光平(KAWABATA Kohei)</li>
  <li style="margin: 10px 0px 10px">会社：(株)NTTデータ</li>
  <li style="margin: 10px 0px 10px">今の仕事：<span style="font-size:18px">プロジェクト支援(主にクラウド系)とR&amp;D</span></li>
  <li style="margin: 10px 0px 10px"><a href="https://aws.amazon.com/jp/blogs/psa/japan-apn-ambassador-2019/" target="_blank">2019 APN AWS Top Engineers &amp; Ambassadors</a></li>
  <li style="margin: 10px 0px 10px">マイナビ「ITSearch+」で記事連載中</li>
  </div>
</ul>

---

### 本日のトピックス

![image](images/cloud-native.jpg)
![image](images/devops.jpg)


---

### その前に…

---

### How to use this slide

<br />

- [「reveal.js」](https://github.com/hakimel/reveal.js){:target="_blank"}を使って、GitHub Pages上に作成
- 黄色の文字はリンク
- ESCキーを押すとスライドのオーバービュー
- Altキー + マウスクリックで拡大ズーム
- J,K,M,Lキーでも遷移(Vimユーザ朗報)
- 幾つかのスライドは下に遷移

***

### Article Topics


![image](images/cloud-native.jpg)

<span style="font-size:32px">AWSクラウドでよく利用される基本的なサービスの構築方法や、SpringBootをベースとしたアプリケーションを実装する際の基本事項をまとめた連載記事</span>

---

#### サーバレス編

![image](images/serverless.png)

<ul>
  <span style="font-size:24px">
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4316" target="_blank">(1)Spring Cloud Functionを使ったLambdaファンクション実装</a></li>
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4318" target="_blank">(2)AWS Lambdaの設定</a></li>
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4321" target="_blank">(3)Amazon API Gatewayの設定</a></li>
  </span>
</ul>

---

#### ECSコンテナ編

<img src="images/ecs-architecture.png" style="float:left" width="50%"/>
<ul style="float:right">
  <div style="font-size:18px">
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4354" target="_blank">(4)VPC(Virtual Private Cloud)の構築</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4359" target="_blank">(5)ALB(Application Load Balancer)の構築</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4363" target="_blank">(6)SpringBootを使ったアプリケーション実装</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4390" target="_blank">(7)アプリケーションのDockerイメージの作成</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4405" target="_blank">(8)ECSクラスタの構築</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4408" target="_blank">(9)ECSタスクの定義</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4416" target="_blank">(10)ECSサービスの実行</a></li>
  </div>
</ul>
---

#### RDS(PostgreSQL)編

<img src="images/rds_setting_overview.png" width="80%"/>

<ul>
  <div style="font-size:32px">
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4422" target="_blank">(11)RDS(RelationalDatabaseService)の構築</a></li>
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4426" target="_blank">(12〜13)Spring Cloud AWSとSpring Data JPAを使った実装</a></li>
  </div>
</ul>
---

#### NoSQL編

<img src="images/database-cap-category.png" width="80%"/>

---

#### NoSQL編

<ul>
  <div style="font-size:32px">
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4473" target="_blank">(14)NoSQL基礎解説(CAP定理による分類)</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4479" target="_blank">(15)NoSQL基礎解説(AP型データベースの特徴)</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4498" target="_blank">(16)AmazonDynamoDBの構築</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4506" target="_blank">(17〜18)Spring Data DynamoDBを使った実装</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4523" target="_blank">(19)ローカルRedisServerの構築</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4525" target="_blank">(20〜21)Spring SessionとSpring Data Redisを使った実装</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4543" target="_blank">(22)AmazonElastiCacheの構築</a></li>
  <li style="margin: 10px 0px 10px"><a href="https://news.mynavi.jp/itsearch/article/devsoft/4566" target="_blank">(23〜24)セッション共有するECSアプリケーション実装</a></li>
  </div>
</ul>

---

#### S3編

<img src="images/S3Access.png" width="70%"/>

<ul>
  <div style="font-size:24px">
    <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4447" target="_blank">(25)AmazonS3バケットの構築とアップロード</a></li>
    <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4566" target="_blank">(26〜27)SpringCloudAWSを使ったファイルダウンロード・アップロード実装</a></li>
  </div>
</ul>

---

<span style="font-size:24px">STSを使ったクライアントからのS3へのファイルアップロード・ダウンロード</span>

<img src="images/S3DirectAccess.png" width="70%"/>

<ul>
  <div style="font-size:24px">
    <li>AWSで作るクラウドネイティブアプリケーション発展編(仮)で解説予定</li>
    <li><a href="https://github.com/debugroom/mynavi-sample-aws-s3/tree/master/src/main/java/org/debugroom/mynavi/sample/aws/s3/app/web/helper" target="_blank">今のところ実装のみ作成</a></li>
  </div>
</ul>

---

#### SQS編(今月から)

<img src="images/sqs-pattern.png" width="60%"/>

<ul>
  <div style="font-size:24px">
    <li>SQS+SpringCloudAWSを使用したオンライン非同期処理パターン(Producer)</li>
    <li>ディレードバッチやクラウドサービスイベントトリガーパターン</li>
    <li>SQS+SpringCloudAWS+SpringBatch+ECSTaskScheduler(Consumer)</li>
    <li><a href="https://github.com/debugroom/mynavi-sample-aws-sqs" target="_blank">今のところ実装のみ作成</a></li>
  </div>
</ul>


***
***
### Article Topics

![image](images/devops.jpg)

<span style="font-size:32px">マイクロサービスアーキテクチャアプリケーションでDevOpsや基盤自動化する際の基本事項をまとめた連載記事</span>


---

<span style="font-size:24px">クラウドネイティブ記事のECSコンテナ編の環境でマイクロサービスなアプリケーションを構築した想定</span>

<img src="images/MicroServiceArchitecture.png" width="40%"/>

<ul>
  <span style="font-size:24px">
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4379" target="_blank">(1)マイクロサービスアプリケーションのオーバービュー</a></li>
  </span>
</ul>

---

#### CI - 静的チェックツール環境の導入編 -

<img src="images/continuous-integration.jpg" width="60%"/>

<ul>
  <span style="font-size:24px">
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4463" target="_blank">(2)SonarQubeServerの構築</a></li>
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4466" target="_blank">(3)静的チェックルールの定義とIDEへの設定</a></li>
  </span>
</ul>

---

#### CI - SpringBootテストコード実装編 -

<img src="images/microservice-test-scope.png" width="60%"/>

<ul>
  <span style="font-size:24px">
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4475" target="_blank">(4)マイクロサービスにおけるテスト自動化とテスト戦略</a></li>
  </span>
</ul>

---

<ul>
  <span style="font-size:24px">
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4486" target="_blank">(5)マイクロサービスアプリケーションのパッケージ構成</a></li>
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4508" target="_blank">(6)マイクロサービスにおける単体テストコード実装</a></li>
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4519" target="_blank">(7)マイクロサービスにおける結合テストコード実装</a></li>
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4547" target="_blank">(8)マイクロサービスを呼び出す側の単体テストコード実装</a></li>
  <li><a href="https://news.mynavi.jp/itsearch/article/devsoft/4550" target="_blank">(9)マイクロサービスを含むEnd2Endテストコード実装</a></li>
  </span>
</ul>

---

#### CI - AWS CodeBuildによるCI実践編 -

<img src="images/continuous-integration.jpg" width="60%"/>

---

#### CI - AWS CodeBuildによるCI実践編 -

<span style="font-size:24px">ブランチ戦略</span>

<img src="images/branch_strategy.png" width="60%"/>

---

#### CI - AWS CodePipelineによるCD実践編 -

<img src="images/pipeline.png" width="45%"/>

---

#### CD - AWS CodePipelineによるパイプライン1 -

<img src="images/pipeline-1.png" width="60%"/>

---

#### CD - AWS CodePipelineによるパイプライン2 -

<img src="images/pipeline-2.png" width="60%"/>

---

#### CD - AWS CodePipelineによるパイプライン3 -

<img src="images/pipeline-3.png" width="60%"/>

---

#### CD - AWS CodePipelineによるパイプライン4 -

<img src="images/pipeline-4.png" width="60%"/>

---

#### CD - AWS CodePipelineによるパイプライン5 -

<img src="images/pipeline-5.png" width="60%"/>

---

#### CD - AWS CodePipelineによるパイプライン6 -

<img src="images/pipeline-6.png" width="60%"/>

---

#### CD - AWS CodePipelineによるパイプライン7 -

<img src="images/pipeline-7.png" width="60%"/>

---

#### CD - AWS CodePipelineによるパイプライン8 -

<img src="images/pipeline-8.png" width="60%"/>

---
***

### 記事の背景

- ここ最近で支援したAWSプロジェクトで実装、R&D検証した内容を汎用化
- 幾つかのテーマにAWSソリューションアーキテクトとも議論

---
### 各テーマのポイント

---

```java
public class HelloWorld {
  public static void main(String[] args) {
      System.out.println("Hello World!");
  }
}
```

---
