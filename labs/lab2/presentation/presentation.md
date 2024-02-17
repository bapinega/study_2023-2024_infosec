---
## Front matter
lang: ru-RU
title: Лабораторная работа 2
subtitle: Основы информационной безопасности
author:
  - Пинега Б.А.
institute:
  - Российский университет дружбы народов, Москва, Россия

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

## Докладчик

  * Пинега Белла Александровна
  * Студентка НБИбд-02-22
  * Российский университет дружбы народов

:::
::::::::::::::

## создам учётную запись пользователя guest 
![рис 1](image/1.png){#fig:001 width=40%}

## Войду в систему от имени пользователя guest и увижу где я нахожусь
![рис 2](image/2.png){#fig:002 width=40%}
Я нахожусь не в домашней директории

## имя моего пользователя 
![рис 3](image/3.png){#fig:003 width=40%}

## сравним
![рис 4](image/4.png){#fig:004 width=25%}
![рис 5](image/5.png){#fig:005 width=25%}

## просмотрю файл /etc/passwd
![рис 6](image/6.png){#fig:006 width=70%}
Можно заметить что значения совпадают с значениями с фото 4

## список поддиректорий директории /home и их права
![рис 7](image/7.png){#fig:007 width=70%}

## права dir1 
создам файл file1, тк я сняла с директории все атрибуты я получаю отказ.
![рис 8](image/8.png){#fig:008 width=70%}

## таблица
![рис 9](image/9.jpeg){#fig:009 width=70%}

## Выводы
Я приобрела практические навыки работы в консоли с атрибутами файлов, закрепление теоретических основ дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linuх.
