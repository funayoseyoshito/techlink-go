# Go言語初心者向けハンズオン #1

## decker-compose

* 起動
  ```
  docker-compose up -d
  ```

* 起動中のコンテナに入る
  ```
  docker-compose exec app bash
  ```

* 停止
  ```
  docker-compose stop
  ```

* 停止(データも消える)
  ```
  docker-compose down
  ```

## source sample

* flagパッケージを使ってcliツールを作ってみる(導入編)
https://gist.github.com/funayoseyoshito/f5a206a9dd1b6d32d372b157d6e68d0d

* flagパッケージを使ってcliツールを作ってみる(csvファイルを読み込んで、DBへ保存する)
https://gist.github.com/funayoseyoshito/915e9336a0e40b79d334d4fbddc8c12f

* flagパッケージを使ってcliツールを作ってみる(csvファイルを読み込んで、並列処理でDBへ保存する)
https://gist.github.com/funayoseyoshito/01d0bf2dcbceaaa340c3900f560d2eae
