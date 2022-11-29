# Instruction for Github

## Основные команды

>**git config user.name** - инициализация имени пользователя

>**git config user.mail** - инициализация почты пользователя

>**git status** - текущее состояние гита, есть ли изменения, которые нужно закоммитить

>**git add file_name** - добавляет содержимое рабочего каталога

>**git commit -m "commit-message"** - зафиксировать или сохранить
> - -m - комментарий
> - -a - let us avoid repeating command add

>**git log** - получить информацию о сохраненных версиях

>**git checkout 1234** - переключение между версиями

>**git diff** - показать изменения

## Синтаксис языка Markdown

>* Жирный текст — **

>* Курсивный текст — *

>* Зачеркнутый текст — ~

>* Выделяют заголовки — # в начале строки

>* Показать уровень заголовка — 
подчеркивание знаками = или ****

>* Нумерованные Списки — обозначаются 
обычными цифрами **1, 2, 3**

>* Ненумерованные Списки — **обозначаются** * **знаками в начале строки**

>* Вложенные Списки — выполняем отступы

>* Цитата - используется знак «больше» («>»)

>* Создание ссылки - текст ссылки  заключается в квадратные скобки. Гиперссылка заключается в круглые скобки сразу после закрывающей квадратной, в них же возможно расположить название, заключенное в кавычки, которое будет отображаться при наведении, но этот пункт не является обязательным. [пример] (http://example.com/ "Необязательная подсказка")

## Изображения

### 2 способа вставки изображений в документ:

>1. **С помощью непосредственного указания URL-адреса изображения.**

![Альтернативный текст] (/путь/к/изображению.jpg)

Синтаксис состоит из следующих элементов:
* восклицательный знак;
* квадратные скобки, в которых указывается альтернативный изображению текст
* круглые скобки, содержащие URL-адрес или относительный путь изображения, а также (необязательно) всплывающую подсказку, заключённуе в двойные или одиночные кавычки.

>2. **С помощью метки-идентификатора.**

![Альтернативный текст] [id]

где «id» — имя определённой метки изображения. 

Метки изображений определяются при помощи синтаксиса, совершенно идентичного меткам гиперссылок:

[id] : путь/к/изображению 

git branch - посмотреть существующие ветки

git branch name - создать новую ветку

git merge - слияние веток

git checkout -b name - создать и перейти на новую ветку

Создаем конфликт для ДЗ# Instruction for Github

## Основные команды

>**git config user.name** - инициализация имени пользователя

>**git config user.mail** - инициализация почты пользователя

>**git status** - текущее состояние гита, есть ли изменения, которые нужно закоммитить

>**git add file_name** - добавляет содержимое рабочего каталога

>**git commit -m "commit-message"** - зафиксировать или сохранить
> - -m - комментарий
> - -a - let us avoid repeating command add

>**git log** - получить информацию о сохраненных версиях

>**git checkout 1234** - переключение между версиями

>**git diff** - показать изменения

## Синтаксис языка Markdown

>* Жирный текст — **

>* Курсивный текст — *

>* Зачеркнутый текст — ~

>* Выделяют заголовки — # в начале строки

>* Показать уровень заголовка — 
подчеркивание знаками = или ****

>* Нумерованные Списки — обозначаются 
обычными цифрами **1, 2, 3**

>* Ненумерованные Списки — **обозначаются** * **знаками в начале строки**

>* Вложенные Списки — выполняем отступы

>* Цитата - используется знак «больше» («>»)

>* Создание ссылки - текст ссылки  заключается в квадратные скобки. Гиперссылка заключается в круглые скобки сразу после закрывающей квадратной, в них же возможно расположить название, заключенное в кавычки, которое будет отображаться при наведении, но этот пункт не является обязательным. [пример] (http://example.com/ "Необязательная подсказка")

## Изображения

### 2 способа вставки изображений в документ:

>1. **С помощью непосредственного указания URL-адреса изображения.**

![Альтернативный текст] (/путь/к/изображению.jpg)

Синтаксис состоит из следующих элементов:
* восклицательный знак;
* квадратные скобки, в которых указывается альтернативный изображению текст
* круглые скобки, содержащие URL-адрес или относительный путь изображения, а также (необязательно) всплывающую подсказку, заключённуе в двойные или одиночные кавычки.

>2. **С помощью метки-идентификатора.**

![Альтернативный текст] [id]

где «id» — имя определённой метки изображения. 

Метки изображений определяются при помощи синтаксиса, совершенно идентичного меткам гиперссылок:

[id] : путь/к/изображению

## Работа с веткамми

>git branch - посмотреть существующие ветки

>git branch name - создать новую ветку

>git merge - слияние веток

>git checkout -b name - создать и перейти на новую ветку

## Работа с удаленными репозиториями

>git clone - склонировать внешний репозиторий на наш ПК

>git pull - позволяет скачать все из текущего репозитория и автоматически 
сделать merge с нашей версией

>git push - позволяет отправить нашу версию репозитория на внешний 
репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории

