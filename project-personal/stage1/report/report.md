---
## Front matter
title: "Индивидуальный проект. Этап №1"
subtitle: "Установка Kali Linux"
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

Научиться основным способам тестирования веб-приложений.

# Задание

1. Скачивание дистрибутива
2. Установка системы
3. Проверка возможностей

# Выполнение лабораторной работы

## Скачивание дистрибутива

Заходим на официальный сайт и скачиваем установочный образ (рис. [-@fig:001]).

![Официальный сайт](image/pr-01-01.png){ #fig:001 width=100% }

## Установка системы

Устанавливаем систему на виртуальный диск (рис. [-@fig:002]).

![Установка системы](image/pr-01-02.png){ #fig:002 width=100% }


## Проверка возможностей

Запускаем систему (рис. [-@fig:003]).

![Интерфейс системы](image/pr-01-03.png){ #fig:003 width=100% }

# Выводы

В ходе лабораторной работы была установлена Kali Linux.