---
## Front matter
title: "Отчёт по прохождению внешнего курса"
subtitle: "3 этап"
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

Пройти третий этап внешнего курса "Введение в Linux".

# Выполнение этапа

1. Теоретический вопрос (рис. [-@fig:001]).

![Задание 1](image/1.png){#fig:001 width=70%}

2. Вот объяснение команды :%s/Windows/Linux в vim:

: — вводит командный режим в vim.
% — означает, что команда применяется ко всему файлу (все строки).
s — команда замены (substitute).
/Windows/ — шаблон, который ищется в строке; в данном случае слово "Windows".
/Linux — текст, на который заменяется найденный шаблон; в данном случае "Linux".(рис. [-@fig:002]).

![Задание 2](image/2.png){#fig:002 width=70%}

3. Команды из набора А (первой оболочки bash) не будут доступны, потому что они были введены в другой сессии.
Команды из набора В (оболочка sh) не будут доступны, потому что они были введены в другой сессии sh.
Команды из набора С (последняя запущенная оболочка bash) будут доступны при перемещении по истории.(рис. [-@fig:003]).

![Задание 3](image/3.png){#fig:003 width=70%}

4. Файл создан в каталоге /home/bi. Потом просто перешли в другой каталог. Это не поменяло путь к файлу (рис. [-@fig:004]).

![Задание 4](image/4.png){#fig:004 width=70%}

5. VARiable

Начинается с буквы, содержит только буквы.
Подходит
123variable

Начинается с цифры.
Не подходит
variable_123

Начинается с буквы, содержит буквы, цифры и подчеркивание.
Подходит
variable

Начинается с буквы, только буквы.
Подходит
variable123

Начинается с буквы, содержит буквы и цифры.
Подходит
_variable

Начинается с подчеркивания, что допустимо.
Подходит
__variable

Начинается с двух подчеркиваний, что тоже допустимо.
Подходит

(рис. [-@fig:005]).

![Задание 5](image/5.png){#fig:005 width=70%}

6. Легкий скрипт, который выводит то, что получает(рис. [-@fig:006]).

![Задание 6](image/6.png){#fig:006 width=70%}

7. Довольно сложное задание. На решение понадобилось достаточно много времени.(рис. [-@fig:007]).

![Задание 7](image/7.png){#fig:007 width=70%}

8. Первый запуск: var=3
Подставим var=3 в условия:

if []]
— 3 > 5? Нет, условие ложно.
elif []]
— 3  3? Нет, равно, условие ложно.
elif [ ]
— 3 == 4? Нет, условие ложно.
Все условия ложны, значит выполнится блок else:

echo "four"


Второй запуск: var=5
Подставим var=5:

if []
— 5 > 5? Нет, равно, условие ложно.
elif []
— 5  3? Нет, условие ложно.
elif []
— 5 == 4? Нет, условие ложно.
Все условия ложны, снова выполняется блок else:

echo "four"(рис. [-@fig:008]).

![Задание 8](image/8.png){#fig:008 width=70%}

9. Простая программа на bash, с обычными ветвлениями через if/elif/else(рис. [-@fig:009]).

![Задание 9](image/9.png){#fig:009 width=70%}

10. Подсчитаем сколько раз выводятся слова на каждой итерации:

1	a	start	Нет	finish
2	,	start	Нет	finish
3	b	start	Нет	finish
4	,	start	Нет	finish
5	c_d	start	Да	continue (пропуск finish)

(рис. [-@fig:010]).

![Задание 10](image/10.png){#fig:010 width=70%}

11. Опять же довольно простая программа. Надо только написать бесконечный цикл, прописать условия выхода(рис. [-@fig:011]).

![Задание 11](image/11.png){#fig:011 width=70%}
![Код](image/12.png){width=70%}

12. Программа для поиска НОД. Уже более сложная. Так же используется бесконечный цикл, if else, while.(рис. [-@fig:012]).

![Задание 12](image/13.png){#fig:012 width=70%}
![Код](image/14.png){width=70%}

13. Калькулятор на bash(рис. [-@fig:013]).

![Задание 13](image/15.png){#fig:013 width=70%}
![Код](image/16.png){width=70%}


14. Объяснение параметров команды:
-mindepth 2: искать файлы, начиная со второго уровня вложенности относительно /home/bi.
-maxdepth 3: искать только до третьего уровня вложенности.
-name "file*": искать файлы, имена которых начинаются с "file".
Расположение файлов по уровням:
/home/bi/dir1 — уровень 1 (относительно /home/bi)
/home/bi/dir1/file1 — уровень 2
/home/bi/dir1/dir2 — уровень 2
/home/bi/dir1/dir2/file2 — уровень 3
/home/bi/dir1/dir2/dir3 — уровень 3
/home/bi/dir1/dir2/dir3/file3 — уровень 4
Анализ по условиям:
-mindepth 2: ищем начиная со второго уровня, то есть начиная с /home/bi/... внутри.
-maxdepth 3: ищем только до третьего уровня.
Это значит, что ищем файлы, расположенные на уровнях 2 и 3.

Какие файлы подходят?
file1: находится в /home/bi/dir1/file1, уровень 2 → подходит.
file2: находится в /home/bi/dir1/dir2/file2, уровень 3 → подходит.
file3: находится в /home/bi/dir1/dir2/dir3/file3, уровень 4 → не подходит, так как maxdepth=3.(рис. [-@fig:016]).

![Задание 14](image/17.png){#fig:016 width=70%}

15. Без -n, sed по умолчанию печатает каждую строку после обработки, независимо от команд внутри скрипта.(рис. [-@fig:017]).

![Задание 15](image/18.png){#fig:017 width=70%}

16. Инструкция sed(рис. [-@fig:018]).

![Задание 16](image/19.png){#fig:018 width=70%}

17. gnuplot(рис. [-@fig:019]).

![Задание 17](image/20.png){#fig:019 width=70%}

18. Меняем работу программы под условие(рис. [-@fig:020]).

![Задание 18](image/21.png){#fig:020 width=70%}


# Выводы

Были получены знания о Линуксе: vim, bash, gnuplot. Были выполнены тесты.

