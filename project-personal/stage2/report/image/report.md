---
## Front matter
title: "Отчёт о выполнении. Индивидуальный проект. Этап 2"
subtitle: "Операционные системы"
author: "Андреева Софья Владимировна"

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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
- \usepackage{indentfirst}
- \usepackage{float} # keep figures where there are in the text
- \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель и задачи  работы

- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору:Управление версиями. Git./Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Выполнение работы


Разместили фотографию владельца сайта, поменяв фото в соответствующей папке  (рис. [-@fig:001]).

![Разместили фотографию владельца сайта](image/1.jpg){#fig:001 width=70%}

Разместили краткое описание владельца сайта (Biography), отредактировав _index.md (рис. [-@fig:002]).

![Разместили краткое описание владельца сайта](image/2.jpg){#fig:002 width=70%}

Добавили информацию об интересах и информацию от образовании, отредактировав _index.md.Также добавили ссылки на личные страницы различных сайтов (рис. [-@fig:003]).

![Добавили информацию об интересах и информацию от образовании](image/3.jpg){#fig:003 width=70%}

Сделали пост по прошедшей неделе, добавив новую папку в каталоге blog/content/post.Написали текст в файле markdown, прикрепили фото  (рис. [-@fig:004]).

![Сделали пост по прошедшей неделе](image/4.jpg){#fig:004 width=70%}

Добавить пост на тему:" Управление версиями. Git",  добавив новую папку в каталоге blog/content/post.Написали текст в файле markdown, прикрепили фото  (рис. [-@fig:005]).

![Добавить пост на тему:" Управление версиями. Git"](image/5.jpg){#fig:005 width=70%}

Основная информация о владельце (рис. [-@fig:006]).

![Основная информация о владельце.](image/6.jpg){#fig:006 width=70%}

Посты  (рис. [-@fig:007]).

![Посты](image/7.jpg){#fig:007 width=70%}
 
# Вывод

Добавили к сайту данные о себе.
