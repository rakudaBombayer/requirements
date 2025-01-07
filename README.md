# 用件定義


## 1.プロダクト名  スケダチ

**一言サービスコンセプト**
能登半島特有の、身近な困りごとを誰かに助けてもらえるよう呼びかけができるアプリ


## 2.誰のどんな課題を解決するのか？
**誰:**
- 能登半島の住民(LINEが使いこなせるスマホ操作レベル感の人でも使える？)

- 能登半島の不便さの解消の助け、経済の回復の助け

- 手伝うことで報酬ををいただきたい人

- 仕事の少ない地域なので、新しい仕事が生まれる


**どんな課題:**
- 能登半島特有のの不便さ
例:町に動物病院がない、大きな病院がない、雪解けや草刈り一人暮らしだと大変、重たい買い物、田舎町にないチェーン店がたべたい(マック、ケンタッキー等)、ゴミ出し、スマホのアプリの使い方を知りたい等
  
- 車がないと生活が不便になってしまうので、高齢の方でも免許を手放せない
  
- ご近所さんには頼みにくい(気を使う、人間関係や距離感が変わる)、近所に頼める人がいない、第三者のほうが頼みやすい。

- お金を払って手伝ってもらう方が気持ち的に楽(ライドシェアに関しては報酬を金銭にしないことで合法的になる = 白タク行為にならない)
  
- 地方で仕事が少ないので、お手伝いすることで、新たな収入源が生まれる。
  
- 地元にシルバーセンター(高齢者が協力してくれる制度)があるが、頼める内容が狭い。


## 3.なぜそれを解決したいのか？
- 能登半島特有の不便さ　(例:町に動物病院がない、大きな病院がない、雪解けや草刈り一人暮らしだと大変、重たい買い物を頼みたい、田舎町にないチェーン店がたべたい(マック、ケンタッキー等)、ゴミ出し、スマホのアプリの使い方を知りたい、電車が通っていない、バスの便数が少なすぎる、バス停まで遠すぎる、まともな公共施設が車がないといけない。仕事が少ない、雪で身動きが取れなくなる、草刈りが大変)
を解消したい。

- 能登半島地震後、住民の3割は能登地区から避難中で自治体がこれ以上人がいなくならない(避難中の人が戻ってきてもらえる)によう施策を考えている。ところでその助けをしたい。
- 被災地の復興の助けをしたい。
- 私の出身地を住みやすい町にしたい。

## 4.どうやって解決するのか？
1. **お願い事をする側()**
    - 1.アプリにお願い事とその報酬を投稿(LINEで投稿できるようにする。?)
    - 2.応募者が多数の場合は選定
    - 3.チャットでやりとり
    - 4.お助けしてもらう。
    - 5.お助けごとをしてもらった後は報酬を支払う。

2. **お願い事を受ける側:**
    - 1.アプリに投稿された助けてほしいことに応募する。
    - 2.投稿者に選定される。
    - 3.チャットでやり取りする。
    - 4.お手伝いする。
    - 5.報酬をもらう。
 


## 5.機能要件

-　画面サイズはスマホサイズ。 
- 投稿機能(お願い事を報酬付きで投稿できる。)
- 

- お願い事を受ける側は身分証の登録が必要。
- チャット機能
- 相手ユーザーと1対1で簡単なメッセージ交換
- 可能ならお願い事をする側はLINEだけで完結させることができる。


### ユーザー機能
    - 新規登録・ログイン・ログアウト
       facebookなどの本名でのSNSでログイン可
    - マイページ
        自身の投稿一覧、通知の確認
        ユーザー情報編集(ユーザー名、プロフ画像変更等は勿論、得意言語などのステータス設定をできるよう実装)
    - 通知機能
        Discord連携OK:Discord内通知,サイト内通知 NG:サイト内通知のみ
        いいね、コメント、新規レビューが付いたときの通知(いいね以外は通知詳細で該当URLへ遷移)
    - 投稿機能
    - 

### 教材共有機能
#### 閲覧画面
    - アプレンティス推奨教材、公式ドキュメントの表示
        [推奨教材][公式ドキュメント]タグを付与して絞り込み、逆に除外出来るようにあらかじめ設定      
    -  サムネイル表示機能
        amazonなら商品画像、他媒体もサムネイルに該当するものを表示
    - 教材のソート機能
        既存の絞り込み＋ソート機能を追加(時間順、評価順)
        フリーワード検索を追加
    - いいね機能

#### 投稿画面
    - 

### プロダクト共有機能
    - 一覧画面
        絞り込み＋ソート機能
        フリーワード検索
        各プロダクトの投稿意図(テスター募集なのかレビューが欲しいのか)を表示
    - プロダクト名
        簡易的な紹介
        サイト内スクリーンショット
        投稿意図(テスター募集orレビュー募集,etc)
        サイトのURL
        githubURL(任意)
        利用技術(複数選択可能)
        公開設定(公開or匿名投稿)
    - コメント・レビュー
        テキストボックス
        公開設定(公開or匿名投稿) 











## 6.非機能要件
- 
- 
- 

## 7.業務フロー








** url一覧
類似アプリ↓
https://www.any-times.com/

** 自家用旅客有償運送について

自家用有償旅客運送
https://kotsutorisetsu.com/20200815-01/

自家用有償旅客運送に関する法律
[04.pdf](https://github.com/user-attachments/files/18315536/04.pdf)

自家用有償旅客運送の申請
https://www.pref.nagano.lg.jp/kotsu/kurashi/kotsu/bus/jikayouyusho/20150401.html

### 自家用有償旅客運送とは
地域住民の生活の維持に不可欠な過疎地や福祉の輸送がバス・タクシー事業では十分提供されない場合に、自治体や住民、事業者など地域の関係者が合意すれば、国土交通大臣等の登録を受けた上で、市町村やNPO等が自家用車を使用して有償で運送できる制度です。

** ライドシェアに関しては報酬を畑の野菜など金銭に変えにくいものにすることで白タク行為に当たらなくなる。(自治体の承認や国土交通大臣等の登録なくても問題ない。)
*** また自治体の承認のもと、国土交通省の登録をドライバーが受けることができれば有償での送迎が可能。









システム構成図




