# Custom featured section (Dawn)
[DEMO](https://tpxnqohm41enxtqh-67706716396.shopifypreview.com)

Password: Password29

## Description
До стандартної теми Dawn додана кастомна секція Featured Products. Вона виводить список рекомендованих продуктів, які йдуть з колекції, яку можна вибрати через кастомайз теми. Якщо товар із колекції вже є в кошику - цей товар не виводиться в секції (при перезавантаженні сторінки). При кліку на кнопку “Add to cart” товар додається в кошик та вискакує popup (але тільки за наявності ще однієї секції з можливістю add to cart. якщо другої секції немає - редірект у корзину).

## Local development
### Dependencies (Windows)
* Node.js 18 or higher.
* NPM v6.14.4 and higher
* Ruby+Devkit 3.0, installed using RubyInstaller for Windows
(select the MSYS2 component and the MSYS2 base installation option)
* Git
* Bundler 2.3.8 or higher
* gulp
* @shopify/cli

### Installing
* Fork and clone this repository
* Run `npm install` in your terminal
* Run `shopify theme dev --store {polinavafik-refactor}` (only first time, after that just`shopify theme dev`)
