# service_name

## サービス概要
日々、仕事や人間関係や育児などで心が疲れたりネガティブになった人が
匿名で心の毒を独り言のようにつぶやけて、匿名相談で同じような経験をした人から
解決のヒントをもらうこともできる心の疲れを溜め込まないサービスです。

## このサービスへの思い・作りたい理由
日々のストレス社会で心が疲れてしまって元気がない時に、
知らない誰かと一緒に自分の本音を匿名でひっそりつぶやけたら心が少し楽になれると思ったから。
誰にも相談できない悩み事を一人で抱え込まずに、知らない誰かに相談出来たら解決策が見つかったり客観的に考えられるようになりそうだから

## ユーザー層について
20〜４0代の男性、女性
日々少しずつ溜まるストレスを匿名でつぶやきたい人
周りの人に相談できない、解決したい悩み事がある人

## サービスの利用イメージ
・ユーザーがモヤッとしたりイラっとした時にアプリを開いたらすぐに愚痴れる
・誰にも相談できないことを匿名で相談できるし、匿名でアドバイスをすることができる
・相談ページ以外には共感ボタン・お疲れボタンしかないので気軽にボタンをクリックできるし
　押してもらうことができる

## ユーザーの獲得について
SNS（Xなど）に投稿して周知する。使用して使いやすいと思った人から口コミでSNSにあげて広まってほしいです

## サービスの差別化ポイント・推しポイント
・チャット機能を使って書き込みをする。決まった件数しか表示されないため
　つぶやきを書いてもすぐに消えてしまうので愚痴もかきやすい。
・共感ボタンやお疲れボタンなどがあるので、つぶやきを見た人が共感してくれるかもしれない
・匿名で相談・回答できるので、人に言えないことも解決策が見つかる可能性がある
・つぶやきに対してコメント機能がないので否定的なことを言われることがない

## 機能候補
　■ＭＶＰリリースにむけて
ユーザーはログインすることができる
ユーザーはログインなしでつぶやくことができる
ユーザーはログインしたら匿名相談ができる
ユーザーは共感・お疲れボタンを押すことができる
ユーザーは直近30件のつぶやきを見ることができる
ユーザーは過去の相談からキーワード検索ができる
ユーザーは自分が投稿したつぶやきを過去24時間のみ見返すことができる
ユーザーは書いたつぶやきが消えるのでその時の気持ちを忘れることができる

■ＭＶＰ後
・日々の生活の中でクスッと笑ってしまうような出来事をつぶやいてみんなで共有できる
・どんなことでみんながストレスをつぶやいているのかキーワードで管理者がわかるようにグラフ化する
・匿名相談に回答してくれた人にお礼メッセージを相談者が送れるようにする（非公開予定）

## 機能の実装方針予定
・ActionCableでつぶやきが流れるようなチャットをつくる
・Stimulus Autocompleteの仕様を候補に検索機能をつくる