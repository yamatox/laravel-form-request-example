# 以下記事のサンプルです
https://qiita.com/yamatox/items/94e123849d924329a167

# インストール
```
$ docker-compose up -d
$ docker-compose exec php composer install
$ docker-compose exec php cp -p .env.example .env
$ docker-compose exec php php artisan key:generate 
$ docker-compose run node npm install
$ docker-compose run node npm run dev
```

# Formを使ったPOSTのパターン
http://localhost/add

# Ajaxを使ったPOSTのパターン
http://localhost/add2
