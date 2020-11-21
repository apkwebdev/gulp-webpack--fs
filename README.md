README.md

## gulp-webpack--fs

## Сборщик проектов на базе gulp4 и webpack-stream
Для сборки html используется препроцессор pug.
Для сборки css используется препроцессор sass в синтаксисе scss.
Для сборки js используется webpack-stream.

## Особенности
Есть специальные функции и миксины создающие для размеров элементов функции calc()
и медиазапросы, зависящие от ширины окна браузера и главного контейнера страницы. 

## Чтобы установить сборщик
1. clone this repo
2. npm i

## Команды сборщика
1. режим "development": gulp      /*при запуске сначала очищается всё, кроме images и fonts*/
2. режим "production": gulp --p   /*при запуске сначала делается полная очистка*/
3. очистка всего, кроме images и fonts: gulp clean
4. полная очистка: gulp clean --p