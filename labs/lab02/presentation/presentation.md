---
## Front matter
lang: ru-RU
title: Лабораторная работа №1
subtitle: Дисциплина - Операционные системы
author:
  - Оширова Юлия Николаевна, НКАбд-02-22
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 18 февраля 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Оширова Юлия Николаевна
  * студентка группы НКАбд-02-22
  * факультет ФФМиЕН: направление "Компьютерные и информационные науки"
  * Российский университет дружбы народов
  * [1132222843@pfur.ru]
  * <https://github.com/joshirova>

:::
::: {.column width="30%"}


:::
::::::::::::::

# Вводная часть



# Создание презентации

## Процессор `pandoc`

- Pandoc: преобразователь текстовых файлов
- Сайт: <https://pandoc.org/>
- Репозиторий: <https://github.com/jgm/pandoc>

## Формат `pdf`

- Использование LaTeX
- Пакет для презентации: [beamer](https://ctan.org/pkg/beamer)
- Тема оформления: `metropolis`

## Код для формата `pdf`

```yaml
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
```

## Формат `html`

- Используется фреймворк [reveal.js](https://revealjs.com/)
- Используется [тема](https://revealjs.com/themes/) `beige`

## Код для формата `html`

- Тема задаётся в файле `Makefile`

```make
REVEALJS_THEME = beige 
```

# Цели лабораторной работы

- Изучить идеаологию и применение средств контроля версий.
- Освоить умения по работе с Git.



:::

# Основные задачи

- Зарегистрироваться на Github;
- Создать базовую конфигурацию для работы с Git; 
- Создать ключ SSH;
- Создать ключ PGP; 
- Настроить подписи Git;
- Создать локальный каталог для выполнения заданий по предмету.

:::

# Вывод

Я изучила средства контроля версий и научилась применять их. Освоила работу с Git, научилась подключать репозитории, добавлять и удалять необходимые файлы.

:::

