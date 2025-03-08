---
## Front matter
title: "Лабораторная работа № 1"
subtitle: "Установка линукс"
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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Задание

- Создание виртуальной машины
- Настройка машины
- Установка дистрибутивов для работы с markdown

# Выполнение лабораторной работы

Виртуальная машина у меня уже была установлена, поэтому я лишь создаю новую (рис. [-@fig:001]).

![Создание машины](image/1.jpeg){#fig:001 width=70%}

При запуске я следую указаниям и с помошью anakonda завершаю установку (рис. [-@fig:002]).

![Завершение установки](image/2.jpeg){#fig:002 width=70%}

Открываю терминал, вхожу в учетную запись и выполняю установку необходимых пакетов (рис. [-@fig:003]).

![Установка необходимых пакетов](image/3.jpeg){#fig:003 width=70%}

Проверяю, что имя пользователя и прочее были корректно заданы во время создания машины (рис. [-@fig:004]).

![Проверка](image/4.jpeg){#fig:004 width=70%}

Далее я устанавливаю pandoc (рис. [-@fig:005]).

![Установка](image/5.jpeg){#fig:005 width=70%}

Затем устанавливаю дистрибутив TeXlive (рис. [-@fig:006]).

![Установка](image/6.jpeg){#fig:006 width=70%}

# Выводы

В результате выполнения данной работы я приобрела практические навыки установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Список литературы{.unnumbered}

::: {#refs}
:::
