# template strapi basic

[template-strapi-basic](https://github.com/Rick-torrellas/template-strapi-basic)

A quick description of your strapi application

## usage

* npm i
* config project
* npm run dev

## config

./config/database.js

* client: 'mysql',
* host: env('DATABASE_HOST', 'localhost'),
* port: env.int('DATABASE_PORT', 3306),
* database: env('DATABASE_NAME', 'test'),
* username: env('DATABASE_USERNAME', 'root'),
* password: env('DATABASE_PASSWORD', 'test123'),
* ssl: env.bool('DATABASE_SSL', false),
