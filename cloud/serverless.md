# Serverlessについてまとめ

## Serverless(サーバレス)とは

アプリに必要なリソース（メモリ、ディスク）の割り当てを動的に管理し、
事前に購入されたリソースに基づく請求ではなく、アプリケーション要件を満たすためんに使用される個々のリソース量に基づいた請求を行うようなクラウド・コンピューティングのモデル。
物理的なサーバをユーザ（アプリ開発者）の視点から完全に隠蔽されているため、サーバ”レス”と呼ぶ。

## 歴史

* サーバレスという言葉がで始めたのは、AWS Lambdaが登場してから。(2014/11)
* "AWS Lambda" = "FaaS(Fanction as a Service)" がサーバレスを指すことが多かった
  * Dinamic Computingとも、Serverless Architecture/Computingとも呼ばれていた
  * 現在はDinamic Computingはほとんど使われない
* 現在はFaaSだけでなく、BaaSやPaaSも含むニュアンスで使われることが多い
* さらに、Computingのみならず、DBやデータフローにもサーバレスという言葉を使用することもある。
* 現在は、サーバの存在を感じさせないアーキテクチャの総称を指してサーバレスと呼ぶことが多い

## サービスの例

### FaaS(Function as a Service)

* Google Cloud Function
* AWS Lambda
