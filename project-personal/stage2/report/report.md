---
## Front matter
title: "Отчет по проекту Этап 2"
subtitle: ""
author: "Татур Стефан"

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

# Выполнение лабораторной работы

1. Для размещения фотографии заходим в “authors” -> “admin” и добавляем
фотографию. 

![Название рисунка](image/pic1.png)

2. Добавим краткое описание владельца сайта, информацию о интересах, об-
разовании. 

![Название рисунка](image/pic2.png)

3. Далее добавим пост недели и пост по выбору. Переходим в папку “contents”
-> “post” и добавляем необходимую информацию. 

![Название рисунка](image/pic3.png)

4. Выгружаем всё на сайт, используя знакомые команды и не забываем делать
это и из “public”. Проверяем сайт.

![Название рисунка](image/pic4.png)

5. Сайт преобразился.


![Название рисунка](image/pic5.png)

# Выводы

В ходе выполнения данной работы я получила основы создания сайта, а так же
научилась изменять инфомрацию о себе и писать посты.


::: {#refs}
:::
