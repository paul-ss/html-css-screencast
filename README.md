# Скринкаст по вёрстке. Технопарк

### Установка
Чтобы помочь с выполнением первого домашнего задания, мы решили сделать этот скринкаст. Если на данный момент вы пребываете в растерянности и не знаете, откуда начать, то это нормально, а, главное, поправимо.

[Данный скринкаст](https://cloud.mail.ru/public/3pXZ/5oTbGG4WA) о том, как с нуля за 60 минут сделать вёрстку несложной страницы с формой авторизации. Оно без звука. Поэтому включайте любимый трек и смотрите его на скорости **1,5-2x**, а также не забудьте заглянуть в `static/page.html`, чтобы оценить конечный результат. Или сделайте всё в обратном порядке!

### Структура записи
#### 1. Настройка среды разработки
Чтобы верстать и мгновенно видеть результат в открытой вкладке браузера, понадобиться npm пакет **static-livereload**.

#### 2. Вёрстка компонент
Хороший разработчик, разглядывая макет или салфетку с наброском будущей страницы, мысленно разбивает её на самостоятельные части. В случае с формой авторизации всё очень просто. Нам понадобятся: пара кнопок, пара полей ввода, броский заголовок.
Эти элементы кажутся примитивными, но на самом деле у них есть *состояния* (кнопка нажата, инпут в фокусе, заголовок &mdash; в нескольких вариантах).
В `components.html` подготовим все компоненты и все их состояния.

#### 3. Форма
Имея на руках готовые компоненты, нетрудно собрать из них форму (копипастой, для максимальной простоты). Здесь главная задача &mdash; спозиционировать их в желаемом порядке и красиво оформить саму форму в `form.html`.

#### 4. Страница
Готовую форму переносим в центр `page.html` и дополняем её красивым логотипом и бекграундом.


### Что почитать
* [htmlacademy](https://htmlacademy.ru)
* [Вёрстка это не тупо](http://webmasters.teamdev.com/)
* [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Change Autocomplete Styles in WebKit Browsers](https://css-tricks.com/snippets/css/change-autocomplete-styles-webkit-browsers/)
* [Как сделать цвета на пару оттенков темнее-светлее для состояний кнопок](http://pinetools.com/darken-color)
