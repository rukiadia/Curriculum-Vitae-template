# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|Sho Yamada|
|Age|32|
|Blog|[ゆとり日記](http://rukiadia.hatenablog.jp/)|
|Twitter|[@rukiadia](https://twitter.com/rukiadia)|
|Qiita|[@rukiadia](http://qiita.com/rukiadia)|
|Codepen|[rukiadia](http://codepen.io/rukiadia/)|
|Speakerdeck|[@rukiadia](https://speakerdeck.com/rukiadia)|

## スキル

### 言語

- HTML5
  - アクセシビリティを意識したマークアップ
- CSS
  - 基本的にSassを使用。
  - CSS設計の際は[FLOCSS](https://github.com/hiloki/flocss)を元にルールを加えた設計手法を取る。
- JavaScript
  - jQuery
  - ES2015
  - TypeScript
  - React + Redux + Express
- PHP
  - 5.3〜7.3
  - CakePHP
    - 〜2系
  - CodeIgniter
    - 2系〜3系
- Java (for Android)
  - 前職でAndroidアプリの開発をしていた時期があったので記載。
    - この業界に入ったきっかけの言語でもあります。
- Ruby(Ruby on Rails)
  - 前職で1年半ほど、プロダクト運用していました。
    - 当時のバージョンは4系→5.1

- 英語
  - 英文ドキュメントは問題なく読める。日本語と比較すると、少し多めに時間がかかる。
  - 海外カンファレンスに1人で行ける程度の英語力
    - [Devfest.asia 2016](https://2016.devfest.asia/)に参加

### その他

- エディタ
  - PHPStorm、PyCharm、IntelliJ
    - 現職でCodeIgniterとDjangoを使うため。
    - 個人ではIntelliJのみを使用中。
  - Visual Studio Code
    - C++を書く時はこちら。AtCoderの問題演習に使用。

- ツール
  - Git
  - SVN
  - Adobe PhotoShop
  - Adobe XD

- タスク(チケット)管理
  - Backlog
  - JIRA
  - Redmine

- タスクランナー
  - gulp
  - npm scripts

- テンプレートエンジン(ジェネレータ)
  - ejs

- スタイルガイド
  - KSS

## 強み

- 組織内への積極的な情報展開を継続している。
  - Slack内にある技術共有用のチャンネルで情報を随時展開。

- 継続的に改善を行う姿勢
  - 自分自身の仕事への取り組み方、コードのリファクタリング、社内の教育方針の改善や提案等
    - 細かい失敗を振り返り、地道に改善を重ねていくようにしています。

- 定期な振り返りを実施
  - プライベートでは個人の振り返りもやるようにしています。
    - 日曜日に翌週の計画を立て、週末に実際の行動を振り返るサイクルを回しています。
    - 「良かったこと」「もっとよくできること」「まだやれてないこと」
      - やれてないことが多くなると精神衛生上良くないので、無茶な計画は立てないように注意しています。

## 登壇歴

- 2014/06/08 [天下一altJS武闘会](https://connpass.com/event/6402/)
  - Dartについて
- 2014/12/15 [SCRIPTY#2](https://scripty.connpass.com/event/10345/)
  - meteorについて
- 2017/02/22 [HTML5とか勉強会](https://html5j.connpass.com/event/50524/)
  - パフォーマンス意識を組織内に根付かせる挑戦
- 2018/09/28 [Rejectcon 2018（builderscon tokyo 2018 番外編）
](https://techplay.jp/event/686258)
  - フロントエンドエンジニアが考えるべき事はたくさんある
- 2019/02/08 [第２回AtomicDesignについて考える会](https://thinkatomicdesign.connpass.com/event/115574/)
  - https://speakerdeck.com/rukiadia/atomic-designdeyi-shi-sitaikoto-inspired-by-flocss
- 2019/11/15 [フロントエンドカンファレンス福岡 2019 前夜祭&リジェクトコン](https://fec-fukuoka.connpass.com/event/154737/)
  - https://speakerdeck.com/rukiadia/chi-yan-du-miip-mitofalsezheng-siifu-kihe-ifang

## 執筆歴

- 2020/04 [WEB+DB PRESS vol.116](https://gihyo.jp/magazine/wdpress/archive/2020/vol116)
  - フロントエンドのトラブルシューティング特集

## 職務経歴

### 2018/12〜 : 株式会社オミカレ

職業：Webアプリケーションエンジニア

婚活パーティーのポータルサイトをやっている会社で、知人の誘いで入社しました。
フロントエンドがメインではありますが、サーバーサイドを書く時間が最近長いです。APIを自分で書くこともあります。

#### コーポレートサイトのリニューアル

プロダクトの画面フルリニューアルです。
https://party-calendar.net/

レガシーコードからの脱却と、Bootstrapに強く依存したデザインからの脱却の両軸を目指したプロジェクトで、期間としては2019年3月〜6月頃です。

##### 基本的な技術構成

フレームワークはCodeIgniter3とDjango2系の併用です。リニューアル前はCodeIgniter2を独自に拡張したものを使用していました。
DjangoはAPIとして動いており、Webとネイティブアプリの両方から参照されている状態です。

CodeIgniterは単なるMVCではなく、MVPパターンを用いて開発をしています。
Viewの責務がControllerに影響してファットコントローラーになることを防ぐのが目的でそうしています。RailsでいうところのDecoratorパターンがイメージとしては近いかもしれません。

CSSは[FLOCSS](https://github.com/hiloki/flocss)を基本としつつ、少しだけ手を加えた構成にしています。
JavaScriptは将来的に「React + TypeScript」の導入を検討していたので、TypeScriptを選定しています。

##### プロジェクトを振り返ってみて

###### 良かったこと

- 問題の少ないCSS構成が出来た。
- チームが纏まるきっかけになった。

###### 問題の少ないCSS構成が出来た
汎用性を持たせすぎず、捨てやすいCSSにしたことでメンテナンス性を高めることが出来ました。
粒度の大きい画面パーツをなるべく作らず、ページ固有のパーツとして運用するようにしたことで予期せぬ箇所のデザイン変更が起こりづらくしています。

ページの分類は以下のようにしています。

- TOPページ
- 検索ページ
  - ここのデザインを大きく変えたくなったとしても、他のページをあまり意識せずに済む
- 詳細ページ
- フォーム系のページ

###### チームが纏まるきっかけ
プロジェクトの終盤は非常に大変でした。スケジュールの見積もりミスによる小さな遅れが積み重なったことで、リリース予定日を結果的に1ヶ月遅らせることになりました。

ここで良かったのは、「何故遅れてしまったのか」「どうすれば同じ失敗を繰り返さずに済むか」といった改善策を考える土壌がチームに生まれたことです。
この土壌があることで「前回失敗をしたから、今回は別のアプローチに挑戦してみよう」といった改善のサイクルが生まれました。

個人単位だけでなくチーム単位でも定期的に振り返り会、向き直り（※カイゼン・ジャーニーを参照）をすることでチームを上手く機能させる試行錯誤を今も続けています。

### 2017/07 - 2018/11 : 株式会社リブセンス

職業：フロントエンドエンジニア

フロントエンドだけではなく、Webアプリケーションエンジニアになるための経験を積むためにこの会社を選びました。

#### サービスサイトのリニューアル

入社直後に行った仕事がこれでした。

リブセンスが創業当時から運営しているジョブセンスというサービスを、マッハバイトという別名サービスにリブランディングするために
画面全体の修正が必要になりました。

- ブランドカラーも変更になるため、ページ全体のトンマナを大きく変更。
- 短期間（約三ヶ月）でのリニューアルとなるため、バックエンド側には手を加えない。

という前提の元で修正コストをなるべく抑えつつも、デザイン上の変更点が大きい場合は後々の保守性を考え、ページを一から組み直す作業を全ページに渡って行いました。

周りのフォローが手厚かったこともあり、大きなトラブルもなく9月末にリリースまで完了。

#### prototype.jsとの戦い

創業当時から動いているサービスなので、最終更新日が2010年だったりするファイルがあちこちに存在します。JavaScriptも例外ではありませんでした。

2010年当時に流行していたprototype.jsで書かれた処理も多く存在していました。

- 周辺ライブラリの開発は勿論止まっている。
- 目を輝かせて入ってきた新人の心を折る。
- 7~8年前に流行っていたものなので、そもそもドキュメントが少なく、開発がやりやすいとは言えなかった。
- モダンにしていきたいという周りの声もあった。

上記のような経緯もあり、2017年の秋・冬はこれらを比較的新しいjQueryとES2015をベースにしたコードにひたすら書き換えていました。

#### 日々の開発タスク

現在担当しているサービスが元々PHPで開発されており、今現在もPHPで動いている部分が多くありますが、
日々Railsへの移植を進めています。その際はバックエンド側の処理からフロントエンド側の実装まで一通りやっています。

### 2014/08 - 2017/06 : 株式会社レイハウオリ

職務: フロントエンドエンジニア

#### LP作成

- 基本的にはページ数少なめの短期案件。2週間で10画面弱作成、くらいの規模が多い。
- レスポンシブ対応の有り無しは案件によってまちまち。PC/SPで別に作る場合も。
- JavaScriptで実装が必要な部分は多くない。
  - あっても、アコーディオン、スライドメニュー、カルーセル程度。

- キャンペーン用の特設ページだと、応募フォームの実装が必要な場合もある。
  - その場合はSubmitからバリデーションまで、PHPで実装する。
    - JavaScriptで二重にバリデーションをかける場合も時々。

#### コーポレートサイトのリニューアル

- 「自社HPをリニューアルしたい」という流れで来る場合が殆どの中規模案件。
- 実質、上記のLP案件の規模大きい版。20~30画面。
  - 初期の段階での設計や、テンプレートエンジンやCSSメタ言語によるコード整理が重要になってくる。
- 若手のメンバーが増えてからは、お客様とのやり取りや開発環境の整備、メンバーのフォローをする場面が多くなった。

##### よく使用していたタスクランナー構成
- browser-sync
  - ローカルサーバーとlive-reload。
- gulp-sass、gulp-cssnano、gulp-concat
  - Sassのコンパイル、ファイル纏め、最小化。
- autoprefixer
  - 地味に重要。付け忘れを防止することで、実機検証時の表示崩れ修正コストを大きく減らせる。
- run-sequence、gulp-plumber
  - 処理の順序付け等
- gulp-KSS
  - 稀にスタイルガイドが必要な場合があったので、その場合は使用。
- 自己流FTPタスク
  - 検証環境へのファイルアップロード忘れ防止。自動で上げるようにしていた。

無茶な冒険をせず、必要な物だけを入れた構成。属人性防止のため、案件毎にドキュメントを整備し、メンバーへの布教も随時実施。

#### 既存ページのパフォーマンス改善

- 表示速度と、ボトルネック処理の改善。CVRやPageSpeedの点数改善が目的。
- 競合他社と比較し、CVRやPageSpeedの点数が低い事がきっかけで相談が来る場合が多い。
- 点数の改善が分かりやすいため、画像の圧縮やlazyloadの実装から始めていく。
- 不要なファイルの読み込みや、処理実行を地道に洗い出して消していく。
- サーバー側に触れる場合は、キャッシュの期限設定やgzipの設定を入れたり。

#### ブッキングテーブル

2016年頃に業務委託で関わっていたプロジェクトです。

レストラン・飲食店をオンラインで予約をするWebサービス（食べログやRettyと同系統）で、価格層が少し高めの店舗の絞って掲載されるところが差別化のポイントです。
期間としてはリリース前から1年ほど関わっていました。

##### 基本的な技術構成

当時は少し珍しかったSingle Page Applicationです。Backend for Frontendの層はExpressで構成されており、画面はRedux・Reactで開発を行っていました。私を含めたフロントエンドのメンバーの担当領域はAPI・デザインを以外を全てやるという割り振りでした。

技術的にはチャレンジしがいのある要素が多く、非常にやりがいのあるプロジェクトでしたが、アサイン直後の3ヶ月が苦労の連続でした。

- React・Reduxが実務初経験。
- JavaScriptのテストコード（Mocha）を書くことも初めて。
- 外部から新規に参加したメンバーだったので、ドメイン知識がない。

こうした要因が重なったことで、参加当初はかなり苦労しました。ですが、先にプロジェクトに参加していたメンバーのにドメイン知識を質問しまくり、実際にコードを書き続けて反復練習をすることでなんとか切り抜けました。

##### チャレンジしたこと

- 画面パーツのコンポーネント指向開発
- リリース後のリファクタリング
- 企画にも積極的に参加

###### 画面パーツのコンポーネント指向開発

それまではPHPやJavaといったサーバーサイドでHTMLを丸ごとをレンダリングする手法しかやったことがありませんでしたが、Reactでは画面をコンポーネント指向で開発していくことになります。開発アプローチするにあたって、Atomic Designをチーム全員で学びました。

昨年は自分の考えをアウトプットするため、コンポーネント指向開発の話を勉強会のLTで行いました。
https://speakerdeck.com/rukiadia/atomic-designdeyi-shi-sitaikoto-inspired-by-flocss

###### リリース後のリファクタリング

リリース後も新規の機能開発は数多くありましたが、作ってきた画面のコンポーネントの粒度の大きさや汎用性を振り返りつつ、数人のメンバーとリファクタリングに積極的に取り組んでいました。既にテストコードがあったことで安全にリファクタリングを進められたことは、今の自分の開発手法にも活かせているように思えます。

##### プロジェクトを振り返ってみて

最終的にはサービスが大きくグロースせずにチームも解散になってしまいましたが、得られるものは多くありました。

- 事例が多くない技術スタックでプロダクトを作る挑戦
- 規模の大きいチームで働く

自分にとっては初体験なことばかりでしたが、この2つが特に大きかったです。

###### 事例が多くない技術スタックでプロダクトを作る挑戦

当時のReactやNode.jsといったモダンな技術を使いつつ、試行錯誤しながらプロダクトを作るのは最高に楽しかったです。「使ったことない技術スタックでも必死にやればなんとか形にできる」という自信にもなっています。

###### 規模の大きいチームで働く

このプロジェクトのチームはデザイナーやQAも含めると30人超の人数で構成されていて、所属もバラバラでした。プロダクトを運営する社員の方をはじめ、他社から業務委託で出向してきている方やフリーランス契約の方も在籍しており、それまで制作会社の受託案件が主だった私にとっては初めての体験でした。

私自身がマネージャーをやっていたわけではないですが、プロジェクトマネジメントのことを少しでも知っておこうと考え始めたきっかけになっています。

##### 反省したこと

巨大なPull Requestを作りがちだったことが大きな反省点です。

一人あたりのタスクの粒度が大きく、それを細かくタスク分解せずに通しでPull Requestを作ってしまっていました。
レビュアーに大きな負荷を与えるうえに、手戻りが発生した時のコストも大きかったりと様々なデメリットがありました。

チーム開発をトラブルなく進められるよう、今はタスクの粒度を小さくするための分解や進捗共有を強く意識するようになりました。

### 2011/04 - 2014/04 : 株式会社リーディング・エッジ社

職務: Androidエンジニア・PHPエンジニア

#### 研修

LAMP環境を使用する機会が多くあるため、その準備としての研修。

- CentOSでのLinuxサーバー構築
- サーバ仮想化のための仮想化技術の学習

#### 大手通信キャリアの業務システム構築

一言で言うと、Redmineのような物をゼロから構築。システムの役割はキャリアが出している全アプリのバグ管理。

- フロント側はjQuery、Bootstrap2系を使用。B側の画面（いわゆる管理画面）であったため、小綺麗なデザインは求められていなかった。
  - 初めて、CSSやJavaScriptに触れたタイミングであり、フロントエンド領域に興味を持ったきっかけ。
- サーバー側はCakePHP、DBはPostgreSQLを使用。
  - 先方の環境に入っている物を使わなければならなかったため、自動的にPHPとPostgreSQLに決定。
  - バグ起票フォームのバリデーション実装がきっかけで正規表現に触れる。
    - DBへのinsert、update自体はCakePHPのModel内で弾けるものの、勉強がてらにやらせてもらっていた。

- 隙間時間でアプリの自動テストの仕組みも作っていた。
  - 当時あった「MonkeyRunner」を使い、画面テストやキャプチャー取得を自動化。再現率の低いバグの検出を目的としていた。
  - MonkeyRunnerがJython実装であったため、スクリプト自体はPython2系で記述。
  - エラーがあった時のメール通知を当時のメンター役の先輩に作ってもらい、中身のjarファイルを読んだりしていた。