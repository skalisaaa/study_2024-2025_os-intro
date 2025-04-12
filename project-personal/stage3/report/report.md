---
## Front matter
title: "Индивидуальный проект. Часть 3"
subtitle: "Отчет о выполнении"
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

Создать персональный часть научного работника.

# Задание

Добавить информацию о хобби, навыках, достижениях и написать две статьи.

# Выполнение индивидуального проекта

В файле index.md добавляем информацию о хобби, навыках и достижениях.

![Пишем о своих навыках](image/1.png){#fig:001 width=70%}

![Пишем о своих достижениях](image/2.png){#fig:002 width=70%}

Проверяем добавленные изменения на сайте с помощью hugo server.

![Все отображено корректно](image/3.png){#fig:003 width=70%}

![Навыки также отображены корректно](image/4.png){#fig:004 width=70%}

![Достижения отображены корректно](image/5.png){#fig:005 width=70%}

Пишем две статьи: про прошедшую неделю и про язык разметки Markdown.

![Пишем статью про Markdown](image/6.png){#fig:006 width=70%}

![Пишем статью про прошедшую неделю](image/7.png){#fig:007 width=70%}

Проверяем, добавились ли наши статьи на сайт.

![Статья отображена корректно](image/8.png){#fig:008 width=70%}

![Вторая статья также отображена корректно](image/9.png){#fig:009 width=70%}

# Выводы

Мы успешно выполнили 3 этап проекта и добавили нужные изменения на наш сайт.
