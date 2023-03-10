---
## Front matter
title: Индивидуальный проект. 1 этап.
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

Научиться создавать сайт на Хьюго, создать необходимые репозитории.

# Задание

№1 Первый этап процесса (Хьюго, новый репозиторий).

№2 Второй этап процесса.

# Теоретическое введение

Хьюго - это один из генераторы статических сайтов с открытым исходным кодом самый популярный, который к тому же совершенно бесплатный. Обладая поразительной скоростью и гибкостью, этот генератор позволяет быстро и легко создавать веб-сайты.

Общая характеристика Хьюго

- Высокая скорость. Как указано на их веб-сайте, это самый быстрый инструмент в своем роде. В среднем сайт создается менее чем за секунду.
- Надежное управление контентом и правила гибкости. Хьюго - мечта контент-стратега. Хьюго поддерживает неограниченное количество типов контента, таксономий, меню, динамического контента на основе API и т. д., все без надстроек.
- Шорткоды предлагают нам возможность использовать синтаксис Markdown, обеспечивая большую гибкость.
- Встроенные шаблоны. Этот конструктор статических веб-сайтов имеет общие шаблоны для быстрого создания нашей работы. Hugo поставляется с готовыми шаблонами для быстрой работы с SEO, комментариев, аналитики и других функций.
- Пользовательские выходы. Позволяет нам генерировать наш контент в нескольких форматах, включая JSON или AMP, и, таким образом, облегчить создание контента.
- Доступно более 300 тем, давая нам надежную систему тем, которую легко реализовать, но способную создавать даже самые сложные веб-сайты. Может быть брошен взглянуть на темы доступно на сайте проекта.


# Выполнение лабораторной работы

***Первый этап***

Первое, что нам нужно, это скачать файл хьюго, чтобы генерировать страницу сайта, ссылку можно найти в описании к индивидуальному проекту:

![Скачивание Хьюго](image/b1){#fig:001 width=70%}

Скачиваем файл hugo_extended последней версии (110) в tar.gz, разархивируем и перенесем в текущую папку. Копируем этот файл и вырежем.

В домашней папке создаем пустую папку «bin» и скопируем этот файл туда:

![Создание папки "Бин" и скопируем файл туда](image/b2){#fig:002 width=70%}

Создаем репозиторий на основе шаблона, переходим по ссылке и нажимаем «use this template». Указываем имя «blog»:

![Создание репозитория на основе шаблона](image/b3){#fig:003 width=70%}

После этого клонируем его в терминале. Появится каталог «blog», а внутри уже будут все файлы:

![Клонирование репозитория в терминале](image/b4){#fig:004 width=70%}

![Все файлы появились](image/b5){#fig:005 width=70%}

Переходим в блог, можем видеть все файлы с помощью команды «ls -l».

Пишем команду «~\bin\hugo»:

![Выполнение команды](image/b6){#fig:006 width=70%}

С помощью команды mc удаляем каталог «public»:

![Удаление "Паблик"](image/b7){#fig:007 width=70%}

Выполним команду «~\bin\hugo server»:

![Выполнение команды](image/b8){#fig:008 width=70%}

Видим ссылку в выводе, копируем и вставляем в браузере, видим сайт, который доступен только нам:

![Сайт, который доступен только нам](image/b9){#fig:009 width=70%}

***Второй шаг***

Переносим сайт на еще один репозиторий. Надо будет создать его. Чтобы это сделать, надо перейти в гитхаб, создадим репозиторий со специальным названием, в моем случае «joshirova.github.io»:

![Создание репозитория с именем аккаунта на Гитхаб](image/b10){#fig:010 width=70%}

Переходим в терминал, клонируем репозиторий с помощью команды «git clone —rescursive (ваша ссылка на репозиторий)»:

![Клонируем репозиторий](image/b11){#fig:011 width=70%}

Перейдя в него, выполняем команду «git checkout -b main»:

![Выполнение команды](image/b12){#fig:012 width=70%}

После этого создаем пустой файл с помощью команды «touch README.md». Добавляем файл на гитхаб с помощью уже знакомых команд с прошлого и нынешнего семестра:

![Создаем пустой файл и добавляем на Гитхаб](image/b13){#fig:013 width=70%}

Проверив в браузере на гитхабе в репозитории, удостоверились, что файл появился.

Переходим обратно в blog, выполним команду, которая подключит новый репозиторий к папке public внутри нашего blog (заранее исправив «#public/ в комментировании .gitignore):

![Подключаем новый репозиторий к папке Паблик](image/b14){#fig:014 width=70%}

С помощью команды «~/bin/hugo» в папке public автоматически появились файлы:

![С помощью команды осуществилось появление файлов](image/b15){#fig:015 width=70%}

Синхронизуем эти файлы с репозиторием, возвращаемся в public, делаем стандартные действия:

![Отправка на Гитхаб](image/b16){#fig:016 width=70%}

Обновляем репозиторий и видим, что все файлы появились.

Копируем ссылку на наш новый сайт, подождём секунд 20 и позже появится полноценный сайт, который в дальнейших этапах индивидуального проекта мы будем редактировать:

![Наш будущий сайт](image/b17){#fig:017 width=70%}

# Выводы

Я создала сайт на Хьюго, а также нужные репозитории.

# Список литературы{.unnumbered}

[1. Что такое Хьюго?](https://ubunlog.com/ru/hugo-generador-sitios-web-estaticos/)

[2. Первый этап индивидуального проекта](https://vk.com/away.php?utf=1&to=https%3A%2F%2Fyoutu.be%2FOpsSv0RE3C4)
::: {#refs}
:::
