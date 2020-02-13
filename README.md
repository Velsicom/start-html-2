# Сборка для верстки start-html-2
Простая сборка для верстки на базе Gulp и webpack.

## Как использовать

`cd start-html-2` - Перейти директорию проекта

`npm i` - Установить все заисимости

`gulp` - Запуск сервера http://localhost:3000/

`gulp build` - Запуск сборки в продакшн

`ncu` - Проверка обновлений зависимостей в файле `package.json`

`ncu -u` - Обновить версии в списоке зависимостей

### Дополнительная информация

Сборка включает в себя минификацию css, `autoprefixer`, сжатие избражений `imagemin`, шаблонизатор `nunjucks`, модульность в `js`, `core-js` для выборочного подключения `polyfill`.

Поддерживается синтаксис `sass` и `scss`, `import` в JS.

### Сторонние библиотеки

`fancybox`

`animate.css`

`bootstrap-4-grid`

`normalize.css`

`owl.carousel`

`waypoints`

`wow.js`
