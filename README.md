## Админка дял сайта НКО «ФАР»

#### Технологический стек: HTML, CSS, JavaScript, React, Styled compopents express, mongoDB, webpack, strapi, npm, git, linux, bash

#### Реализованные возможности:

Для реализации админки сайта используется headless CMS Strapi
Написан плагин для управления пунктами меню (сортировка, подключение целевых страниц)
Кастомизирован текстовый редактор для поля с контентом
Практически весь контент на страницах можно изменять
Так же можно создавать шаблонные страницы


https://far.listen-me.ru/api/admin


requirements:

"engines": {

    "node": ">=10.16.0 <=14.x.x",
    
    "npm": "^6.0.0"
    
  }

Запускается: 

npm i

NODE_ENV=production npm run build

npm start / pm2 start
  
