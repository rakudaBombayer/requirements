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
(例:町に動物病院がない、大きな病院がない、雪解けや草刈り一人暮らしだと大変、重たい買い物、田舎町にないチェーン店がたべたい(マック、ケンタッキー等)、ゴミ出し、スマホのアプリの使い方を知りたい等)
  
- 車がないと生活が不便になってしまうので、高齢の方でも免許を手放せない
  
- ご近所さんには頼みにくい(気を使う、人間関係や距離感が変わる)、近所に頼める人がいない、第三者のほうが頼みやすい。

- お金を払って手伝ってもらう方が気持ち的に楽(ライドシェアに関しては報酬を金銭にしないことで合法的になる = 白タク行為にならない)
  
- 地方で仕事が少ないので、お手伝いすることで、新たな収入源が生まれる。
  
- 地元にシルバーセンター(高齢者が協力してくれる制度)があるが、頼める内容が狭い。


## 3.なぜそれを解決したいのか？
- 能登半島特有の不便さ　(例:町に動物病院がない、大きな病院がない、雪解けや草刈り一人暮らしだと大変、重たい買い物を頼みたい、田舎町にないチェーン店がたべたい(マック、ケンタッキー等)、ゴミ出し、スマホのアプリの使い方を知りたい、電車が通っていない、バスの便数が少なすぎる、バス停まで遠すぎる、まともな公共施設が車がないといけない。仕事が少ない、雪で身動きが取れなくなる、草刈りが大変)


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








## 6.非機能要件
- 24時間アクセス可能
- 直感的なUI/UX
- 画像保存オブジェクトストレージ(S3)を使用

## 7.業務フロー
1. ユーザー登録・ログイン
2. 服の登録
3. タイムライン表示
4. スワイプ（good / bad）
5. マッチング通知 → DMで交渉
6. 服の削除・管理画面更新







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








システム構成図




