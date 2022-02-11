# php8.0 Docker 環境

起動
docker-compose up -d

停止
docker-compose stop

コンテナ終了
docker-compose down

コンテナ終了 + DB 削除
docker-compose down --volumes

Docker image 削除
docker rmi < イメージ名 || イメージ ID >
