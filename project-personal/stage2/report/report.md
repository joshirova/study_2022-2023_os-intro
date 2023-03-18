---
## Front matter
title: Индивидуальный проект. Этап 2.
subtitle: Дисциплина - Операционные системы
author: Оширова Юлия Николаевна, НКАбд-02-22

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

Продолжить работы со своим сайтом. Редактировать его в соответствие с требованиями. Добавить данные о себе на сайт.

# Задание

1. Разместить фотографию владельца сайта.

2. Разместить краткое описание владельца сайта (Biography).

3. Добавить информацию об интересах (Interests).

4. Добавить информацию от образовании (Education).

5. Сделать пост по прошедшей неделе.

6. Добавить пост на тему по выбору: Управление версиями. Git. Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Теоретическое введение

Сайт – это совокупность веб-страниц, объединённых под общим доменом и связанных ссылками, тематикой и дизайнерским оформлением [1] . Мы будем создавать статический сайт, для этого нам понадобится Hugo. Hugo — генератор статических страниц для интернета.

Мы продолжаем работу с Hugo. Будем учиться редактировать данные о себе и писать посты.

# Выполнение лабораторной работы

1. Разместим свою фотографию на сайте:

![Добавление фотографии в репозиторий](image/d1){#fig:001 width=70%}

2. Разместим краткое описание владельца сайта (Biography).

3. Добавим информацию об интересах (Interests).

4. Добавим информацию от образовании (Education).

![Изменение в файле данных о себе](image/d2){#fig:002 width=70%}

![Добавление изменений в репозиторий](image/d3){#fig:003 width=70%}

![Результат на сайте](image/d4){#fig:004 width=70%}

5. Добавим пост на тему по выбору. Я выбрала тему: Управление версиями. Git:

![Написали информацию про пост о Git](image/d5){#fig:005 width=70%}

![Пост о Git](image/d6){#fig:006 width=70%}

6. Сделаем пост по прошедшей неделе:

![Написали информацию про пост о прошедшей неделе](image/d7){#fig:007 width=70%}

![Пост о прошедшей неделе](image/d8){#fig:008 width=70%}

![Результат на сайте](image/d9){#fig:009 width=70%}

# Выводы

В процессе выполнения второго этапа индивидуального проекта я научилась редактировать данные о себе, а также писать посты и добывлять их на сайт.

# Список литературы{.unnumbered}

[1. Что такое сайт (простыми словами)](https://uguide.ru/chto-takoe-sajt-prostymi-slovami)

