---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №2
subtitle: Дискреционное разграничение прав в Linux. Основные атрибуты
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

![](/home/aalushin/work/study/study_2023-2024_infosec/labs/lab2/presentation/image/me.jpg)

:::
::::::::::::::

# Вводная часть

## Цели и задачи

- Получение практических навыков работы в консоли с атрибутами файлов, закрепление теоретических основ дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux


# Ход работы

## Создание нового пользователя

Первым делом мы создаем нового пользователя. Сделать это можно двумя вариантами: через консоль и через настройки ОС. Если мы делаем это через настройки, то первым делом вписываем "useradd", затем ставим пароль через команду "passwd". На этом создание завершено, можно переходить и использовать новый аккаунт. 

![](/home/aalushin/work/study/study_2023-2024_infosec/labs/lab2/presentation/image/1.jpg)

## Проверка прав

С помощью команды "ls -l" мы можем проверить какие права есть у директории или файла. Всего есть 3 категории прав: для владельца файла (U) ,  для владельца группы (g) и все остальные (o). Так же в каждая из категорий есть 3 права: r - read, w - write, x = exec

![](/home/aalushin/work/study/study_2023-2024_infosec/labs/lab2/presentation/image/8.jpg)

## Работа с правами

С помощью команды chmod мы можем забрать или дать права у определённого файла или директории. То есть если я пропишу 000, то у файла заберутся вообще все права. Если же я пропишу 700, то директория получит всевозможные права.

![](/home/aalushin/work/study/study_2023-2024_infosec/labs/lab2/presentation/image/12.jpg)

## Таблица 1

По ходу лабораторной работы я составил таблицу,где представлены 64 возможных выдачи прав. Начиная с прав 000 для директории и 000 для файла, заканчивая правами 700 для директории и 700 для файла. В таблице прописана возможность работы с файлом или директорией и что можно делать при определённых правах, а что нельзя.

![](/home/aalushin/work/study/study_2023-2024_infosec/labs/lab2/presentation/image/14.jpg)

## Таблица 2

Так же мы выполнили вторую таблицу, но она зависит от первой. Мы вписали необходимые права для каждого действия. То есть, если мы хотим создать файл в директории, то необходимы права 300 на директорию и 000 на файл.

![](/home/aalushin/work/study/study_2023-2024_infosec/labs/lab2/presentation/image/15.jpg)

# Результаты

## Вывод 

Я получил практические навыки работы в консоли с атрибутами файлов. Так же закрепил теоретическую основу дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux