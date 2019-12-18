# sample-dokusyokansou-app
サンプルの読書感想アプリを作る想定で設計してみる

## 何が出来るシステムか？
- ユーザは会員登録して利用する
- ユーザは本の読書感想を投稿できる
- ユーザは他の人の読書感想を見ることが出来る
- ユーザは他の人の読書感想にいいねできる

## ユースケース素案を洗い出す

<アクター>は<対象>を<アクション>する　という書き方で書いてみる.

- ユーザはアカウントを登録する
- ユーザはアカウントを更新する
- ユーザはアカウントを退会する
- ユーザは読書感想の一覧を取得
- ユーザは読書感想を投稿する
- ユーザは読書感想を更新する
- ユーザは読書感想を削除する
- ユーザは本を検索する
- ユーザは本から他の人の読書感想の一覧を見る
- ユーザは他の人の読書感想を閲覧できる
- ユーザは他の人の読書感想にいいねできる

## ユースケース図(use-case.pu)を作成

- [Plant UML](https://www.google.com/search?client=safari&rls=en&q=plantuml&ie=UTF-8&oe=UTF-8) で書く. 
  - 記法は学ぶ必要がある
  - 細かい図の配置で神経使わなくてもよしなに配置してくれてコンポーネントの追加削除が圧倒的に楽ちん.
- エディタはVS Code+プラグインなりで書きませう
- github上で見る場合は、ブラウザ拡張等で工夫して見ましょう

## [OAS2.0](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md) でAPI仕様を作成

T.B.C
- ゆとりなので [GUIのエディタ](https://openapi.tools/#gui-editors) で書く

## [OAS2.0](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md) を使ってモックサーバを立てる

T.B.C
- [mock](https://openapi.tools/#mock) からよさそうなの探しましょう


# 疑問
- MVPって度のタイミングで決めるん？ステークホルダーと開発内容を合意するとき?