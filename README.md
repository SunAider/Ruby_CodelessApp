# 【アプリ概要】

作品名：CODELESS

・旅行宿泊業界の事業者が、オリジナル予約（EC）サイトを感覚的かつ手早く、コードを用いずに作成できるアプリケーション。

・本業界において根幹を担う、顧客管理や検索が行えます。

#### 【URL】
https://www.codelessjp.com/

・画面左上の「無料デモ使う」では、予約と予約管理機能が使用できます。

・画面左上の「デモを編集する」ではECサイトの編集が行います。

・画面右上の新規登録より新規ECサイトの作成が行なえます。

※詳しくは下記の操作方法をご参照ください。

#### 【操作方法】
https://www.codelessjp.com/demos/about


#### 【GitHub】
https://github.com/SunAider


# 【作成の背景】

予約と売上管理の自動化や、予約サイトの作成、編集を手軽にコードを用いず行えることで、業務効率化の実現に貢献します。
私が過去、スタートアップに携わったセブの旅行会社にて、自社のLPを使用して集客しておりましたが、アナログな手法を用いていたため、大変苦労致しました。当時のシステムは、予約時の顧客情報がメールで届き、それをエクセルに移して管理したり、ページの編集を行う際には、高度な専門的な知識が必要でした。結果、技術の習得が必要となり、その技術習得に多くの時間を要しました。
上記の課題は、業界問わず多くの現場で生じるものであるとも考えております。そこで、同じ課題を持つ方に幅広く活用していただきたく、本アプリケーションの開発に至りました。


・手動の予約・（顧客）管理の自動化

・ページを修正するのにプログラミングの知識が必要

以上2点の課題を解決する為に本アプリを作成しました。



# 【機能紹介】

### アカウント

・ユーザー管理

・クライアント管理

・デモ

### ECサイト作成/編集

・動画・画像投稿/編集/削除

・商品紹介の投稿/編集/削除

・クライアントのアカウント毎にECサイトを作成できる

・エディターを表示機能（非同期）

### ECサイト

・値段を自動計算機能（非同期）

・クレジット決済機能

・予約日保存機能

・人数保存機能

### 顧客情報管理

・予約者の情報をカレンダーに表示

・予約の編集/消去

・プラン別検索機能

### その他

・デモ機能（新規登録をせず上記の機能を試行）


# 【使用技術】

### フロントエンド

・HTML CSS(SCSS) / Bootstrap JavaScript / Vue.js

### バックエンド

・Ruby / Ruby on Rails /Rspec

### インフラ

・AWS / EC2,S3,Route53,ALB,SSL,ACM,Nginx

・Capistrano

・MYSQL

### API

・PAY.JP

# 【インフラ構成図】

<img src="https://user-images.githubusercontent.com/69699126/105904445-7c19e500-6064-11eb-80b5-5fb6c635b17f.png" width="750px">

# 【ER図】

<img src="https://user-images.githubusercontent.com/69699126/105826410-0da53a80-6004-11eb-9b2c-5c779acb3f29.png" width="750px">



# 【追加予定の機能】

### レスポンシブ対応

### 売上管理機能

・売上自動計算

・参加人数自動集計

・参加組数自動集計

・データをCSVにする機能

### 検索機能

・名前別検索日

・「年」「月」「日」別検索

・予約日別検索

### インフラ

・Docker
