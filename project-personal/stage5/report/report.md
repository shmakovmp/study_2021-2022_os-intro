---
## Front matter
title: "Отчет по 5 этапу проекта"
subtitle: "Дисциплина: операционные системы"
author: "Шмаков Максим Павлович"

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

# Задание

Сделать записи для персональных проектов.
Сделать пост по прошедшей неделе.
Добавить пост на тему "Языки научного программирования".

# Выполнение лабораторной работы

Сделать записи для персональных проектов.

Захожу в work/blog/content/project и переименовываю папку на название моего проекта. (рис. [-@fig:001]) (рис. [-@fig:002])

![рис. 1](image/Screenshot_1.png){ #fig:001 width=70% }

![рис. 2](image/Screenshot_2.png){ #fig:002 width=70% }

Захожу в папку, меняю картинку и редактирую файл index.md, где я написал про свой проект.  (рис. [-@fig:003]) (рис. [-@fig:004])

![рис. 3](image/Screenshot_3.png){ #fig:003 width=70% }

![рис. 4](image/Screenshot_5.png){ #fig:004 width=70% }

Сделать пост по прошедшей неделе.
Добавить пост на тему "Языки научного программирования".

Тут уже знакомый процесс.

Захожу в work/blog/content/post, создаю 2 новых папки с постами, меняю картинки и редактирую файлы index.md.  (рис. [-@fig:005]) (рис. [-@fig:006])

![рис. 5](image/Screenshot_6.png){ #fig:005 width=70% }

![рис. 6](image/Screenshot_7.png){ #fig:006 width=70% }

Строю сайт и выгружаю все файлы в репозиторий.  (рис. [-@fig:007]) (рис. [-@fig:008])

![рис. 7](image/Screenshot_8.png){ #fig:007 width=70% }

![рис. 8](image/Screenshot_9.png){ #fig:008 width=70% }

Таким в итоге получился сайт. (рис. [-@fig:009]) (рис. [-@fig:010]) (рис. [-@fig:011])

![рис. 9](image/Screenshot_10.png){ #fig:009 width=70% }

![рис. 10](image/Screenshot_11.png){ #fig:010 width=70% }

![рис. 11](image/Screenshot_12.png){ #fig:011 width=70% }


# Выводы

В ходе работы я выложил информацию о своем проекте на сайт и 2 новых поста.

