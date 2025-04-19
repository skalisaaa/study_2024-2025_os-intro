---
## Front matter
title: "Отчет по прохождению внешнего курса"
subtitle: "Часть 3. Продвинутые темы"
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

Выполнить все задания 3-го раздела курса.


# Прохождение внешнего курса

1. Текстовый редактор vim

![Для выхода необходимо использовать эту комбинацию](image/1.png){#fig:001 width=70%}

![Выбранные утверждения верны](image/2.png){#fig:002 width=70%}

![Выбранные варианты ответов верны](image/3.png){#fig:003 width=70%}

![Вводим команду](image/4.png){#fig:004 width=70%}

![Верные утверждения](image/5.png){#fig:005 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились пользоваться текстовым редактором vim. 

2. Скрипты на bash: основы

![Ответ верный](image/6.png){#fig:006 width=70%}

![Абсолютный путь будет выглядеть следующим образом](image/7.png){#fig:007 width=70%}

![Данные строки могут быть именами переменных в bash](image/8.png){#fig:008 width=70%}

![Пишем скрипт, который принимает на вход два аргумента и выводит на экран строку требуемого вида](image/9.png){#fig:009 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились писать небольшие скрипты и запускать их. 

3. Скрипты на bash: ветвления и циклы

![Выбранные ответы верны](image/10.png){#fig:010 width=70%}

![Сначала будет выведен four, и затем снова four](image/11.png){#fig:011 width=70%}

![Пишем скрипт, который принимает на вход один аргумент, который будет обозначать число студентов в аудитории. В зависимости от числа выводятся разные сообщения](image/12.png){#fig:012 width=70%}

![При запуске данного скрипта выведется 5 раз "start" и 4 раза "finish"](image/13.png){#fig:013 width=70%}

![Пишем скрипт, который определяет, в какую возрастную группу попадают пользователи](image/14.png){#fig:014 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились использовать управляющие конструкции языка bash, которые позволяют писать скрипты, где часть инструкций выполняется только при опр. условиях(ветвления), а часть инструкций выполняется по много раз подряд(циклы).

4. Скрипты на bash: разное

![Ответ верный](image/15.png){#fig:015 width=70%}

![Будет выведено /home/bi](image/16.png){#fig:016 width=70%}

![Выбор всех верных утверждений](image/17.png){#fig:017 width=70%}

![Вводим строку, которая будет выведена](image/18.png){#fig:018 width=70%}

![Пишем скрипт, который будет искать НОД двух чисел](image/19.png){#fig:019 width=70%}

![Пишем калькулятор на bash](image/20.png){#fig:020 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились писать довольно сложные и полезные скрипты на bash. Также мы изучили несколько тем: арифметические операции, запуск внешних программ и обработка результатов их работы; понятие функций в языке bash и их использование.

5. Продвинутый поиск и редактирование

![Правильный ответ](image/21.png){#fig:021 width=70%}

![Верные утверждения](image/22.png){#fig:022 width=70%}

![Все кроме file3](image/23.png){#fig:023 width=70%}

![Верный ответ](image/24.png){#fig:024 width=70%}

![Все выбранные варианты ответов верны](image/25.png){#fig:025 width=70%}

![Произойдет следующее](image/26.png){#fig:026 width=70%}

![Введенная инструкция sed верна](image/27.png){#fig:027 width=70%}

Изучив материалы данного раздела и выполнив все задания мы научились работать с потоковым текстовым редактором sed, который позволяет не только искать слова в файлах, но и сразу же эти файлы редактировать.

6. Строим графики в gnuplot

![Ответ верный](image/28.png){#fig:028 width=70%}

![Верный ответ](image/29.png){#fig:029 width=70%}

![Команда написана абсолютно верно](image/30.png){#fig:030 width=70%}

![Файл изменен абсолютно верно](image/31.png){#fig:031 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы научились использовать базовые команды gnuplot для работы в интерактивном режиме, а также научились писать gnuplot-скрипты.

7. Разное

![Правильный ответ](image/32.png){#fig:032 width=70%}

![Правильный ответ](image/33.png){#fig:033 width=70%}

![Верные утверждения](image/34.png){#fig:034 width=70%}

![Команда верна](image/35.png){#fig:035 width=70%}

![Верный ответ](image/36.png){#fig:036 width=70%}

Изучив материалы данного раздела и выполнив все практические задания мы узнали много нового об еще нескольких важных темах.


# Выводы

После изучения всех текстовых и видеоматериалов 3-ой части курса, а также успешного выполнения всех практических заданий, мы приобрели и закрепили навыки работы в продвинутых темах, таких как написание программ.


