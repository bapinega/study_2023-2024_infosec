## Front matter
title: "Индивидуальный проект этап 4"
subtitle: "Основы информационной безопасности"
author: "Пинега Белла Александровна"

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

Научиться основным способам тестирования веб приложений

# Задание
nikto — базовый сканер безопасности веб-сервера. Он сканирует и обнаруживает уязвимости в веб-приложениях, обычно вызванные неправильной конфигурацией на самом сервере, файлами, установленными по умолчанию, и небезопасными файлами, а также устаревшими серверными приложениями.

# Теоретическое введение
Ищутся уязвимости в специально предназначенном для этого веб приложении под названием Damn Vulnerable Web Application (DVWA).
    Назначение DVWA — попрактиковаться в некоторых самых распространённых веб уязвимостях.
    Предлагается попробовать и обнаружить так много уязвимостей, как сможете.


# Выполнение лабораторной работы
1. Установлю nikto
![рис 1](image/1.png){#fig:001 width=70%}
2. Познакомлюсь с nikto
![рис 2](image/02.png){#fig:002 width=70%}
3. Выполню сканирование SSL и порта 443
![рис 3](image/3.png){#fig:003 width=70%}
4. Сканирую ip-адрес
![рис 4](image/04.png){#fig:004 width=70%}
![рис 5](image/5.png){#fig:005 width=70%}
5. Чтобы отправить все хосты в nikto и увидеть все ip-адреса проделаем следующее:
![рис 6](image/6.png){#fig:006 width=70%}
![рис 7](image/7.png){#fig:007 width=70%}
![рис 8](image/8.png){#fig:008 width=70%}

# Выводы
Я познакомилась с nikto

# Список литературы{.unnumbered}

::: {#refs}
:::
