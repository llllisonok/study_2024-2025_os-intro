---
## Front matter
title: "Индивидуальный проект"
subtitle: "Часть 2"
author: "Толстых Александра Андреевна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Внести информацию о себе на сайт и создать два поста.

# Задание

- Добавить данные о себе
- Создать пост о прошедшей неделе
- Создать пост на тему "Управление версиями. Git."

# Теоретическое введение

Более подробно про Unix см. в [@tanenbaum_book_modern-os_ru; @robbins_book_bash_en; @zarrelli_book_mastering-bash_en; @newham_book_learning-bash_en].

# Выполнение лабораторной работы

Редактирую файл index.md, внося следующие данные:

1. Имя и статус (рис. [-@fig:001]).

![Изменение статуса и имени](image/1.jpg){#fig:001 width=70%}

2. Место работы (рис. [-@fig:002]).

![Изменение работы](image/2.jpg){#fig:002 width=70%}

3. Социальные сети (рис. [-@fig:003]).

![Добавление ссылок](image/3.jpg){#fig:003 width=70%}

4. Биография (рис. [-@fig:004]).

![Добавление биографии](image/4.jpg){#fig:004 width=70%}

Меняю аватар (рис. [-@fig:005]).

![Смена аватара](image/5.jpg){#fig:005 width=70%}

Меняю адрес сайта (рис. [-@fig:006]).

![Смена адреса сайта](image/6.jpg){#fig:006 width=70%}

Создаю папку для нового поста (рис. [-@fig:007]).

![Создание папки](image/7.jpg){#fig:007 width=70%}

Пишу пост о прошедшей неделе (рис. [-@fig:008]).

![Написание поста](image/8.jpg){#fig:008 width=70%}

Создаю папку для нового поста (рис. [-@fig:009]).

![Создание папки](image/9.jpg){#fig:009 width=70%}

Пишу пост о git (рис. [-@fig:010]).

![Написание поста](image/10.jpg){#fig:010 width=70%}

Сохраняю изменения на гитхабе (рис. [-@fig:011]).

![Сохранение изменений](image/11.jpg){#fig:011 width=70%}


# Выводы

В результате выполнения лабораторной работы я добавила на сайт информацию о себе и два поста - о прошедшей неделе и о git-е.

# Список литературы{.unnumbered}

::: {#refs}
:::
