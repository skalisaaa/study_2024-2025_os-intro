---
## Front matter
title: "Отчет по прохождению внешнего курса"
subtitle: "Часть 2. Работа на сервере"
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

Пройти внешний курс для получения и закрепления навыков работы с операционными системами Linux.

# Задание

Выполнить все задания 2-го раздела курса.


# Выполнение лабораторной работы

1. Знакомство с сервером 

![Ответ верный](image/1.png){#fig:001 width=70%}

![Без опаски можно пересылать только ключ id_rsa.pub](image/2.png){#fig:002 width=70%}

2. Обмен файлами

![Остальные команды сработают иначе](image/3.png){#fig:003 width=70%}

![Выбранные действия устранят возникшую проблему](image/4.png){#fig:004 width=70%}

![Программа Filezila используется для следующих действий](image/5.png){#fig:005 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились обмениваться файлами в обе стороны, а также рассмотрели два способа обмена файлами: используя терминал и Filezila.

3. Запуск приложений

![Выбор необходимых действий](image/6.png){#fig:006 width=70%}

![Вызов справочной информации о program](image/7.png){#fig:007 width=70%}

![Данные форматы данных FastQC принимает на вход](image/8.png){#fig:008 width=70%}

![Данная команда запускает в терминале Clustal и выполняет множественное выравнивание](image/9.png){#fig:009 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились запускать приложения на сервере. 

4. Контроль запускаемых программ

![При выполнении jobs будет показана информация о program2 и program3](image/10.png){#fig:010 width=70%}

![Идентификаторы одинаковые только у ps и top](image/11.png){#fig:011 width=70%}

![kill -9 мгновенно завершает остановленный процесс](image/12.png){#fig:012 width=70%}

![Выбранный ответ верный](image/13.png){#fig:013 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научимся следить за своими и чужими приложениями, запускать их в фоновом и основном режимах и отменять некоторые из запусков в случае необходимости.

5. Многопоточные приложения 

![Использует 0% CPU](image/14.png){#fig:014 width=70%}


![Остановленное многопоточное приложение занимает столько памяти, сколько оно потребляло в момент остановки](image/15.png){#fig:015 width=70%}

![Принудительно завершить никак нельзя](image/16.png){#fig:016 width=70%}

![Ответ верный](image/17.png){#fig:017 width=70%}

![Вывод программы верный](image/18.png){#fig:018 width=70%}

Изучив материалы данного раздела и выполнив все задания мы научились работать с потоками и процессами, без которых практически невозможно представить обработку больших объемов данных.

6. Менеджер терминалов tmux

![Ответ верный](image/19.png){#fig:019 width=70%}

![В таком случае tmux завершит работу](image/20.png){#fig:020 width=70%}

![Верный ответ](image/21.png){#fig:021 width=70%}

![Произойдет следующее](image/22.png){#fig:022 width=70%}

![Данная команда отвечает за переименование текущей вкладки](image/23.png){#fig:023 width=70%}

![Выбираем все верные варианты](image/24.png){#fig:024 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились работать с менеджером терминалов tmux. 


# Выводы

После изучения всех текстовых и видеоматериалов 2-ой части курса, а также успешного выполнения всех практических заданий, мы закрепили навыки работы на сервере в ОС Linux.


