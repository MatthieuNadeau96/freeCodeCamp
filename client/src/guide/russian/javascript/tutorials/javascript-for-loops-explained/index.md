---
title: JavaScript for Loops Explained
localeTitle: JavaScript для пояснений
---
Оператор for создает цикл, который состоит из трех необязательных выражений, заключенных в круглые скобки и разделенных точками с запятой, за которыми следует оператор или набор операторов, выполняемых в цикле.

Цикл for имеет следующий синтаксис:
```
for (<a href='http://forum.freecodecamp.com/t/javascript-while-loop/14668' target='_blank' rel='nofollow'>initialization]; [condition]; [final-expression]) { 
    code block to be executed 
 } 
```

\[Инициализация\] выполняется до начала цикла (блок кода).

\[условие\] определяет условие для запуска цикла (блок кода).

\[final-expression\] выполняется каждый раз после того, как цикл (блок кода) был выполнен.

## Пример в JavaScript:
```
var ourArray = []; 
 for (var i = 0; i < 5; i++) { 
    ourArray.push(i); 
 } 
```

Из приведенного выше примера вы можете прочитать:

\[initialization\] устанавливает переменную перед запуском цикла (var i = 0).

\[условие\] определяет условие запуска цикла (я должен быть меньше 5).

\[final-expression\] увеличивает значение (i ++) каждый раз, когда выполняется кодовый блок в цикле.

## Почему нам нужны «для циклов»?

Для циклов используются для циклического преобразования кода кода в известное количество раз. Иногда компьютер знает, сколько раз, а не вы, но это все еще известно.

Оформить заказ на некоторые другие наши статьи по циклам:

*   \[While Loop
*   [Для In Loop](http://forum.freecodecamp.com/t/javascript-for-in-loop/14665)