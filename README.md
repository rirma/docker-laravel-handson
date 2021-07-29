# docker-laravel-handson
laravel勉強
参考url
```
https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4
https://www.hypertextcandy.com/laravel-tutorial-create-folder/
```

sql起動コマンド
```
docker-compose exec db bash -c 'mysql -u${MYSQL_USER} -p${MYSQL_PASSWORD} ${MYSQL_DATABASE}'
```

試し実行コマンド
```
php artisan tinker
```

コントローラー作成
```
php artisan make:controller FolderController
```

モデル作成
```
php artisan make:model Folder
```

バリデーションを行うのはFormRequestクラス
```
php artisan make:request CreateFolder
```

テストコード生成
```
php artisan make:test TaskTest
```

.envは頑張ってネットで拾ってね