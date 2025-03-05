---
## Front matter
title: "Отчёт по лабораторной работе №2"
subtitle: "Первоначальна настройка git"
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

Получить навыки работы с системой контроля версий git

# Выполнение лабораторной работы

1. Устанавливаем git (уже был установлен) и gh(рис. [-@fig:001]).

![Установка git и gh](image/1.png){#fig:001 width=70%}

2. Задаём имя и почту владельца репозитория(рис. [-@fig:002]).

![Задание имени и почты владельца репозитория](image/2.png){#fig:002 width=70%}

3. Задаём другие настройки (utf 8, имя начальной ветки, autocrif, safecrif)(рис. [-@fig:003]).

![Установка параметров](image/3.png){#fig:003 width=70%}

4. Создаём ключ rsa(рис. [-@fig:004]).

![Ключ rsa](image/4.png){#fig:004 width=70%}

5. Создаём ключ ed25519(рис. [-@fig:005]).

![Ключ ed25519](image/5.png){#fig:005 width=70%}

6. Генерируем ключ gpg(рис. [-@fig:006]).

![Ключ gpg](image/6.png){#fig:006 width=70%}

7. Добавляем ключ на GitHub(рис. [-@fig:007]).

![Ключ gpg на GitHub](image/7.png){#fig:007 width=70%}

8. Настраиваем автоматические подписи коммитов(рис. [-@fig:008]).

![Настройка автоматических подписей коммитов git](image/8.png){#fig:008 width=70%}

9. Авторизовываемся в gh(рис. [-@fig:009]).

![Авторизация в gh](image/9.png){#fig:009 width=70%}

10. Создаём каталог для курса и переходим в него(рис. [-@fig:010]).

![Создание и переход в каталог](image/10.png){#fig:010 width=70%}

11. Клонируем репозиторий(рис. [-@fig:011]).

![Git clone](image/11.png){#fig:011 width=70%}

12. Переходим в каталог и удаляем лишний файл(рис. [-@fig:012]).

![Работа с репозиторием](image/12.png){#fig:012 width=70%}

13. Создаём необходимые каталоги(рис. [-@fig:013]).

![Создание каталогов](image/13.png){#fig:013 width=70%}

14. Отправляем изменения на сервер(рис. [-@fig:014], рис. [-@fig:015]).

![Добавление файлов и коммиты](image/14.png){#fig:014 width=70%}

![Отправка на сервер](image/15.png){#fig:015 width=70%}




# Выводы

Были получены и отработаны практические навыки по работе с git.

