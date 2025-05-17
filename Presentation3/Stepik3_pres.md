---
## Front matter
title: "Отчёт по прохождению внешнего курса №3"
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
---



# Задание

![image-20250517170305508](./images/image-20250517170305508.png)

Правильный ответ - последний

![image-20250517170324883](./images/image-20250517170324883.png)

Хэш-функция должна быть быстрой, иметь одинаковую длину выхода и быть максимально стойкой к коллизиям

![image-20250517170414541](./images/image-20250517170414541.png)

AES и SHA2 - хэш-функции, а не алгоритмы цифровой подписи

![image-20250517170441465](./images/image-20250517170441465.png)

Код аутентификации сообщения является симметричным примитивом

![image-20250517170507097](./images/image-20250517170507097.png)

Правильный ответ - асимметричный примитив генерации общего секретного ключа

![image-20250517170525868](./images/image-20250517170525868.png)

Для проверки подписи используется открытый ключ

![image-20250517170547339](./images/image-20250517170547339.png)

Необходимы подпись, открытый ключ и само сообщение

![image-20250517170612821](./images/image-20250517170612821.png)

Конфиденциальность не обеспечивается цифровой подписью

![image-20250517170638494](./images/image-20250517170638494.png)

Для подачи налоговой отчётности необходима усиленная квалифицированная подпись

![image-20250517170705997](./images/image-20250517170705997.png)

Такую подпись можно получить в специальном удостоверяющем центре

![image-20250517170729666](./images/image-20250517170729666.png)

Платёжная система - система, обеспечивающая передачу данных между разными участниками платежа

![image-20250517170805331](./images/image-20250517170805331.png)

Многофакторная аутентификация - аутентификация, использующая несколько РАЗЛИЧНЫХ факторов

![image-20250517170840184](./images/image-20250517170840184.png)

При онлайн платеже вы подтверждаете личность банку, выпустившему вашу карту (эмитенту)

![image-20250517170921085](./images/image-20250517170921085.png)

Proof-of-work требует высокую сложность нахождения прообраза

![image-20250517170955643](./images/image-20250517170955643.png)

Он обладает всеми свойствами

![image-20250517171017152](./images/image-20250517171017152.png)

Цифровая подпись необходима для проверки
