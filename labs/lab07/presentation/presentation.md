---
## Front matter
title: "Лабораторная работа №7"
subtitle: "Командная оболочка Midnight Commander"
author: "Козлов Всеволод Павлович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение основных возможностей командной оболочки Midnight Commander. 

Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Выполнение лабораторной работы

Запустил mc (рис. [-@fig:002]).

![Запуск mc](image/2.png){#fig:002 width=70%}

Перемещение одного из файлов (рис. [-@fig:003]).

![Перемещение файла](image/3.png){#fig:003 width=70%}

Получил информацию о размере и правах доступа на файл (рис. [-@fig:004]).

![Информация о файле](image/4.png){#fig:004 width=70%}

Открыл расширенный формат списка через меню левой (или правой) панели (рис. [-@fig:005]).

![Расширенные настройки списка](image/5.png){#fig:005 width=70%}

Редактирую содержимое созданного файла test.txt (рис. [-@fig:006]).

![Редактирование файла](image/6.png){#fig:006 width=70%}

Создаю каталог (рис. [-@fig:007]).

![Создание каталога](image/7.png){#fig:007 width=70%}

Поиск файла .cpp с функций main() (рис. [-@fig:010]).

![Поиск файла](image/10.png){#fig:010 width=70%}

Перешел в домашний каталог (рис. [-@fig:011]).

![Переход в домашний каталог](image/11.png){#fig:011 width=70%}

Осуществил анализ файлов меню (рис. [-@fig:012]).

![Анализ файлов меню](image/12.png){#fig:012 width=70%}

Изменил структуру экрана mc (рис. [-@fig:014]).

![Структура экрана](image/14.png){#fig:014 width=70%}

Создал файл test.txt и вставил в него текст (рис. [-@fig:015]).

![Создание файла test.txt и его редактирование](image/15.png){#fig:015 width=70%}

Удалил строку текста (ctrl + y), выделил фрагмент текста и скопировал на новую строку (f6), сохранил файл (рис. [-@fig:016]).

![Дальнейшее редактирование файла](image/16.png){#fig:016 width=70%}

Перешел в конец и начало файла, дописал текст (ctrl + END/ctrl + HOME) (рис. [-@fig:017]).

![Переход в начало и конец файла](image/17.png){#fig:017 width=70%}

Открыл файл .cpp через mc (рис. [-@fig:018]).

![Запуск файла .cpp](image/18.png){#fig:018 width=70%}

Отключил подсвету синтаксиса (рис. [-@fig:019]).

![Отключение подсветки синтаксиса ](image/19.png){#fig:019 width=70%}

# Выводы

Освоил основные возможности командной оболочки Midnight Commander. 

Приобрел навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Список литературы{.unnumbered}

::: {#refs}
:::
