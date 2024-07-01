- Cookie SameSite
  - ドメインをまたぐクッキー情報のリクエスト例
    1. ドメイン A からドメイン B にページ遷移するとき
    1. ドメイン A 内で iflame を使ってドメイン B を表示
    1. ドメイン A からドメイン B にリクエストする非同期通信
  - SameSite の設定項目
    - Strict
      - 1~3 のすべての条件下でクッキー情報のリクエストを許可しない
    - Lax
      - 1 のときのみクッキー情報のリクエストを許可する
    - None
      - 1~3 すべての条件下でクッキー情報のリクエストを許可する
  - SameSite の設定をしていない場合は Lax がデフォルト値となる
- 参考: https://www.youtube.com/watch?v=FHh9cAfiRJ