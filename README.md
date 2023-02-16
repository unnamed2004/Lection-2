# Lection-2
 ## Function declaration




function declaration определяет функцию с указанными параметрами.


function calcRectArea(width, height) {

  return width * height;

}

console.log(calcRectArea(5, 6)); //5*6

// Expected output: 30 


### Global Scope 

Наше здание представляет собой вложенную программу
набор правил области действия. Первый этаж здания
представляет вашу текущую область действия,
где бы ты ни был. Верхний уровень здания находится
глобальный охват.

![](https://github.com/saidovv/Functions/blob/master/img/4.jpg)




## R

Functions
A function is a block of code that can be declared once and called as many times as needed. Functions return a single value. Functions in JavaScript are objects, more specifically, they are objects of type Function.

(tajik language) Функсия блоки кодест, ки онро як маротиба эълон кардан мумкин аст ва чанд маротиба даъват кардан мумкин аст. Функсияҳо арзиши ягонаро бармегардонанд. Функсияҳо дар JavaScript объектҳо мебошанд, аниқтараш, онҳо объектҳои навъи Function мебошанд.

Function – Declaration
The syntax to declare a function is:



-A function is declared using the function keyword. -The body of function is written within {}.

(tajik language) -Функсия бо истифода аз калимаи калидии function эълон карда мешавад. -Бадани функсия дар дохили {} навишта шудааст.



Function – Expression


Variable x is used to store the function. Here the function is treated as an expression. And the function is called using the variable name.

The function is called an anonymous function

(tajik language) Тағирёбандаи x барои нигоҳ доштани функсия истифода мешавад. Дар ин ҷо функсия ҳамчун ифода баррасӣ карда мешавад.Ва функсия бо истифода аз номи тағирёбанда даъват карда мешавад.

Ин функсия функсияи беном номида мешавад

SCOPE
Scope – Lexical Scope



Scope –Global Scope



Scope – Local Scope



Hoisting – Function Declaration


Hoisting – Function Expression


Recursion
Recursion is a process of calling itself. A function that calls itself is called a recursive function.

(tajik language) Рекурсия як раванди даъвати худ аст. Функсияе, ки худаш худашро даъват мекунад!

Closure
Closure is one of the most important, and often least understood, concepts in JavaScript. You can think of closure as a way to “remember” and continue to access a function’s scope (its variables) even once the function has finished running.

(tajik language)

Замыкания функсияе мебошад ки дар ретурни функсияи дигар меояд!