---
## Front matter
title: "Отчет по первому этапу проекта"
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

Добавить к сайту данные о себе.

Список добавляемых данных.
Разместить фотографию владельца сайта.
Разместить краткое описание владельца сайта (Biography).
Добавить информацию об интересах (Interests).
Добавить информацию от образовании (Education).
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору:
Управление версиями. Git.
Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Выполнение лабораторной работы

Разместить фотографию владельца сайта.

Зашел по адресу content/authors/admin удалил старую аватарку и поставил свою (рис. [-@fig:001])

![рис. 1](image/Screenshot_3.png){ #fig:001 width=70% }

Далее выгружаю файлы в репозиторий. (рис. [-@fig:002])(рис. [-@fig:003]) (рис. [-@fig:004]) (рис. [-@fig:005])

![рис. 2](image/Screenshot_11.png){ #fig:002 width=70% }

![рис. 3](image/Screenshot_5.png){ #fig:003 width=70% }
![рис. 4](image/Screenshot_6.png){ #fig:004 width=70% }

![рис. 5](image/Screenshot_7.png){ #fig:005 width=70% }

Разместить краткое описание владельца сайта (Biography).
Добавить информацию об интересах (Interests).
Добавить информацию от образовании (Education).

Зашел в по адресу content/authors/admin/_index.md и переписал все под себя. (рис. [-@fig:006])

![рис. 6](image/Screenshot_4.png){ #fig:006 width=70% }

И выгружаю в репозиторий (рис. [-@fig:007]) (рис. [-@fig:008]) (рис. [-@fig:009])

![рис. 7](image/Screenshot_11.png){ #fig:007 width=70% }
![рис. 8](image/Screenshot_8.png){ #fig:008 width=70% }
![рис. 9](image/Screenshot_15.png){ #fig:009 width=70% }

Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору:
Управление версиями. Git.

Зашел по адресу content/post скопировал две новых папки и в них отредактировал  файлы index.md под темы. (рис. [-@fig:010]) (рис. [-@fig:011])

![рис. 10](image/Screenshot_10.png){ #fig:010 width=70% }
![рис. 11](image/Screenshot_1.png){ #fig:011 width=70% }

И выгружаю в репозиторий (рис. [-@fig:012]) (рис. [-@fig:013])

![рис. 12](image/Screenshot_12.png){ #fig:012 width=70% }
![рис. 13](image/Screenshot_13.png){ #fig:013 width=70% }

Вот таким получился мой сайт shmakovmp.github.io (рис. [-@fig:014]) (рис. [-@fig:015]) (рис. [-@fig:016]) (рис. [-@fig:017])

![рис. 14](image/Screenshot_16.png){ #fig:014 width=70% }
![рис. 15](image/Screenshot_17.png){ #fig:015 width=70% }
![рис. 16](image/Screenshot_18.png){ #fig:016 width=70% }
![рис. 17](image/Screenshot_19.png){ #fig:017 width=70% }

# Выводы

В ходе работы я научился редактировать свой сайт и выкладывать новые посты.

