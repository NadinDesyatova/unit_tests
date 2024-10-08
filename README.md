# Домашнее задание к лекции «Unit-тестирование»

## Чистые функции

[![Build status](https://ci.appveyor.com/api/projects/status/kxsa8vm5eht5xvyq?svg=true)](https://ci.appveyor.com/project/NadinDesyatova/unit-tests)


### Описание

Реализована функция, которая должна отображать состояние здоровья игрового персонажа.
На вход она принимает объект вида:
```javascript
{name: 'Маг', health: 90}
```
И возвращает ответ в виде одной из строк: `healthy`(здоровье более 50), `wounded`(здоровье от 50 и до 15), `critical`(менее 15)

Сгенерирован проект на базе `npm`, туда подключен `jest` и написаны авто-тесты.

---