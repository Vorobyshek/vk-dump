Первый абзац
***
Второй абзац
или

Первый абзац
---
Второй абзац
Далее - заголовки и прочее:

h1 заголовок первого уровня
=====================
h2 заголовок второго уровня
-----------------------------------
### h3 заголовок третьего уровня
#### h4 заголовок четвёртого уровня
##### h5 заголовок пятого уровня
###### h6 заголовок шестого уровня
Оформление ссылки [Видимая часть, название ссылки] (http://webdesign.ru.net адрес ссылки - невидимая часть)

[Мой сайт](http://webdesign.ru.net)
Если заключить адрес в угловые скобки, то он автоматически станет ссылкой

<http://webdesign.ru.net>
Выделение жирным шрифтом

**Жирный шрифт**
***Наклонный жирный***
Выделение тёмным фоном прямо в тексте

`выделенные слова`
Блок текста с более тёмным фоном, четыре пробела (и более) от начала каждой строки

    dir /fonts
    dir /images
    dir /js
Блоки текста с подвеченным синтаксисом. Выделенный цветом фона блок с html-кодом. Теги выделяются цветом по правилам html

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
Выделенный цветом фона блок с php-кодом. Теги выделяются цветом по правилам php

```php
<?php here_pagecontent(); ?>
```
Выделенный цветом фона блок с каскадными таблицами. Теги выделяются цветом по правилам css

```scss /* или css */
@import "bower_components/tree-normalize/generic.normalize";
h1 {
 font-size:1.5em;
 font-weight: 300;
}
```
И так далее...

Блок текста, выделенный тёмной полосой по левому краю (цитата)

> Текст
> 
> Продолжение текста выделенного блока
> Завершение текста
Допустимы вложенные цитаты (цитата в цитате). Тогда цитата второго уровня выделяется двумя знаками ">>", а цитата третьего уровня вложенности - тремя.

Таблица с чередованием светлых и тёмных строк (зебра)

Название файла  | Содержание файла
----------------|----------------------
style.css       | Пустой файл каскадной таблицы стилей, в который производится сбока необходимых стилей
reset.css       | Reset CSS от Эрика Мейера
normalize.css   | Нормалайзер CSS от Nicolas Gallagher
block.css       | Основные стили блоков системы
addition.css    | Дополнительные стили
fontawesome.css | Стили иконочного шрифта
layout.css      | Основные стили, применительно к определённому сайту
lightbox.css    | Стили лайтбокса, если таковой используется
index.html      | Индексный файл для проверки вносимых изменений
<li> Листинг - ненумерованый список

* Пункт 1
* Пункт 2
* Пункт 3
Нумерованный список создаётся ещё проще:

1. Пункт 1
2. Пункт 2
3. Пункт 3
italic - наклонный шрифт. Пробел, знак препинания или подчёркивание отменяют правило маркера

_наклонный_ _шрифт_ _наклонный__шрифт_
Комбинируя эти маркеры вы сможете правильно разметить свой текст, сделать его более понятным.

Надеюсь, что эта статья будет вам полезна. Успехов в работе на GitHub!

UPDATE!

Вставка изображения в текст

![screenshot of sample](http://webdesign.ru.net/images/Heydon_min.jpg)
