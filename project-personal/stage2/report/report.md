---
## Front matter
title: "Отчёт по выполнению индивидуального проекта"
subtitle: "Часть 2"
author: "Скобеева Алиса Алексеевна"

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

Создать персональный сайт научного сотрудника.

# Задание

Добавить в наш сайт личную информацию, фотографию, навыки и написать две статьи.


# Выполнение лабораторной работы

1. Добавляем информацию о себе. 

Пишем ФИО и образование.

![Пишем информацию о себе](image/1.png){#fig:001 width=70%}

Добавляем информацию о хобби и навыках. Также пишем биографию.

![Заполнение сайта информацией](image/2.png){#fig:002 width=70%}

2. Написание 2-ух статей

Пишем статью о прошедшей неделе.

![Рассказываем о том, как прошла неделя](image/3.png){#fig:003 width=70%}

Пишем статью про Git.

![Написание статьи](image/4.png){#fig:004 width=70%}

3. Отправляем файлы и открываем сайт

Открываем наш сайт и проверяем, что получилось.

![Информация об авторе изображена корректно](image/5.png){#fig:005 width=70%}

Проверяем статьи.

![Все на месте](image/6.png){#fig:006 width=70%}


# Выводы

Мы добавили информацию о себе и написали две статьи на нашем персональном сайте.


