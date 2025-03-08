---
## Front matter
title: "Лабораторная работа № 4"
subtitle: "ОПродвинутое использование git"
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

Получение навыков правильной работы с репозиториями git.

# Задание

- Выполнить работу для тестового репозитория.
- Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

# Выполнение лабораторной работы

Создаю репозиторий на GitHub (рис. [-@fig:001]).

![Создание репозитория](image/1.jpeg){#fig:001 width=70%}

Создаю копию репозитория у себя на ноутбуке (рис. [-@fig:002]).

![Копирование репозитория](image/2.jpeg){#fig:002 width=70%}

Настраиваю коммиты (рис. [-@fig:003]).

![Выполнение настроек](image/3.jpeg){#fig:003 width=70%}

Изменяю файл package.json (рис. [-@fig:004]).

![Изменение файла](image/4.jpeg){#fig:004 width=70%}

Инициализирую git-flow (рис. [-@fig:005]).

![Работа с git-flow](image/5.jpeg){#fig:005 width=70%}

Загружаю репозиторий в хранилище (рис. [-@fig:006]).

![Загрузка репозитория](image/6.jpeg){#fig:006 width=70%}

Работаю с релизом 1.0.0 (рис. [-@fig:007]).

![Работа с релизом](image/7.jpeg){#fig:007 width=70%}

Сохраняю релиз 1.0.0 (рис. [-@fig:008]).

![Сохранение релиза](image/8.jpeg){#fig:008 width=70%}

Переключаюсь на ветку для нового релиза (рис. [-@fig:009]).

![Смена ветки](image/9.jpeg){#fig:009 width=70%}

Работаю с релизом 1.2.3 (рис. [-@fig:010]).

![Работа с релизом](image/10.jpeg){#fig:010 width=70%}

Завершаю работу с релизом и сохраняю его (рис. [-@fig:011]).

![Сохранение релиза](image/11.jpeg){#fig:011 width=70%}

# Выводы

В ходе выполнения работы были приобретены навыки правильной работы с репозиториями git.

# Список литературы{.unnumbered}

::: {#refs}
:::
