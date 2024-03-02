---
## Front matter
lang: ru-RU
title: Презентация по первой части индивидуального проекта
subtitle: Установка Операционной системы Kali
author:
  - Лушин А.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Факультет Физико-математических и естественных наук
date: 18 февраля 2005

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

  * Лушин Артём Андреевич
  * Бакалавр направления компьютерные и информационные науки
  * Кафедра теории вероятности и кибербезопасности
  * Российский университет дружбы народов
  * Редактор Первого Федерального канала
  * [lusin5745@gmail.com](mailto:lusin5745@gmail.com)

:::
::: {.column width="30%"}

![](/home/aalushin/work/study/study_2023-2024_infosec/labs/lab1/presentation/image/me.jpg)

:::
::::::::::::::

# Вводная часть

## Цели и задачи

- Установить операционную систему "Kali" и создать пользователя.

# Ход работы

## Создание новой виртуальной машины

В самом начале работы мы создаём новую виртуальную машину. Предварительно необходимо скачать программу VirtualBox. При создании указываем название машины, тип операционной системы, папку, где будут располагаться файлы и версию возможной ОС.

![](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/presentation/image/1.jpg)

## Выбор локации

Чтобы выбрать нашу локацию нужно немного постараться. Так как в основном списке нет России, то мы переходим в раздел "other", затем выбираем "Europe" и уже там выбираем Российскую Федерацию.

![](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/presentation/image/5.jpg)

## Установка сети

Когда мы устанавливаем сеть, в качестве хоста мы вписываем какое-то либо. В моём случае это "Kali", а в качестве домена я вписываю свой ник с припиской localdomain. То есть получилось aalusin.localdomain.

![](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/9.jpg)

## Создание пользователя

В задании нас попросили установить имя пользователя "root", но так назвать пользователя нельзя. Поэтому я указал имя "root1". А в качестве пароля "toor".

![](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/11.jpg)

## Установка диска. 

Чтобы установить диск нам в первом окне нужно выбрать "use entire disk". Затем в предложенном окне выбираем такой диск, который хотим использовать. И в следующем окне у нас появится общая информация, мы её сверяем и завершаем присоединение диска.

![](/home/aalushin/work/study/study_2023-2024_project/labs/lab1/report/image/14.jpg)

# Результаты

## Вывод 

Я установил операционную систему "Kali", настроил её и создал пользователя.


