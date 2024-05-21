# MyPlants
MyPlantsは、多肉植物の育成記録を共有し、関連するイベントへの参加を管理するためのサービスです。<br/>
多肉植物とそれに関連するイベントに関する情報を整理・保存することができます。
### サービスURL
https://my-plants-front.vercel.app/

2024年5月現在は、料金の都合によりバックエンドのデプロイ先をAWS Fargate -> Heroku に変更しております。
<br/>

---

## 主な機能
#### 未登録ユーザーの機能
- 観察記録の表示
    - 画面右のウィジェットに投稿された記録に関連づけられた記録を表示し、成長過程を確認する機能
    - 観察記録のタグ情報を使用した検索機能とオートコンプリート機能
- イベントの表示
    - イベント一覧を閲覧し、Googleマップで場所を確認する機能
- ソーシャルログイン機能 (Firabase Authenticationを使ったGoogleログイン、Passwordログイン)
#### 登録ユーザーの機能
- 観察記録の管理
    - 投稿・いいね・ブックマーク・コメント
    - 既存の記録に関連づけた、新しい観察記録の投稿
- イベントの管理
    - 投稿
      - タイトル、日付、場所、参考URlの投稿
      - 場所は住所からオートコンプリートし、マップにマーカーの設置
      - 詳細な日付や時間が決定していない場合でも投稿できる
    - ブックマーク・コメント
    - 参加予約
    - 画面右上のウィジェットに参加予定のイベントの中で直近のイベントを表示
    - イベント詳細画面で、画面右のウィジェットに、イベントへ参加するユーザーの一覧表示
- マイページ機能
    - プロフィール(アバター画像、名前、ひとこと)
    - いいねした記録、参加予定のイベント、参加予定のイベントを表示

## 主な使用技術
#### フロントエンド
- Next.js
- TailwindCSS

#### バックエンド
- Ruby on Rails
- MySQL

#### インフラ
- Vercel
- AWS (ECS on Fargate, S3)

#### 環境構築
- Docker
- docker-compse

#### 外部サービス
- Firebase Authentication
- Maps JavaScript API (Place API + Geocoding API)

## インフラ構成図
![MyPlants_Infra_conf_20230928](https://github.com/Shocker55/MyPlants/assets/115390088/83a79b95-51eb-4f28-ba81-34fc991775f7)
<br/>
<br/>
## ER図
![MyPlants_ER_20231023](https://github.com/Shocker55/MyPlants/assets/115390088/5e8134b3-b89b-424e-8b51-de7dc8639755)
<br/>
<br/>
## 画面遷移図
[Figma](https://www.figma.com/file/94aBqkdlwTqNyVybV0E0Ih/MyPlants?type=design&node-id=0%3A1&mode=design&t=QgtIWSJNYG2CM9z8-1)
