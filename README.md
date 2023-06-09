# MyPlants
### サービスの概要
「多肉植物に興味はあるが、育て方やイベントの参加に不安を感じる」という悩みを持つ人に  
「多肉植物の記録を共有、また多肉植物のイベント参加管理」を提供する  
「多肉植物&イベントの記録・管理」サービスです。  

### ユーザーが抱える課題
課題1. 多肉植物に新しい発見や変化を感じた時の楽しさを共有できない。育て方に不安を感じる。  
課題2. 多肉植物用のイベントに参加しようと考えるが、公式サイトがないことが多く詳細が分かりづらい為、参加をためらってしまう。

### 課題に対する仮説
課題1. 
- 多肉を観察し、様子の変化に楽しさを感じる人と、交流が持てていないのではないか？
- 同じ植物を似たような条件で育てている人と、情報が共有できていないのではないか?
- 成長記録を簡単に残せるツールがないのではないか？

課題2.
- 多肉のイベントについて詳細が分かるサイトが無いため、参加を迷っているのではないか？
- どんな人が参加するかが分からず、参加するまでのハードルが上がってしまっているのではないか?

### 解決方法
課題1. 多肉の成長を記録を作成、共有して、育て方の参考にしてもらう。  
課題2. 運営またはユーザに実際のイベントに基づいた、イベントの予定をリストとして作成してもらい、参加予定の人数(男女別)、行った感想がコメントで分かるようにする。

### メインターゲット
- 自宅に多肉植物に植物がある20~30代。
- 多肉に興味があるが、どう管理すればいいかわからない人。
- 多肉のイベントへ参加を考えているが、どんな植物が売られどんな価格帯で売られているか分からず参加をためらってしまっている人。

### 実現したいこと
- 一般ユーザー
    - 未登録ユーザー
        - ユーザー登録機能
        - トップ画面表示
        - 投稿(観察記録)の表示機能、検索機能
        - イベントの表示、検索機能
    - 登録ユーザー
        - ログイン、ログアウト機能
        - パスワードの再設定機能
        - フォロー機能
        - 投稿機能
            - 観察記録の投稿
                - タイトル、本文、カテゴリー、画像を記録として投稿できる
                - 投稿した記事に関連付けて、別の記事を作成できる
                - 投稿は、本文無しのタイトルだけでも投稿できる
                - 投稿へのお気に入り機能 
                - 投稿へのコメント機能
                - 投稿へのいいね機能
                - 検索機能
                - 投稿数に応じてマイページに表示されるヒートマップが変化する
                - 他の SNS　に OGP シェアできる機能
        - イベント管理機機能
            - タイトル、日付、場所、参考URlをイベントとして投稿できる
            - イベントへ参加するユーザーの一覧表示 
            - 女性でも参加しやすいように、参加するユーザーの性別が判断できる
            - 投稿へのお気に入り機能 
            - 投稿へのコメント機能
            - 投稿へのいいね機能
            - 検索機能
            - 投稿数に応じてマイページに表示されるヒートマップが変化する
            - 他の SNS　に OGP シェアできる機能
        - マイページ機能
            - プロフィール(アバター画像、名前、メールアドレス、好きな植物)
            - 検索機能
            - フォロー、フォロワー機能
            - DM機能


### なぜこのサービスを作りたいのか?
一人でも管理しやすい、多肉植物の魅力をさらに広めたい。
また、植物を通じた交流が増えて、さらに多肉のイベントが活発に行われて欲しい。

### スケジュール
1. 企画（アイデア企画・技術調査）：6/11〆切
2. 設計（README作成・画面遷移図作成・ER図作成）：6/13 〆切
3. 機能実装：6/13 - 7/10
4. MVPリリース：7/10〆切
5. 本リリース：7/31

### 技術選定
- Rails 7.0.4
- Ruby 3.2.2
- MySQL
- React
- Docker
- AWS

