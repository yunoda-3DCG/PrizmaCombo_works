# オープン職務経歴書
公開できる範囲での経歴をまとめてあります。

## 基本情報

|key|value|
|----|----|
|Name|Yu Noda|
|Birth(Age)|25|
|Family|独身|
|Location|兵庫県神戸市|
|Education|慶應義塾大学　商学部|
|Mail| private(please contact through twitter) |
|Twitter|[@@yarikomivr_com](https://twitter.com/yarikomivr_com)|

## 転職活用ステータス

個人スタジオを始めて3年目に入ろうとしています。プログラミングやCGを未経験からスタートし、ようやく戦えるぐらいの武器になりました。
**個人スタジオゆえにチームでの開発経験に乏しく、チームでの開発を経験したくゲーム業界やIT業界での転職意向を持っています。**

## アウトプット

### Qiita

https://qiita.com/yarikomivr_com

備忘録を兼ねた投稿を少し。コーディングに関することよりも、Unity関連のtipsを投稿しています。投稿内容を抜粋すると、
  - 異方性反射マップを使ったライティング処理およびテクスチャ作成法
  - シェーダーを書かずにハイライトを描画する方法
  - 自作物理エンジン（GJKアルゴリズム）

## 趣味

- 3DCG
  - Blenderで毎日何かを作ってます。作品はだいたいtwitterに投稿し、ある程度数がそろうとUnityAssetStoreに卸しています。

## 労働環境に関する主な希望

- 技術力向上がしやすい環境
  - 技術力向上に対する意欲の高い人が多い
  - 幅広い分野の技術で相談できる人がいる
  - アーティスティックな表現にこだわりを持つ人が多い
  - 書籍購入費、勉強会参加費、資格試験費などがある程度補助される
- モダンな開発
  - ドキュメントの整備
  - モダンな技術/ツールの活用
  - 既存のワークフローに凝り固まらない気風
- 自分のペースで働ける
  - フレックス制度 (朝の満員電車避けられる通勤を所望)
  - リモートワーク
- 自分の慣れた開発環境
  - Windows（リンゴアレルギー持ち）
  - エディタは問いません、合わせます。
  - モニタ二枚（モデリング用に大きい画面がほしい）
- 評価基準が透明
  - 目標と役割が明確
  - 未経験分野に対する無茶な要求をしない
- 残業、、、無いに越したことはない。
  - 強制的なイベント参加がない
  - 仕事とプライベートの切り替えが曖昧でない
  - 休日は法令遵守、有給はチームに負荷をかけない程度に取れる

## 自然言語

|言語|レベル|
|-----|-----|
|日本語|ネイティブ|
|英語|TOEIC 800点(2016夏)|
|スペイン語|日常会話(1年間バルセロナに留学経験あり)|

## プログラミング言語/ソフトウェア
- C#およびUnity
  - 経験二年。すべて独学で習得
  - VRゲームにおけるユーザビリティの実装開発
  - jsonを使ったセーブデータ管理
  - データ指向プログラミングを使った群データ処理
  - jobやburstコンパイラを組み込んだ処理速度の改善
  - computeshaderによる並列処理
  - UIデザインの設計
  - 多言語仕様の会話データの管理
  - パーティクルシステムによるゲーム演出
  - 2D3D両方の開発経験あり
- HLSL
  - Unityのstandardシェーダーを改造し、ハイライト追加する機能を実装
  - コーディングで攻めるよりも、ノードベースのエディターでシェーダーを組むことが多いです
- python
  - Blenderが長年放置するバグを回避するプラグインを開発
  - 日常的に使用するわけでないので、知識はありますが武器になりません
- html
  - githubpageにてスタジオのホームページを管理しています 
- Blender
  - キャラクターやprops等の3DCGモデルを作成
  - ゲーム環境での動作を目指したリギング設定
  - unityで利用しやすい形でのアニメーション作成
- Photoshop
  - CGモデルのテクスチャ調整に使用
  - 作品のイメージや宣伝画像を作成
  - CG用のシームレスマップやペイントブラシを作成
- StadioOne
  - ゲーム音楽を作曲
  - 作曲知識は一通り網羅
- WPF
  - MIDIファイルを解析するアプリを開発

## 実務経歴(新しい順)

### 個人スタジオPrizmaCombo(2018/01 ~ 現在)

#### 概要

- ゲーム開発を志すも、すでに新卒採用枠はなく、またプログラミングやCGが未経験だったため個人で立ち上げる
- 設立当初はVRを使ったアダルトゲームを企画

#### プロジェクト

- UIリニューアルにおけるAPI実装
  - 既に稼働中のWebサービスにおける、フルリニューアルプロジェクト
  - 約1年間プロジェクトに従事
  - Railsによる新規APIの実装
  - rspecによる単体テスト、リクエストテストの作成
  - apiblueprint/aglioによるAPIドキュメントの作成
- ワークフローの機能強化
  - ユーザのワークフローに関わる大型機能開発の指揮
  - 初めてのスクラム開発の採用(スクラムマスターではない)
  - UIリニューアルはサーバサイド(Rails)だけだったが、ここからフロントエンド(Vue)も書くように
- 検索機能強化
  - 既存の検索機能を強化して、より詳細に目的のリソースにたどり着けるようにする仕組みの開発
  - Elasticsearchによる検索の改善
    - インデックスの再定義の検討
    - ダウンタイムなしでのインデックスの張替え
    - 効率の良いクエリの検証、実装
  - レスポンシブなVueコンポーネントの実装
  - Vueコンポーネントの単体テストの導入(vue-test-util)
- 集計機能強化
  - Amazon Redshift上にあるログを元に集計をユーザに提供する機能の開発
  - AWS Redshift/S3/Auroraを活用したサマリーの生成周りの設計、実装(補助)
  - terraformによるAWSリソースのコード化
- 開発部の生産性向上のための仕組みづくり
  - CircleciによるCIの継続的改善活動
  - storybook駆動開発の促進
  - モジュールバージョンアップの自動化