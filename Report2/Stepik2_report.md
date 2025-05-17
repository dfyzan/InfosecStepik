---
## Front matter
title: "Отчёт по прохождению внешнего курса №2"
subtitle: "Основы Кибербезопасности"
author: "Авилов Иван Олегович"

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
typora-copy-images-to: ./images
---



# Задание

![image-20250517165411621](./images/image-20250517165411621.png)

Да, зашифровать загрузочный сектор возможно

![image-20250517165432963](./images/image-20250517165432963.png)

Правильный ответ - симметричное шифрование

![image-20250517165456005](./images/image-20250517165456005.png)

Wireshark - программа для перехвата пакетов, Disk Utility - утилита для просмотра информации про диск

![image-20250517165600319](./images/image-20250517165600319.png)

Стойкий пароль должен содержать буквы верхнего и нижнего регистра, цифры и спец символы

![image-20250517165706839](./images/image-20250517165706839.png)

В остальных вариантах пароль легко может быть украден

![image-20250517165727466](./images/image-20250517165727466.png)

Капча помогает отличить человека от бота

![image-20250517165746178](./images/image-20250517165746178.png)

На сервере хранятся хэши паролей

![image-20250517165805668](./images/image-20250517165805668.png)

Соль не поможет, если получен доступ к самому серверу

![image-20250517165838189](./images/image-20250517165838189.png)

Все эти меры по разному помогают защититься от утечки атакой перебором

![image-20250517165922995](./images/image-20250517165922995.png)

Выбранные ссылки являются фишинговыми, то есть мимикрирующими под легитимные

![image-20250517165959722](./images/image-20250517165959722.png)

Может, если почта была взломана или адрес подменён

![image-20250517170022456](./images/image-20250517170022456.png)

Спуфинг - подмена

![image-20250517170038156](./images/image-20250517170038156.png)

Троян несёт своё название от троянского коня

![image-20250517170102820](./images/image-20250517170102820.png)

Ключ формируется для одной беседы

![image-20250517170119541](./images/image-20250517170119541.png)

Название идёт от того, что сообщения передаются в зашифрованном виде "насквозь"
