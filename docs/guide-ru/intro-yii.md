Что такое Yii?
===========

Yii – это высокопроизводительный компонентный PHP фреймворк предназначенный для быстрой разработки современных Web приложений. Слово Yii (произносится `Йи` `[ji:]`) в китайском языке означает «простой и развивающийся». Так же, Yii расшифровывается как акроним **Yes It Is**!


Для каких задач Yii больше всего подходит?
---------------------

Yii – это универсальный фреймворк для Web разработки и может быть задействован во всех типах Web приложений. Благодаря его модульной структуре и мощной поддержке кеширования Yii особенно подходит для разработки таких крупных проектов как порталы, форумы, CMS, сервисы электронной коммерции, RESTful-приложения и т.п.


Сравнение Yii с другими фреймворками
-------------------------------------------

- Как и многие другие PHP фреймворки, в Yii реализована модель MVC (Model-View-Controller). Предполагается, что Ваш код будет организован в соответствии с этой моделью.
- Yii придерживается философии простого и элегантного кода не пытаясь усложнять дизайн только ради того, что бы следовать каким-либо принципам проектирования.
- Yii представляет собой full-stack фреймворк включая такой проверенный и готовый к использованию функционал, как ActiveRecord для реляционных и NoSQL баз данных, поддержка разработки RESTful API, многоуровневое кеширование и т.д.
- Yii черезвычайно масштабируем. Вы можете настраивать и изменять практически любую часть основного кода. Используйте преимущества модульной архитектуры применяя существующие или разрабатывая свои собственные расширения.
- Одна из главных целей Yii – производительность.

Yii — не проект одного человека. Он поддерживается и развивается силами [небольшой команды][] и довольно большим сообществом разработчиков, которые им помогают. Разработчики фреймворка следят за тенденциями веб разработки и развитием других проектов. Наиболее интересные возможности и лучшие практики регулярно внедряются в фреймворк в виде простых и элегантных интерфейсов.

[небольшой команды]: http://www.yiiframework.com/about/

Версии Yii
------------

На данный момент существует две основные ветки Yii: 1.1 и 2.0. Версия 1.1 является предыдущим поколением и находится в поддерживаемом состоянии. Версия 2.0 – это полностью переписанный Yii адоптированный к таким последним технологиям и протоколам как Composer, PSR, пространство имен, типажи (traits) и многие другие. Версия 2.0 представляет собой последнее поколение фреймворка и на ней будут сосредоточены основные усилия разработчиков несколько следующих лет. Данное руководство именно о версии 2.0.


Требования и предпосылки
------------------------------

Yii 2.0 requires PHP 5.4.0 or above. You can find more detailed requirements for individual features
by running the requirement checker included in every Yii release.

Для работы Yii 2.0 необходим PHP 5.4.0 и выше. Детальные требования покажет и проверит соответствующий скрипт, который включен в Yii. Для использования Yii требуются базовые знания Объектно-Ориентированного программирования, т.к. Yii основан на ООП. Yii 2.0 так же использует такой новый функционал PHP как  [пространство имен](http://www.php.net/manual/en/language.namespaces.php) и [типажи](http://www.php.net/manual/en/language.oop5.traits.php). Понимание этих концепций поможет быстрее разобраться в Yii 2.0.
