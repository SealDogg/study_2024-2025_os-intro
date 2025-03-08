---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 1"
author: "Ярослав Антонович Меркулов"

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

# Цель работы

Разместить на github pages заготовку для персонального сайта.

# Выполнение

1. Устанавливаем hugo, переносим его в /usr/local/bin(рис. [-@fig:001]).

![Установка hugo](image/1.png){#fig:001 width=70%}

2. Создаём новый репозиторий из шаблона(рис. [-@fig:002]).

![Создание нового репозитория](image/2.png){#fig:002 width=70%}

3. Клонируем репозиторий на машину(рис. [-@fig:003]).

![Клонирование репозитория](image/3.png){#fig:003 width=70%}

4. Создаём сам сайт командой hugo, генерируются новые файлы(рис. [-@fig:004]).

![Команда hugo](image/4.png){#fig:004 width=70%}

5. Отправляем всё на github с помощью git push(рис. [-@fig:005]).

![Загрузка на сервер](image/5.png){#fig:005 width=70%}

6. Проверяем работоспособность сайта. Сайт работает(рис. [-@fig:006]).

![Готовый шаблон](image/6.png){#fig:006 width=70%}

7. Проверяем git pages(рис. [-@fig:007]).

![Git Pages](image/7.png){#fig:007 width=70%}





# Выводы

Заготовка персонального сайта была выложена на git hub. Использовалась утилита hugo
