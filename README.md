# Задача «Прокачай кота»

> Мы очень хотим, чтобы код вы написали сами, а не пользовались внешними библиотеками.

## Основное задание

:warning: Задание необходимо выполнить, **не используя JS**.

В этом задании вам нужно придумать и сверстать форму, например, такую:

<img src="https://yastatic.net/s3/lyceum/ifmo-homeworks/pimp-your-cat.png" title="Прокачай кота" />

<br />
<br />

Форма обязательно должна содержать кнопку отправки формы, поля ввода, чекбоксы и радиокнопки. Остальные элементы форм на ваше усмотрение.

Требования:
- названия полей форм `label` привязаны к своим полям: при нажатии на название фокус должен перейти в поле ввода
- для `input` задан подходящий `type` для удобного заполнения с телефона
- реализованы [кастомные элементы форм](http://wtfforms.com)

## Дополнительное задание

- опишите контекст использования вашей формы, объясните, какие [UI/UX-паттерны](http://ui-patterns.com/patterns/getting-input/list) вы использовали, какие решения приняли и почему.
- при организации вёрстки использована [методология БЭМ](https://ru.bem.info/)

## Доступные команды

> Перед тем, как запускать приведенные ниже команды, необходимо установить зависимости с помощью команды `npm install`

Запускаются так: `npm run <command>`

| Команда   | Действие               |
| --------- | ---------------------- |
| lint      | Проверка кода линтером |
| lint:html | Линтинг HTML           |
| lint:css  | Линтинг CSS            |
| format    | Форматирование кода    |
