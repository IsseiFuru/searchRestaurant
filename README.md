### アプリ名
searchRestaurant

## 作者
古谷 一晴

## 開発期間
4日間

## 開発環境
### 開発環境
Visual Studio Code

### 開発言語
PHP 8.1.6
JavaScript

## アプリケーション機能
### 機能一覧
- 位置情報取得：Geolocation APIを使用して、現在の緯度経度を取得する。
- レストラン検索：ホットペッパーグルメサーチ API を使用して、現在地周辺の飲食店を検索する。(距離範囲と予算を指定することが可能)
- レストラン一覧表示：検索結果を10個ずつ表示される。(距離順、名前順、おすすめ順に並び替え可能)
- レストラン情報取得：ホットペッパーグルメサーチ API を使用して、飲食店の詳細情報を取得する。

### 画面一覧
- 検索画面(index.php) ：条件を指定してレストランを検索する。
- 検索結果画面(list.php) ：検索結果の飲食店を一覧表示する。
- 店舗詳細画面(detailRestaurant.php) ：店舗一覧から店舗の詳細を表示する。

### 実装すべき機能
- 検索画面(index.php) ：カフェやファミレスといった店の種類を指定して検索をするように細かい検索条件を増やす。また、食べ物の名前を検索してその食べ物の
- 店舗詳細画面(detailRestaurant.php) ：その店の周辺の地図を表示させる。

### 使用している API,SDK,ライブラリなど
- Geolocation API
- ホットペッパーグルメサーチ API
- composer 2.3.9

### こだわったポイント

- 検索結果一覧を表示させる時に、距離順、名前順、おすすめ順に並び替え可能が出来る
- 検索結果画面にスムーススクロールを実装し、操作性を向上させた。

### アドバイスして欲しいポイント
- 他の言語間でのデータの受け渡し方法
- 全体的にサイトを使いやすく、見やすくしたい。
- 検索結果画面で再検索を行った時、緯度と経度が参照されずエラーが起こります。

### 自己評価
取り組む時間と自身の技術が足りなくて、全体的に詰めが甘くて個人的に満足の行くところまでいけなかったのが心残りです。
最低条件は満たした事だけ良かったと思います。
