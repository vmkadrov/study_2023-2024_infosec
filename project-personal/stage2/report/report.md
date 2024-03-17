---
## Front matter
title: "Индивидуальный проект. Этап №2"
subtitle: "Установка DVWA"
author: "Кадров Виктор Максимович"

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
lot: false # List of tables
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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

Установить уязвимый веб-сервер DVWA.

# Задание

1. Установка приложения
2. Тестирование уязвимостей

# Выполнение лабораторной работы

## Установка приложения

Заходим на github, скачиваем себе установочный скрипт и выполняем его. В итоге на виртуальную машину устанавливается уязвимый веб-сервер (рис. [-@fig:001]).

![DVWA](image/pr-02-01.png){ #fig:001 width=100% }

## Тестирование уязвимостей

Ищем веб-уязвимости (рис. [-@fig:002]).

![Command injection](image/pr-02-02.png){ #fig:002 width=100% }

# Выводы

В ходе лабораторной работы был установлен уязвимый веб-сервер DVWA.