---
## Front matter
title: "Лабораторная работа №5"
subtitle: "Настройка рабочей среды"
author: "Толстых Александра НММбд-03-24"

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

Настройка рабочей среды.

# Задание

- Менеджер паролей pass.
- Управление файлами конфигурации.
- Дополнительное программное обеспечение.

# Теоретическое введение                                                        

Более подробно про Unix см. в [@tanenbaum_book_modern-os_ru; @robbins_book_bash_en; @zarrelli_book_mastering-bash_en; @newham_book_learning-bash_en].

# Выполнение лабораторной работы

Все необходимые пакеты у меня уже были установлены, поэтому данный шаг я пропускаю. Просматриваю список ключей (рис. [-@fig:001]).

![Список ключей](image/1.jpg){#fig:001 width=70%}

Инициализирую хранилище (рис. [-@fig:002]).

![Инициализация](image/2.jpg){#fig:002 width=70%}

Создаю структуру гит (рис. [-@fig:003]).

![Создание структуры](image/3.jpg){#fig:003 width=70%}

Устанавливаю необходимый плагин (рис. [-@fig:004]).

![Установка плагина](image/4.jpg){#fig:004 width=70%}

Устанавливаю дополнительное программное обеспечение (рис. [-@fig:005]).

![Установка ПО](image/5.jpg){#fig:005 width=70%}

Устанавливаю необходимые шрифты (рис. [-@fig:006]).

![Установка шрифтов](image/6.jpg){#fig:006 width=70%}

Устанавливаю бинарный файл (рис. [-@fig:007]).

![Установка бинарного файла](image/7.jpg){#fig:007 width=70%}

Создаю репозиторий для конфигурационных файлов. Проверяю и сохраняю изменения (рис. [-@fig:008]).

![Работа с репозиторием](image/8.jpg){#fig:008 width=70%}

# Выводы

В ходе лабораторной работы я выполнила настройку рабочей среды.

# Список литературы{.unnumbered}

::: {#refs}
:::
