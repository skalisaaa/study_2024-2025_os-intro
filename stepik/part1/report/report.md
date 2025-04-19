---
## Front matter
title: "Отчет по прохождению внешнего курса"
subtitle: "Часть 1. Введение"
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

Выполнить все задания 1-го раздела курса.


# Выполнение лабораторной работы

1. Общая информация о курсе

![Ответ верный](image/1.png){#fig:001 width=70%}

![Ответ верный](image/2.png){#fig:002 width=70%}

2. Как установить Linux 

![Выбор используемой ОС](image/3.png){#fig:003 width=70%}

![Определение ВМ](image/4.png){#fig:004 width=70%}

![Ввод ответа](image/5.png){#fig:005 width=70%}

Изучив материалы данного раздела мы узнали, как установить Linux.

3. Осваиваем Linux

![Файл соответствует требованиям задачи](image/6.png){#fig:006 width=70%}

![Расширения deb](image/7.png){#fig:007 width=70%}

![Выполняем задание и вводим получившийся результат](image/8.png){#fig:008 width=70%}

![Update Manager спользуется для следующих действий](image/9.png){#fig:009 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились просматривать, создавать и удалять файлы и папки через файловый менеджер. 

4. Terminal: основы

![Ассоль и термин не являются синонимами](image/10.png){#fig:010 width=70%}

![pwd печатает текущую директорию](image/11.png){#fig:011 width=70%}

![Выбор эквивалентных программ](image/12.png){#fig:012 width=70%}

![Данные команды выводят содержимое, не показывая содержимое других директорий](image/13.png){#fig:013 width=70%}

![С помощью rm -r удаляем директории](image/14.png){#fig:014 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились запускать Терминал и изучили несколько базовых команд для работы в нем.

5. Запуск исполняемых файлов

![Ответ верный](image/15.png){#fig:015 width=70%}

![Остальные варианты не эквивалентны запуску с &](image/16.png){#fig:016 width=70%}

![После запуска файла получили следующий вывод](image/17.png){#fig:017 width=70%}

Изучив материалы данного раздела и выполнив все задания мы научились запускать программы из командной строки.

6. Ввод/вывод

![Правильный ответ](image/18.png){#fig:018 width=70%}

![Данная команда соответствует требованию задачи](image/19.png){#fig:019 width=70%}

![Ошибки выводятся на экран](image/20.png){#fig:020 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились передавать приложению входные данные из файла и записывать результаты выполнения и возникшие ошибки в файл или несколько файлов.

7. Скачивание файлов из интернета

![Верный ответ](image/21.png){#fig:021 width=70%}

![Опция -q или quiet](image/22.png){#fig:022 width=70%}

![Верный ответ](image/23.png){#fig:023 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились скачивать файлы из интернета с помощью команды wget.

8. Работа с архивами

![Выбираем отличие между qzip и zip](image/24.png){#fig:024 width=70%}

![tar и zip создают архив из директории с файлами](image/25.png){#fig:025 width=70%}

![Верный ответ](image/26.png){#fig:026 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились работать с несколькими архиваторами в терминале: создание и распаковка архивов.

9. Поиск файлов и слов в файлах

![Верный ответ](image/27.png){#fig:027 width=70%}

![Выбранные строки будут выведены на экран](image/28.png){#fig:028 width=70%}

![Результат работы программы верный](image/29.png){#fig:029 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научичились использовать инструменты для поиска данных. 

# Выводы

После изучения всех текстовых и видеоматериалов 1-ой части курса, а также успешного выполнения всех практических заданий, мы приобрели и закрепили базовые навыки работы с Linux.


