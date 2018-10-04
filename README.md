
## 概要
楽天のカテゴリページの商品一覧をスクレイピングして、カラーミー商品一括登録用のCSVファイルを出力します。
## 使い方
2個の引数が必要です。""で囲むと良いと思います。

    Command 大カテゴリ名 楽天カテゴリページのURL



## メモ
- 標準出力に出力
- カラー・サイズなどのオプションは取得していません
- goquery使用
- 在庫管理しないに設定
- 掲載フラグ 掲載するに設定
- fmt.Printでシンプルに出力

2018/10/04 の時点で実際に使用してカラーミーに商品一括登録出来たのを確認しています。
