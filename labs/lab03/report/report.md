---
## Front matter
title: "Лабораторная работа 3"
author: "Щетинин Даниил Николаевич"

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


    Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.
    
# Задание

   Создать отчёт по предыдущей лабораторной работе в формате Markdown.
   
# Выполнение лабораторной работы 

Для создания отчета о нашей работе нужно начать с шаблона, предоставленного в папке report нашего репозитория

(рис. @fig:001).

![report.md](image/1.jpg){#fig:001 width=70%}

Начнем редактировать шаблон: Установим цель работы, задание, название, автора

(рис. @fig:002).

![Начало](image/2.jpg){#fig:002 width=70%}

Перейдём к оформлению отчёта, для этого нужно описать выполняемые действия и вставлять картинки о выполненной работе 

(рис. @fig:003).

![Картинка](image/3.jpg){#fig:003 width=70%}



Для того, чтобы вставить картинку, нужно скопировать ее в папку image. 

(рис. @fig:004).

![Пример папки](image/4.jpg){#fig:004 width=70%}

После завершения отчета, требуется скомпилировать его для предоставления в формате pdf с помощью команды make

(рис. @fig:005).

![команда make](image/5.jpg){#fig:005 width=70%}


# Выводы

Я создал отчет в маркдаун 

