---
## Front matter
title: "Индивидуальный проект 1 части"
subtitle: "Установка Операционной системы Kali"
author: "Лушин Артём Андреевич"

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
biblatex: false
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

# Цель работы

Установить операционную систему "Kali" и создать пользователя.



# Выполнение лабораторной работы

1) Я создал новую виртуальную машину "Kali", указал образ ISO и поставил тип Linux.

![Создание новой ос](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/1.jpg){#fig:001 width=70%}

2) Указал 110042 МБ основной памяти для использования а так же выставил 10 процессоров, чтобы ос использовала их.

![Основная памяти и процессоры](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/2.jpg){#fig:002 width=70%}

3) Создал новый виртуальный жёсткий диск на 84 гигабайта. 

![Создание виртуального диска](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/3.jpg){#fig:003 width=70%}

4) При запуске ОС у нас начинается её настройка. Первым делом я выбрал английский язык всей ос.

![Выбор языка](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/4.jpg){#fig:004 width=70%}

5) Чтобы выбрать мою локацию нужно немного постараться. Так как в основном списке нет России, то мы переходим в раздел "other", затем выбираем "Europe" и уже там выбираем Российскую Федерацию.

![Раздел other](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/5.jpg){#fig:005 width=70%}

![Выбор Европы](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/6.jpg){#fig:006 width=70%}

![Выбор страны](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/7.jpg){#fig:007 width=70%}

6) Для удобства я выбрал раскладку клавиатуры - американскую английскую.

![Раскладка клавиатуры](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/8.jpg){#fig:008 width=70%}

7) Чтобы установить имя сети, в качестве хоста я пишу "Kali", а в качестве домена "aalusin.localdomain".

![Установка хоста](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/9.jpg){#fig:009 width=70%}

![Установка домена](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/20.jpg){#fig:010 width=70%}

8) В задании нас попросили установить имя пользователя "root", но так назвать пользователя нельзя. Поэтому я указал имя "root1". А в качестве пароля "toor".

![Создание пользователя](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/11.jpg){#fig:011 width=70%}

![Установка пароля](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/12.jpg){#fig:012 width=70%}

9) Для удобства установил московское время.

![Установка времени](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/13.jpg){#fig:013 width=70%}

10) Чтобы установить диск нам в первом окне нужно выбрать "use entire disk". Из предложенных дисков выбираем нужный нам. Завершаем присоединение диска.

![Выбор формата диска](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/14.jpg){#fig:014 width=70%}

![Выбор нужного диска](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/15.jpg){#fig:015 width=70%}

![Завершение установки](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/16.jpg){#fig:016 width=70%}

11) Установка программного обеспечения. Здесь нам предлагают уже оптимальные программы, которые нужны будут. 

![Программное обеспечение.](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/17.jpg){#fig:017 width=70%}

12) Выбираем путь куда будут сохраняться наши файлы.

![Путь для сохранения](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/18.jpg){#fig:018 width=70%}

# Выводы

Я установил операционную систему "Kali", настроил её и создал пользователя.
