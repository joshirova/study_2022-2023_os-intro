---
## Front matter
title: "Индивидуальный проект. 3 этап."
subtitle: "Дисциплина - Операционные системы"
author: "Оширова Юлия Николаевна, НКАбд-02-22"

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

Продолжить редактирование личного сайта. Добавить к сайту достижения.

# Задание

1. Добавить информацию о навыках (Skills).

2. Добавить информацию об опыте (Experience).

3. Добавить информацию о достижениях (Accomplishments).

4. Сделать пост по прошедшей неделе.

5. Добавить пост на тему по выбору:

• Легковесные языки разметки.

• Языки разметки. LaTeX.

• Язык разметки Markdown.

# Теоретическое введение

Сайт – это совокупность веб-страниц, объединённых под общим доменом и связанных ссылками, тематикой и дизайнерским оформлением [1] . Мы создали статический сайт с помощью Hugo. Hugo — генератор статических страниц для интернета.

В этом этапе проекта мы научимся добавлять на сайт наши достижения. А также я напишу пост про язык разметки LaTex.

Язык разметки (markup language) – средство описания данных и метаданных, хранящихся в документе.

# Выполнение лабораторной работы

1. Добавить информацию о навыках (Skills).

![Изменение в файле информации о навыках](image/s1){#fig:001 width=70%}

![Результат на сайте](image/s2){#fig:002 width=70%}

2. Добавить информацию об опыте (Experience).

![Изменение в файле информации об опыте](image/s3){#fig:003 width=70%}

![Результат на сайте](image/s4){#fig:004 width=70%}

3. Добавить информацию о достижениях (Accomplishments).

![Изменение в файле информации о достижениях](image/s5){#fig:005 width=70%}

![Результат на сайте](image/s6){#fig:006 width=70%}

4. Сделать пост по прошедшей неделе.

![Написание поста по прошедшей неделе](image/s7){#fig:007 width=70%}

![Пост на сайте](image/s8){#fig:006 width=70%}

5. Добавим пост на тему “Языки разметки. Markdown.”

![Написание поста по теме "Языки разметки. Маркдаун."](image/s9){#fig:009 width=70%}

![Пост на сайте](image/s10){#fig:010 width=70%}

# Выводы

В процессе выполнения третьего этапа индивидуального проекта я продолжила редактирование сайта, научилась добавлять на сайт свои достижения, а также продолжила писать посты.

# Список литературы{.unnumbered}

[1. Что такое сайт (простыми словами) [Электронный ресурс]](https://uguide.ru/chto-takoe-sajt-prostymi-slovami)

