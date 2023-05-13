---
## Front matter
title: "Лабораторная работа №14. Презентация"
subtitle: "Именованные каналы"
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

Приобретение практических навыков работы с именованными каналами.

# Выполнение лабораторной работы

Создал файл client.c (рис. [-@fig:1])

![client.c](image/1.png){#fig:1 width = 70%}

Создал client2.c (рис. [-@fig:2])

![client2.c](image/2.png){#fig:2 width = 70%}

Создал common.h (рис. [-@fig:3])

![common.h](image/3.png){#fig:3 width = 70%}

Создал server.c (рис. [-@fig:4])

![server.c](image/4.png){#fig:4 width = 70%}

Создал Makefile (рис. [-@fig:5])

![Makefile](image/5.png){#fig:5 width = 70%}

Запустил команду make (рис. [-@fig:6])

![Запуск команды make](image/6.png){#fig:6 width = 70%}

Запустил исполняемые файлы (рис. [-@fig:7])

![Запуск исполняемых файлов](image/7.png){#fig:7 width = 70%}

# Выводы

Приобрел практические навыки работы с именованными каналами.

# Список литературы{.unnumbered}

::: {#refs}
:::
