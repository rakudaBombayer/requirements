## 1.プロダクト名
**お願いquest** 

## 2.一言サービスコンセプト
田舎町特有の不便さ、身近な困りごとを誰かに助けてもらえるよう呼びかけができるアプリ

## 3.誰のどんな課題を解決するのか？
**誰:**
- 地方の住民、過疎地域の住民(高齢者でもつかえる？)
- ボランティアしたい人(報酬をほしい人も含む)
- 他の地域から来てボランティアをすることでその地域に溶け込みたい人

**どんな課題:**
- 田舎町特有の不便さ(例:町に動物病院がない、大きな病院がない、雪解けや草刈り一人暮らしだと大変、重たい買い物、田舎町にないチェーン店がたべたい(マック、ケンタッキー等)、ゴミ出し、スマホのアプリの使い方を知りたい)
  
- 車がないと生活が不便になってしまうので、高齢の方でも免許を手放せない
  
- ご近所さんには頼みにくい(気を使う、人間関係や距離感が変わる)、近所に頼める人がいない、第三者のほうが頼みやすい。
  
- 困りごとが見えないため、ボランティアや協力がしにくい。
  
- 地元にシルバーセンター(高齢者が協力してくれる制度)があるが、頼める内容が狭い。

## 4.なぜそれを解決したいのか？
- 身近な人で生活に田舎町の不便さに困ってる人を見てきたので、それを課題を解決してあげたい。
- (例:町に動物病院がない、大きな病院がない、雪解けや草刈り一人暮らしだと大変、重たい買い物(amazonつかえない)、田舎町にないチェーン店がたべたい(マック、ケンタッキー等)、ゴミ出し、スマホのアプリの使い方を知りたい)

## 5.どうやって解決するのか？
1. **お願い事をする側()**
    - スマホが扱えない人のために、LINEで身近な困りごとをアプリに投稿できるようにする。
    - 

2. **お願い事を受ける側:**
    - アプリにあるお願い事を協力することで報酬をもらえる。
    - 


## 6.機能要件
- 服の登録と管理
- 写真アップロード機能
- カテゴリ（例: トップス、ボトムス）、色の入力フォーム
- 登録した服の一覧表示
- タイムライン機能
- 他ユーザーが登録した不要な服の一覧を表示
- 「Good」ボタンをクリックしてリクエストを送る
- DM機能
- 相手ユーザーと1対1で簡単なメッセージ交換

## 7.非機能要件
- 24時間アクセス可能
- 直感的なUI/UX
- 画像保存オブジェクトストレージ(S3)を使用

## 8.業務フロー
1. ユーザー登録・ログイン
2. 服の登録
3. タイムライン表示
4. スワイプ（good / bad）
5. マッチング通知 → DMで交渉
6. 服の削除・管理画面更新


システム構成図

自家用有償旅客運送について
[04.pdf](https://github.com/user-attachments/files/18315536/04.pdf)


