# Проект "Лучшие друзья"

## Описание
Одностраничный сайт, для благотворительного фонда "Лучшие друзья", выполненный в рамках дополнительного проекта на курсе "Веб-разработчик" в Яндекс.Практикуме. Проект выполнен в команде с однокурсником [Антоном Войтенко](https://github.com/tohaly) и был выбран заказчиком лучшим среди работ других студентов. В ближайшем будущем новый сайт будет размещен [здесь](https://bestbuddies.ru/).

Фонд «Лучшие друзья» помогают людям с нарушениями развития познакомиться и подружиться со сверстниками без инвалидности, найти работу и жить самостоятельно. На сайте размещена компания по сбору средств на спортивные тренеровки по волейболу и футболу для людей с нарушением развития и интеллекта.

## Реализованный функционал
На сайте размещена форма по отправке пожертвований для Фонда. Прием платежей осущевляется посредством виджета CloudPayments, есть возможность как выбрать предложенную сумму, так и ввести свою, совершить как разовое пожертвование, так и оформить ежемесячный платеж. Для отслеживания суммы пожертвований реализован прогресс-бар. Для демонстрации его функционала используется сервис [Shetty](https://sheety.co/), который заносит все платежи в Google-таблицу, откуда сайт забирает данные посредством fetch запросов и заполняет прогресс-бар. Для удобства все изменямые значения (ссылка на таблицу, токен доступа, требуемая сумма для сбора, ID платежной системы) вынесены в отдельный config файл.
О сайте можно рассказать друзьям, для этого присутствуют share-кнопки популярных социальных сетей. Фотогалерея Фонда реализована с помощью плагина Slider.js.
Сайт адаптирован под все популярные разрешения устройств.


## Используемые технологии

Нативный JS, CSS, HTML, WebPack, GIT, Babel.

## Локальный запуск
1. Склонировать репозиторий
2. Доставить отсутствующие модули npm
    ```
        npm install
    ```
3. Запустить локальный сервер
    ```
        npm run dev
   ```

## Продакшн сборка
1. Склонировать репозиторий
2. Доставить отсутствующие модули npm
    ```
        npm install
    ```
3. Запустить сборку проекта
    ```
        npm run build
   ```

## Ссылка на проект

https://andrewlapshov.github.io/Project-4_BestBuddies/
