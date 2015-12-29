# tutyo

## やれること
* ログイン認証
* 家計簿の作成
    * 機能
        * 一回買ったらそれを入力
        * カテゴリーを選べる
        * 締め日を選べる
        * 年単位の給料を入力できる
        * 消費予算額を設定できる
    * 見た目
        * 今月の一覧がある
            * クレカの一覧がある
        * 消費予算額に対しての消費金額の一覧がある
        * 何らかのグラフが出したい。

## データベース

### category

* name:string
* monthly:boolean
* estimate:integer

### user

name:string
password:string

### record

* payment:integer
* date:date
* category:string
* card:boolean
* memo:text

### annual_salary

* year:integer
* salary:integer

###


## メモ

* ruby 2.3.0
* rails 4.2.5
