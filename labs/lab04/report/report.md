---
## Front matter
title: "Отчет по лабораторной работе № 4"
subtitle: "Продвинутое использование git"
author: "Алиса Алексеевна Скобеева"

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

Создать репозиторий и выполнить с ним команды, которые указаны на платформе.

# Выполнение лабораторной работы

Установка git-flow
Устанавливаем git-flow из коллекции репозиториев Copr:

![Выполняем команду](image/1.png){#fig:001 width=70%}

![Выполняем следующую команду](image/2.png){#fig:002 width=70%}

Установка Node.js
Последовательно выполняем команды:

![Ввод команд](image/13.png){#fig:003 width=70%}

Запускаем:

![Выполняем pnpm setup](image/4.png){#fig:004 width=70%}

Общепринятые коммиты
Добавляем коммиты commitizen и standart-changelog

![Установка коммита commitizen](image/6.png){#fig:005 width=70%}

![Установка коммита standart-changelog](image/7.png){#fig:006 width=70%}

Создание репозитория git

Создаем репозиторий git. Называем его git-extended.

![Создаем репозиторий на GitHub](image/8.png){#fig:007 width=70%}

Добавляем какой-нибудь файл, чтобы репозиторий корректно работал. Назовем его TOUCHME. Откроем его, и напишем произвольный текст. После, можем создавать первый коммит.

![Последовательно выполняем все действия](image/10.png){#fig:008 width=70%}

Добавляем коммит:

![Добавление коммита 1](image/11.png){#fig:009 width=70%}

![Добавление коммита 2](image/12.png){#fig:010 width=70%}

Конфигурация общепринятых коммитов
Выполняем команду pnpm init:

![Выполняем команду](image/13.png){#fig:011 width=70%}

Последовательно заполняем файл так, как от нас требуется:

![Редактируем файл](image/14.png){#fig:012 width=70%}

Добавляем новые файлы с помощью git add .
Далее выполняем коммит git cz и отправляем все на GitHub:

![Выполняем команды](image/15.png){#fig:013 width=70%}

![Выполняем git push для отправки на GitHub](image/16.png){#fig:014 width=70%}

Конфигурация git-flow
Инициализируем git-flow с помощью git flow init и выбираем нужные нам параметры:

![Выбор нужных параметров](image/17.png){#fig:015 width=70%}

Проверяем, находимся ли мы на ветке develop и далее загружаем весь репозиторий в хранилище:

![Выполняем команду](image/19.png){#fig:016 width=70%}

Устанавливаем внешнюю ветку как вышестоящую для этой ветки:

![Выполняем команду](image/20.png){#fig:017 width=70%}

Далее, создаем релиз с версией 1.0.0, создаем журнал изменений и добавляем его в индекс:

![Выполняем команды](image/23.png){#fig:018 width=70%}

Заливаем релизную ветку в основную фетку и отправляем данные на github. Далее создаем релиз на github. Для этого используем утилиты работы с github:

![Выполняем команду](image/24.png){#fig:019 width=70%}

![Выполняем команду](image/25.png){#fig:020 width=70%}

![Выполняем команду](image/26.png){#fig:021 width=70%}

![Выполняем команду](image/27.png){#fig:022 width=70%}

![Выполняем команду](image/28.png){#fig:023 width=70%}

Работа с репозиторием git.
Разработка новой функциональности
Создаем ветку для новой функциональности, далее, продолжаем работу с git как обычно, и по окончании объединяем ветку feature_branch с develop:

![Выполняем команду](image/29.png){#fig:024 width=70%}

![Выполняем команду](image/30.png){#fig:025 width=70%}

Создание релиза git-flow
Создаем релиз с версией 1.2.3. Обновляем номер версии в файле package.json. Далее, создаем журнал изменений и добавляем его в индекс. Далее, заливаем релизную ветку в основную ветку и отправляем данные на GitHub. Создаем релиз на github c комментарием из журнала изменений: 

![Последовательно выполняем все команды 1](image/31.png){#fig:026 width=70%}

![Последовательно выполняем все команды 2](image/32.png){#fig:027 width=70%}

![Последовательно выполняем все команды 3](image/33.png){#fig:028 width=70%}

![Последовательно выполняем все команды 4](image/34.png){#fig:029 width=70%}

![Последовательно выполняем все команды 5](image/35.png){#fig:030 width=70%}

![Последовательно выполняем все команды 6](image/36.png){#fig:031 width=70%}

![Последовательно выполняем все команды 7](image/37.png){#fig:032 width=70%}


# Выводы

В ходе выполнения лабораторной работы мы приобрели навыки продвинутого использования git.


