---
## Front matter
title: "Отчёт по прохождению внешнего курса №1"
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
typora-copy-images-to: ./image
---



# Задание

![image-20250517175910963](./image/image-20250517175910963.png)

Только HTTPS является протоколом прикладного уровня

![image-20250517175919316](./image/image-20250517175919316.png)

TCP является протоколом транспортного уровня

![image-20250517175928806](./image/image-20250517175928806.png)

Адреса, в которых есть числа больше 255 - некорректны

![image-20250517175936875](./image/image-20250517175936875.png)

DNS сервера действительно сопоставляют доменное имя с его IP адресом

![image-20250517175949182](./image/image-20250517175949182.png)

В верной последовательности протоколы отсортированы от верхнего к нижнему

![image-20250517180000074](./image/image-20250517180000074.png)

http, в отличии от https не предполагает шифрования

![image-20250517180008686](./image/image-20250517180008686.png)

Правильный ответ - 2 фазы, рукопожатие и передача данных

![image-20250517180019831](./image/image-20250517180019831.png)

Если у какой-то стороны нету поддержки определённой версии, они договариваются использовать прошлую версию, которая есть у обоих сторон.

![image-20250517180029642](./image/image-20250517180029642.png)

Фаза рукопожатия предполагает лишь обмен информацией о способах шифрования: ключах, алгоритмах и т.д. Шифрование данных не выполняется

![image-20250517180036630](./image/image-20250517180036630.png)

Куки файлы позволяют идентифицировать пользователя, не открывая его персональные данные

![image-20250517180044495](./image/image-20250517180044495.png)

Надёжность соединения - не зона ответственности владельца сайта

![image-20250517180055068](./image/image-20250517180055068.png)

Куки файлы используются и генерируются сервером

![image-20250517180101958](./image/image-20250517180101958.png)

Куки файлы хранятся в браузере на время пользования сайтом

![image-20250517180112106](./image/image-20250517180112106.png)

Промежуточных узлов в сети ТОР - 3

![image-20250517180120800](./image/image-20250517180120800.png)

Отправитель должен знать адрес получателя, иначе он не сможет передать его выходному узлу. Выходной узел должен знать адрес получателя, иначе он не будет знать, куда направить пакеты.

![image-20250517180129818](./image/image-20250517180129818.png)

Каждый узел знает только свой ключ, которым узел снимает один слой "луковицы"

![image-20250517180137882](./image/image-20250517180137882.png)

Нет, так как выходной узел играет роль виртуального пользователя.

![image-20250517180144852](./image/image-20250517180144852.png)

Wi-Fi -  технология беспроводной передачи данных в локальной сети

![image-20250517180150986](./image/image-20250517180150986.png)

Wi-fi работает на канальном уровне

![image-20250517180157417](./image/image-20250517180157417.png)

Самый уязвимый метод - WEP

![image-20250517180203659](./image/image-20250517180203659.png)

Шифрование начинается после аутентификации устройств

![image-20250517180210024](./image/image-20250517180210024.png)

Personal - для личного пользования. Enterprise - для бизнеса
