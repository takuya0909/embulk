# embulk
embulkの使い方  
クローン後下記を順番に実行  
`docker-compose build`  
`docker-compose up -d`  
`docker exec -it embulk`  
データの抽出、変換、ロード (ETL) プロセスの結果をプレビューするたコマンド　  
`embulk preview config.yml`  
データの抽出、変換、ロード (ETL) プロセスを実行するコマンド　  
`embulk run config.yml`  
