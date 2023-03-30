---
## Front matter
title: "Лабораторная работа №8"
subtitle: "Текстовой редактор vi"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Выполнение лабораторной работы

Создал каталог с именем ~/work/os/lab08, создал в нем файл hello.sh (рис. [-@fig:001]).

![Создание каталога и файла](image/1.png){#fig:001 width=70%}

Нажал клавишу i и ввел текст в файл (рис. [-@fig:002]).

![Ввод текста](image/2.png){#fig:002 width=70%}

Сделал файл исполняемым (рис. [-@fig:004]).

![Изменение прав доступа](image/4.png){#fig:004 width=70%}

Открыл файл с помощью команды vi, заменил HELL на HELLO (рис. [-@fig:006]).

![Редактирование файла](image/6.png){#fig:006 width=70%}

Стер слово LOCAL и написал local вместо него (рис. [-@fig:007]).

![Редактирование файла](image/7.png){#fig:007 width=70%}

Всатвил строку echo $HELLO в конец файла (рис. [-@fig:008]).

![Добавление строки](image/8.png){#fig:008 width=70%}

Перешел в командный режим, удалил последнюю строку, дважды нажав на клавишу d (рис. [-@fig:009]).

![Удаление строки](image/9.png){#fig:009 width=70%}

Отменил последнее изменение с помощью команды u (рис. [-@fig:010]).

![Отмена изменения](image/10.png){#fig:010 width=70%}

# Выводы

Познакомился с операционной системой Linux. Получил практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Список литературы{.unnumbered}

::: {#refs}
:::
