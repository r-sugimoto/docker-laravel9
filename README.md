# Docker で Laravel9 環境構築

## バージョン

Laravel 9
PHP 8.1
node 12

## Docker 立ち上げ

docker-compose up -d

## サーバーに入る

docker-compose exec app bash

## Laravel 構築

composer create-project laravel/laravel [プロジェクト名]

## default.conf の「**\***」をプロジェクト名に合わせる

docker-compose stop
docker-compose up -d

## .env など修正

## Laravel

http://localhost:8000/

## phpMyAdmin

http://localhost:8080/

## DB 情報は「docker-compose.yml」を確認する

## Composer エラーの解決策

composer diag<br>
でエラーの内容を確認する

## 認証設定

composer require laravel/breeze --dev

php artisan breeze:install<br>
or<br>
php artisan breeze:install vue<br>
or<br>
php artisan breeze:install react<br>

## npm install

npm install

## npm run dev

npm run dev

# 補足

## Laravel で Form を使う

composer require laravelcollective/html
