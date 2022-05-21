---
## Front matter
title: "Отчет по 4 этапу проекта"
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

Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
eLibrary : https://elibrary.ru/;
Google Scholar : https://scholar.google.com/;
ORCID : https://orcid.org/;
Mendeley : https://www.mendeley.com/;
ResearchGate : https://www.researchgate.net/;
Academia.edu : https://www.academia.edu/;
arXiv : https://arxiv.org/;
github : https://github.com/.

Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору:
Оформление отчёта.
Создание презентаций.
Работа с библиографией.

# Выполнение лабораторной работы

Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
eLibrary : https://elibrary.ru/;

Захожу на сайт, в регистрационной форме ввожу свои данные и регистрирую аккаунт. (рис. [-@fig:001])

![рис. 1](image/Screenshot_1.png){ #fig:001 width=70% }

Google Scholar : https://scholar.google.com/;

Захожу на сайт (рис. [-@fig:002]), вхожу в свой аккаунт гугл (рис. [-@fig:003]) (рис. [-@fig:004]), далее ввожу свои данные, задаю настройки и создаю аккаунт. (рис. [-@fig:005]) (рис. [-@fig:006]) (рис. [-@fig:007]) (рис. [-@fig:008])

![рис. 2](image/Screenshot_2.png){ #fig:002 width=70% }

![рис. 3](image/Screenshot_3.png){ #fig:003 width=70% }

![рис. 4](image/Screenshot_4.png){ #fig:004 width=70% }

![рис. 5](image/Screenshot_5.png){ #fig:005 width=70% }

![рис. 6](image/Screenshot_6.png){ #fig:006 width=70% }

![рис. 7](image/Screenshot_7.png){ #fig:007 width=70% }

![рис. 8](image/Screenshot_8.png){ #fig:008 width=70% }

ORCID : https://orcid.org/;

Захожу на сайт (рис. [-@fig:009]), ввожу свои данные (рис. [-@fig:010]) , задаю пароль для аккаунта (рис. [-@fig:011]) выбираю опцию, чтобы все могли видеть контент моего профиля (рис. [-@fig:012]) и регистрирую новый аккаунт (рис. [-@fig:013]).

![рис. 9](image/Screenshot_9.png){ #fig:009 width=70% }

![рис. 10](image/Screenshot_10.png){ #fig:010 width=70% }

![рис. 11](image/Screenshot_11.png){ #fig:011 width=70% }
 
![рис. 12](image/Screenshot_12.png){ #fig:012 width=70% }
 
![рис. 13](image/Screenshot_13.png){ #fig:013 width=70% }

Mendeley : https://www.mendeley.com/;

Захожу на сайт (рис. [-@fig:014]), ввожу свою почту (рис. [-@fig:015]) , свое имя, фамилию и пароль (рис. [-@fig:016]), и регистрирую свой новый аккаунт(рис. [-@fig:017]) (рис. [-@fig:018]).

![рис. 14](image/Screenshot_14.png){ #fig:014 width=70% }

![рис. 15](image/Screenshot_15.png){ #fig:015 width=70% }

![рис. 16](image/Screenshot_16.png){ #fig:016 width=70% }
 
![рис. 17](image/Screenshot_17.png){ #fig:017 width=70% }
 
![рис. 18](image/Screenshot_18.png){ #fig:018 width=70% }

ResearchGate : https://www.researchgate.net/;

Захожу на сайт (рис. [-@fig:019]), отмечаю, что я студент (рис. [-@fig:020]), выбираю свой институт и направление (рис. [-@fig:021]), ввожу свои данные и пароль (рис. [-@fig:022]), выбираю свою дисциплину (рис. [-@fig:023]), выбираю то, что я умею (рис. [-@fig:024]) и заканчиваю регистрацию (рис. [-@fig:025]).

![рис. 19](image/Screenshot_19.png){ #fig:019 width=70% }

![рис. 20](image/Screenshot_20.png){ #fig:020 width=70% }

![рис. 21](image/Screenshot_21.png){ #fig:021 width=70% }

![рис. 22](image/Screenshot_22.png){ #fig:022 width=70% }

![рис. 23](image/Screenshot_23.png){ #fig:023 width=70% }

![рис. 24](image/Screenshot_24.png){ #fig:024 width=70% }

![рис. 25](image/Screenshot_25.png){ #fig:025 width=70% }

Academia.edu : https://www.academia.edu/;

Захожу на сайт (рис. [-@fig:026]), вхожу с помощью гугла (рис. [-@fig:027]), выбираю аккаунт гугл (рис. [-@fig:028]), выбираю бесплатную опцию (рис. [-@fig:029]) и создаю аккаунт (рис. [-@fig:030]).

![рис. 26](image/Screenshot_26.png){ #fig:026 width=70% }

![рис. 27](image/Screenshot_27.png){ #fig:027 width=70% }

![рис. 28](image/Screenshot_28.png){ #fig:028 width=70% }

![рис. 29](image/Screenshot_29.png){ #fig:029 width=70% }

![рис. 30](image/Screenshot_30.png){ #fig:030 width=70% }

arXiv : https://arxiv.org/;

Захожу на сайт (рис. [-@fig:031]), ввожу свою почту, логин, пароль (рис. [-@fig:032]), ввожу данные о себе и университете(рис. [-@fig:033]), заканчиваю регистрацию (рис. [-@fig:034]).

![рис. 31](image/Screenshot_31.png){ #fig:031 width=70% }

![рис. 32](image/Screenshot_32.png){ #fig:032 width=70% }

![рис. 33](image/Screenshot_33.png){ #fig:033 width=70% }

![рис. 34](image/Screenshot_34.png){ #fig:034 width=70% }

github : https://github.com/.

Аккаунт гитхаб у меня уже есть (рис. [-@fig:034]).

![рис. 35](image/Screenshot_35.png){ #fig:035 width=70% }

Далее размещаю их ссылки на сайте.

Скачиваю недостающие иконки (рис. [-@fig:036]).

![рис. 36](image/Screenshot_37.png){ #fig:036 width=70% }

Захожу в work/blog/content/authors/admin/_index.md, вставляю ссылки на сайты и меняю названия иконок на скачанные (рис. [-@fig:037]) (рис. [-@fig:038]).

![рис. 37](image/Screenshot_36.png){ #fig:035 width=70% }

![рис. 38](image/Screenshot_38.png){ #fig:035 width=70% }

Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору:

Создание презентаций.

Захожу в work/blog/content/post, создаю 2 новые папки для постов.

Захожу в 3rd week и редактирую index.md (рис. [-@fig:039]), также меняю картинку на новую (рис. [-@fig:040]).

![рис. 39](image/Screenshot_39.png){ #fig:039 width=70% }

![рис. 40](image/Screenshot_40.png){ #fig:040 width=70% }

Далее захожу в папку Создание презентаций и редактирую index.md (рис. [-@fig:041]) и тоже меняю картинку на новую.  (рис. [-@fig:042])

![рис. 41](image/Screenshot_42.png){ #fig:041 width=70% }

![рис. 42](image/Screenshot_41.png){ #fig:042 width=70% }

После всем нам уже знакомые операции. 
Захожу в каталог blog, строю сайт и выгружаю все на гитхаб.  (рис. [-@fig:043]) (рис. [-@fig:044])

![рис. 43](image/Screenshot_43.png){ #fig:043 width=70% }

![рис. 44](image/Screenshot_44.png){ #fig:044 width=70% }

Захожу в public и делаю то же самое.  (рис. [-@fig:045])

![рис. 45](image/Screenshot_45.png){ #fig:045 width=70% }

Такой получился сайт.  (рис. [-@fig:046]) (рис. [-@fig:047])

![рис. 46](image/1.png){ #fig:046 width=70% }

![рис. 47](image/2.png){ #fig:047 width=70% }

# Выводы

В ходе работы я зарегистрировался в большом количестве новых для меня сайтов, загрузил ссылки на них на свой сайт и создал 2 новых поста.

