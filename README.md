# README

# React_CRUD

## アプリケーション概要
SPA(Single Page Application)となっており、１ページにてコメントのコメントの登録・編集・削除ができるアプリです。

<img width="1429" alt="reacr-crud samme" src="https://user-images.githubusercontent.com/57065520/90216802-89d30980-de3a-11ea-992c-bddc367bc20b.png">

## 【GIF動画】
https://i.gyazo.com/1cb2ee513f9b450d6d1f42d0e0f24b5f.gif


## 制作背景(意図)
オリジナルアプリ制作前にRailsとReactを組み合わせたアプリの制作を経験したいと考え、とあるサイトの解説を確認しつつ制作しました。
今回は「gem react-rails」を使用して実装しています。
react-railsのgemはアセットパイプラインを利用してJSXをRailsが認証できる形に処理します。（一般的なRailsをapiとして作成する方法ではありません。）

## 機能一覧
- 新規投稿機能
- 投稿編集機能
- 投稿削除機能
- 初期化機能(seedデータの情報以外を全てリセットする機能)
- メッセージ表示機能(Ajax通信時にメッセージを表示)

## デプロイ先
サンプルのため、デプロイはしておりません。
参考にさせていただいたサイトにデモがあるため、以下のURLから確認してください。

【参考サイト】
https://www.petitmonte.com/ruby/react_crud.html

【デモ】
https://www.petitmonte.com/rails-demo/react_crud

## 使用技術
### ◼️ 言語
#### バックエンド
- Ruby 2.5.1
#### フロントエンド
- Javascript

### ◼️ フレームワーク
- Ruby on Rails 6.0.3

### ◼️JSライブラリ
- React 16.13.1

### ◼️データベース
- MySQL 5.6.43

### ◼️その他
- webpacker 4.2.2
- bootstrap
- fetch API内でRailsのCSRFトークンに対応