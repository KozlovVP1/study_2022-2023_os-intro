---
## Front matter
title: "Презентация к лабораторной работе №9"
subtitle: "Текстовой редактор emacs"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Выполнение лабораторной работы

Ввел текст в созданный файл (рис. [-@fig:002]).

![Ввод текста в файл](image/2.png){#fig:002 width=70%}

Вырезал одну из строк и вставил ее в конец файла (рис. [-@fig:003]).

![Перемещение строки](image/3.png){#fig:003 width=70%}

Скопировал область в буфер обмена, вставил ее в конец файла (рис. [-@fig:004]).

![Копирование области в буфер обмена](image/4.png){#fig:004 width=70%}

Отменл последнее действие (рис. [-@fig:005]).

![Отмена действия](image/5.png){#fig:005 width=70%}

Переместился в начало и конец строки, начало и конец буфера (с помощью комбинаций клавиш)

Перешел в новый буфер (рис. [-@fig:007]).

![Переход в новый буфер](image/7.png){#fig:007 width=70%}

В каждом из окон создал новый буфер, ввел текст (рис. [-@fig:009]).

![Создание буферов, ввод текста](image/9.png){#fig:009 width=70%}

Поиск слова "строки" (рис. [-@fig:010]).

![Поиск слова](image/10.png){#fig:010 width=70%}

С помощью режима замена заменил буквы "о" на "А" (рис. [-@fig:011]).

![Замена слов/букв](image/11.png){#fig:011 width=70%}

Ответ на вопрос: Отличие от обычного режима в том, что тут появляется отдельное окно с текстом из файла с выделенными словами, которые нужно было найти.

# Выводы

Познакомился с операционной системой Linux. Получил практические навыки работы с редактором Emacs.

# Список литературы{.unnumbered}

::: {#refs}
:::
