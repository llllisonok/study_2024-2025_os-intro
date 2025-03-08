---
## Front matter
title: "Лабораторная работа № 3"
subtitle: "Основы работы с markdown"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

Написать отчет ко второй лабораторной.

# Выполнение лабораторной работы

Для своего комфорта, пишу текст отчета себе в сообщениях, чтобы затем его просто скопировать (рис. [-@fig:001]).

![Подготовленный текст](image/1.jpeg){#fig:001 width=70%}

Открываю в удобной мне системе markdown файл (рис. [-@fig:002]).

![Markdown файл](image/2.jpeg){#fig:002 width=70%}

Вношу в него написанный текст, включая картинки и прочий текст (рис. [-@fig:003]).

![Markdown файл](image/3.jpeg){#fig:003 width=70%}

Использую команду make для компиляции отчета (рис. [-@fig:004]).

![Компиляция отчета](image/4.jpeg){#fig:004 width=70%}

Сохраняю изменения на гитхаб (рис. [-@fig:005]).

![Сохранение изменений](image/5.jpeg){#fig:005 width=70%}

# Выводы

В ходе выполнения лабораторной работы я научилась оформлять отчёты с помощью легковесного языка разметки Markdown

# Список литературы{.unnumbered}

::: {#refs}
:::
