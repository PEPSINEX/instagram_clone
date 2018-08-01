Instagram_clone
========

## Description
[@now_cold](https://twitter.com/now_cold?lang=ja)が作成した画像投稿&コメントアプリです。
Dive into codでの課題です。今現在の力量で本家に似せる、課題の要件を満たす、見やすく使いやすいアプリを目指しました。

## Requirement
- Ruby 2.3.0
- Rails 5.1.6
- PostgreSQL 10.3
- Bootstrap 3.3.7

## Function
- ユーザーのCRUD処理
- 投稿写真のCRUD処理
- 投稿写真へのコメントのCRUD処理
- お気に入り機能
- 写真投稿時、メール送信機能

## Comming Soon
- HTTPリクエストを送らずにDBからデータを取得してUIをもっと快適にしたい。
- いいねボタン、ユーザー間のお気に入り機能
- 検索機能

## ER Diagram
- Comming soon

## Usage
このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。

```
$ git clone git@github.com:KazuhiroObama/instagram_clone.git
```

次に、以下のコマンドで必要になる Ruby Gems をインストールします。

```
$ bundle install
```

その後、データベースへのマイグレーションを実行します。

```
$ rails db:migrate
```

これで、Railsサーバーを立ち上げる準備が整っているはずです。

```
$ rails server
```

## Author
[KazuhiroObama](https://github.com/KazuhiroObama)

