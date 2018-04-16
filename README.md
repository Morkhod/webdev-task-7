# Задача «Владимир Иванович слишком занят»

Перед выполнением задания внимательно прочитайте:

- [О всех этапах проверки задания](https://github.com/urfu-2017/guides/blob/master/workflow/overall.md)
- [Как отправить пулл](https://github.com/urfu-2017/guides/blob/master/workflow/pull.md)
- [Как пройти тесты](https://github.com/urfu-2017/guides/blob/master/workflow/test.md)
- Правила оформления [javascript](https://github.com/urfu-2017/guides/blob/master/codestyle/js.md), [HTML](https://github.com/urfu-2017/guides/blob/master/codestyle/html.md) и [CSS](https://github.com/urfu-2017/guides/blob/master/codestyle/css.md) кода

## Основное задание

Билли решил сравнить две базы данных: `MongoDB` и `PostgreSQL`, чтобы решить, какая из них лучше подходит
для его магазина.

Как вы могли заметить, необходимые для работы магазина запросы к `MongoDB` у него уже есть.
Теперь Билли хочет реализовать ту же логику с PostgreSQL.

Он попросил помочь ему в этом Владимира Ивановича, но у него слишком много пар.
Поэтому Билли обратился за помощью к вам.

### Требования

В папке dump находится дамп базы данных со следующими таблицами:
- `cart_souvenir`: содержит информацию о содержимом корзин
- `carts`: содержит информацию о корзине юзера
- `countries`: содержит информацию о странах
- `reviews`: содержит информацию об отзывах на сувениры
- `souvenir_tags`: содержит информацию о принадлежности тэга к сувениру
- `souvenirs`: содержит информацию о сувенирах
- `tags`: содержит информацию о тэгах
- `users`: содержит информацию о юзерах

Для выполнения домашнего задания будет удобно восстановить
базу данных на локальной PostgreSQL, воспользовавшись командой
`psql -h localhost -p 5432 --username postgres -f dump/dump.backup` и введя
пароль `urfu`.

Билли подготовил для вас три файла:
- `playground.js`, который может использоваться для тестирования запросов
- `index.js`, в котором можно указать связи между моделями
- `queries.js`, в котором нужно дописать запросы к базе данных

Конкретные требования к запросам Билли оформил в виде комментариев в файле `queries.js`.

![Новак](https://pp.userapi.com/c9436/u34304640/96566996/x_26a8b21a.jpg)
