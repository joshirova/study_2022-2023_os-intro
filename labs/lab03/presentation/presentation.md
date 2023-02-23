---
## Front matter
lang: ru-RU
title: Лабораторная работа №3
subtitle: Дисциплина - Операционные системы
author:
  - Оширова Ю. Н., НКАбд-02-22
institute:
  - Российский университет дружбы народов, Москва, Россия
  - ФФМиЕН, направление - "Компьютерные и информационные технологии"
date: 23 февраля 2023

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
  * направление - "Компьютерные и информационные науки"
  * Российский университет дружбы народов
  * [1132222843@rudn.ru](1132222843@rudn.ru)
  * <https://github.com/joshirova>

:::
::: {.column width="30%"}


:::
::::::::::::::

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

# Как, что и зачем?

## Цели и задачи

- Научиться оформлять отчеты с помощью языка разметки Markdown.
- Научиться конвертировать отчет из мд в пдф и докс.

## Вывод

Я научилась оформлять отчет с помощью языка разметки Маркдаун, а также конвертировать его из мд в пдф и докс.

## Список литературы

[Что такое Маркдаун?](https://ru.wikipedia.org/wiki/Markdown)


:::

