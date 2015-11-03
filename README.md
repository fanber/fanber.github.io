# [fanber.github.io]()

## Настройка окружения

Зависимости:

1. Установить [node.js](https://nodejs.org/)
2. Установить Grunt `npm install grunt-cli -g`

Склонировать этот репозиторий. В его коневой папке выполнить следующие команды:

1. `npm install`
2. `bower install`
3. Скачать [bootstrap v4.0.0-alpha](https://github.com/twbs/bootstrap/archive/v4.0.0-alpha.zip) и распаковать в папку `fanber.github.io/bower_components/bootstrap-4.0.0-alpha/`. (4 версии еще нет в bower) 
4. В папке `fanber.github.io/node_modules/postcss-style-guide` выполнить `npm install`. C модулем что-то не то и надо доустановить зависимости

## Разработка

`grunt dev` — запустить локальный сервер [http://localhost:5555]()

В папке `src` исходники. В папке `out` результат.

[http://localhost:5555/docs/styleguide.html]() — автоматически генерируемый стайл-гайд.

## Публикация

`grunt ghpublish` зальёт страницы на [http://fanber.github.io/]() и [styleguide](http://fanber.github.io/docs/styleguide.html) тоже.
