---
## Front matter
title: "Лабораторная работа №13. Презентация"
subtitle: "Средства, применяемые при разработке программного обеспечения в ОС типа UNIX/Linux"
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

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

# Выполнение лабораторной работы

Написал программу calculate.c (рис. [-@fig:1])

![calculate.c](image/11.png){#fig:1 width = 70%}

Написал программу calculate.h (рис. [-@fig:2])

![calculate.h](image/12.png){#fig:2 width = 70%}

Написал программу main.c (рис. [-@fig:3])

![main.c](image/13.png){#fig:3 width = 70%}

Написал программу Makefile (рис. [-@fig:4])

![Makefile](image/14.png){#fig:4 width = 70%}

Открыл дебаггер и запустил программу (рис. [-@fig:6])

![Запуск программы в отладчике](image/2.png){#fig:6 width = 70%}

Просмотрел строки кода с помощью команды list (рис. [-@fig:7])

![Команда list](image/3.png){#fig:7 width = 70%}

Установил точку останова (рис. [-@fig:9])

![Установка точки останова](image/5.png){#fig:9 width = 70%}

Запуск программы с точкой останова (рис. [-@fig:10])

![Запуск программы](image/6.png){#fig:10 width = 70%}

Удаление точки останова (рис. [-@fig:11])

![Удаление точки останова](image/7.png){#fig:11 width = 70%}

# Выводы

Приобрел простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

# Список литературы{.unnumbered}

::: {#refs}
:::
