---
## Front matter
title: "Отчёт по лабораторной работе №4"
subtitle: "Продвинутое использование git"
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

Научиться правильно работать с git flow

# Выполнение лабораторной работы

1. Устанавливаем git flow(рис. [-@fig:001]).

![Установка git flow](image/1.png){#fig:001 width=70%}

2. Устанавливаем nodeJS(рис. [-@fig:002]).

![Установка nodeJS](image/2.png){#fig:002 width=70%}

3. Устанавливаем pnpm(рис. [-@fig:003]).

![Установка pnpm](image/3.png){#fig:003 width=70%}

4. Добавляем каталог с исполняемыми файлами через команду source(рис. [-@fig:004]).

![Добавление источника](image/4.png){#fig:004 width=70%}

5. Устанавливаем commitizen(рис. [-@fig:005]).

![Установка commitizen](image/5.png){#fig:005 width=70%}

6. Устанавливаем standard-changelog(рис. [-@fig:006]).

![Устанавливаем standard-changelog](image/6.png){#fig:006 width=70%}

7. Создаём новый репозиторий git-extended(рис. [-@fig:007]).

![Создание репозитория](image/7.png){#fig:007 width=70%}

8. Клонируем на виртуальную машину файлы репозитория(рис. [-@fig:008]).

![Клонирование репозитория](image/8.png){#fig:008 width=70%}

9. Добавляем коммит(рис. [-@fig:009]).

![Коммит](image/9.png){#fig:009 width=70%}

10. Выкладываем на github(рис. [-@fig:010]).

![Отправка на сервер](image/10.png){#fig:010 width=70%}

11. Меняем конфигурацию nodeJS(рис. [-@fig:011]).

![Шаблон конфигурации](image/11.png){#fig:011 width=70%}

12. Вписываем собственные данные(рис. [-@fig:012]).

![Готовая конфигурация](image/12.png){#fig:012 width=70%}

13. Отправляем на github(рис. [-@fig:013]).

![Отправка на сервер](image/13.png){#fig:013 width=70%}

14. Настраиваем git flow(рис. [-@fig:014]).

![Настройка git flow](image/14.png){#fig:014 width=70%}

15. Создаём новый релиз 1.0.0(рис. [-@fig:015]).

![Создание релиза](image/15.png){#fig:015 width=70%}

16. Добавляем changelog(рис. [-@fig:016]).

![Добавление changelog](image/16.png){#fig:016 width=70%}

17. Отправка всего на сервер + создание нового релиза(рис. [-@fig:017]).

![Действия с репозиторием](image/17.png){#fig:017 width=70%}

18. Меняем версию в package.json(рис. [-@fig:018]).

![Редактирование конфигурации](image/18.png){#fig:018 width=70%}

19. Отправляем новый релиз на сервер(рис. [-@fig:019]).

![Отправка на github](image/19.png){#fig:019 width=70%}



# Выводы

Были получены и отработаны практические навыки по работе с git flow и релизами.

