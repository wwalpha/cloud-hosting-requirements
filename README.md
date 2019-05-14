# cloud-hosting-requirements
クラウドソリューション設計するための非機能要件確認項目

## Types of Cloud Computing
* 既存クラウドシステム**有**
  * コスト重視：同じクラウドの選択するのは、運用の学習コストが削減できる
  * リスト重視：リスク分散のため、違うクラウドを選択したほうがよい
* 既存クラウドシステム**無**
  * 運用の学習コスト重視： AWS -> Azure -> GCP
  * 社内Microsoft製品が多い：　Azure -> AWS -> GCP
* 使用目的
  * Migration
  * Innovation: AI? Iot? BigData?

## Backup
* 世代数
* 期間

## Storage
* 

## Cost
* 

## 

## Scalability
* 必要か
* リリース後想定の同時アクセス数、ピークアクセス有無
* リリース後、３ヶ月、６ヶ月、１年、想定する同時アクセス数？ピークアクセス有無
* 例えば、キャンペーンやイベントよる大量アクセス発生

## Reliability
* Web Server
* AP Server
* Database

## Disaster Recovery
* 復旧時間
* 掛けるコスト
* 復旧範囲？(AZ, Region)

## SPOF(Single point of failure)
* 許容範囲

## CI/CD
* Agile?
* WaterFall

## Auto Operation
