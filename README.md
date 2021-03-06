<img src="images/cover.png"/>

# Об этой книге

Эта книга рассказывает о парадигме функционального программирования в общем. Мы будем использовать самый популярный в мире функциональный язык программирования: JavaScript. Некоторые из вас могут сказать, что это не самый удачный выбор, потому что в данный момент в JavaScript преобладают императивные тенденции. Однако, я считаю, что JavaScript — это лучший способ знакомства с функциональным программированием по нескольким причинам:

 * Вы, скорее всего, и так каждый день используете его в своей работе.

    Это открывает возможность воспользоваться полученным знанием в реальных прикладных программах, в отличие от тех проектов, которые вы пишите в качестве хобби по выходным на каком-нибудь экзотическом языке.

 * Вам не потребуется учить язык с нуля для того, чтобы начать писать программы.

    В чисто функциональном языке у вас не получится залогировать значение переменной или получить элемент DOM без использования монад. Пока мы не освоили все приёмы функционального программирования, благодаря смешанной парадигме JS, можно немного сжульничать и воспользоваться приёмами из ООП.

 * JS отлично подходит для написания первоклассного функционального кода.

    В JS у нас есть всё что нужно для имитации Scala или Haskell с помощью парочки небольших библиотек. В данный момент ООП доминирует в индустрии, но он очень неудобен в Javascript’е, примерно также, как пойти с палатками на трассу или танцевать чечётку в сапогах. Чтобы случайно не потерять контекст `this`, мы повсеместно используем `bind`. Забыли написать `new`? Будьте готовы к причудливым ошибкам. В JS пока что нет классов, а приватные поля доступны только через замыкания.  Многие из нас считают функциональное программирование более подходящим вариантом для JS.

Учитывая всё вышесказанное, бесспорно, лучше всего для примеров из этой книги подойдут типизированные функциональные языки. JavaScript поможет нам познакомиться с подходом к программированию функционально, какой язык использовать для его применения — решать вам. К счастью, все интерфейсы математические и, посему, универсальные. Вы будете комфортно себя чувствовать, используя swiftz, haskell, purescript и другие математически-ориентированные языки.


# Gitbook (на английском)

http://drboolean.gitbooks.io/mostly-adequate-guide/

### EPUB (на английском)

https://www.gitbook.com/download/epub/book/drboolean/mostly-adequate-guide

### Mobi (Kindle) (на английском)

https://www.gitbook.com/download/mobi/book/drboolean/mostly-adequate-guide

### Вы можете сами собрать эту книгу

```
git clone https://github.com/MostlyAdequate/mostly-adequate-guide-ru

cd mostly-adequate-guide-ru/
npm install gitbook-cli -g
gitbook init

brew update
brew cask install calibre

gitbook mobi . ./functional.mobi
```

# Другие языки

* [English (original)](https://github.com/MostlyAdequate/mostly-adequate-guide)
* [French](https://github.com/MostlyAdequate/mostly-adequate-guide-fr) 
* [Português](https://github.com/MostlyAdequate/mostly-adequate-guide-pt-BR)
* [Russian](https://github.com/MostlyAdequate/mostly-adequate-guide-ru)
* [中文版](https://github.com/llh911001/mostly-adequate-guide-chinese)


# Содержание

*Перевод названия главы будет появляться как только будет доступен перевод самой главы.*

## Часть 1

* [Глава 1: О чём вообще пойдёт речь?](ch1-ru.md)
  * [Вступление](ch1-ru.md#Вступление)
  * [Краткое знакомство](ch1-ru.md#Краткое-знакомство)
* [Глава 2: Функции первого класса](ch2-ru.md)
  * [Краткий обзор](ch2-ru.md#Краткий-обзор)
  * [Зачем отдавать предподчтение первому классу?](ch2-ru.md#Зачем-отдавать-предподчтение-первому-классу)
* [Chapter 3: Pure Happiness with Pure Functions](ch3.md)
  * [Oh to be pure again](ch3.md#oh-to-be-pure-again)
  * [Side effects may include...](ch3.md#side-effects-may-include)
  * [8th grade math](ch3.md#8th-grade-math)
  * [The case for purity](ch3.md#the-case-for-purity)
  * [In Summary](ch3.md#in-summary)
* [Chapter 4: Currying](ch4.md)
  * [Can't live if livin' is without you](ch4.md#cant-live-if-livin-is-without-you)
  * [More than a pun / Special sauce](ch4.md#more-than-a-pun--special-sauce)
  * [In Summary](ch4.md#in-summary)
* [Chapter 5: Coding by Composing](ch5.md)
  * [Functional Husbandry](ch5.md#functional-husbandry)
  * [Pointfree](ch5.md#pointfree)
  * [Debugging](ch5.md#debugging)
  * [Category Theory](ch5.md#category-theory)
  * [In Summary](ch5.md#in-summary)
* [Chapter 6: Example Application](ch6.md)
  * [Declarative Coding](ch6.md#declarative-coding)
  * [A flickr of functional programming](ch6.md#a-flickr-of-functional-programming)
  * [A Principled Refactor](ch6.md#a-principled-refactor)
  * [In Summary](ch6.md#in-summary)

## Часть 2

* [Chapter 7: Hindley-Milner and Me](ch7.md)
  * [What's your type?](ch7.md#whats-your-type)
  * [Tales from the cryptic](ch7.md#tales-from-the-cryptic)
  * [Narrowing the possibility](ch7.md#narrowing-the-possibility)
  * [Free as in theorem](ch7.md#free-as-in-theorem)
  * [In Summary](ch7.md#in-summary)
* [Chapter 8: Tupperware](ch8.md)
  * [The Mighty Container](ch8.md#the-mighty-container)
  * [My First Functor](ch8.md#my-first-functor)
  * [Schrödinger’s Maybe](ch8.md#schrodingers-maybe)
  * [Pure Error Handling](ch8.md#pure-error-handling)
  * [Old McDonald had Effects…](ch8.md#old-mcdonald-had-effects)
  * [Asynchronous Tasks](ch8.md#asynchronous-tasks)
  * [A Spot of Theory](ch8.md#a-spot-of-theory)
  * [In Summary](ch8.md#in-summary)
* [Chapter 9: Monadic Onions](ch9.md)
  * [Pointy Functor Factory](ch9.md#pointy-functor-factory)
  * [Mixing Metaphors](ch9.md#mixing-metaphors)
  * [My chain hits my chest](ch9.md#my-chain-hits-my-chest)
  * [Theory](ch9.md#theory)
  * [In Summary](ch9.md#in-summary)
