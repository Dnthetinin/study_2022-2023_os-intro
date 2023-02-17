---
## Front matter
lang: ru-RU
title: Лабораторная работа 2 
author:
  - Щетинин Даниил Николаевич
institute:
  - Российский университет дружбы народов, Москва, Россия
 
date: 17.02.2023

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

# Вводная часть

## Цель работы


   - Изучить идеологию и применение средств контроля версий.
    
   - Освоить умения по работе с git.
    

## Задание

::: incremental

   - Создать базовую конфигурацию для работы с git.
    
   - Создать ключ SSH.
    
   - Создать ключ PGP.
    
   - Настроить подписи git.
    
   - Зарегистрироваться на Github.
    
   - Создать локальный каталог для выполнения заданий по предмету.

## Шаг 1 

Установим git и gh, посредством введения команд 

```
dnf install git
dnf install gh
```


![Установка git и gh](image/1.jpg){#fig:001 width=70%}

## Шаг 2 

Проведём базовую настройку git: 
Зададим имя и email владельца репозитория, Настроим utf-8 в выводе сообщений git и прочее


![выполненные команды](image/2.jpg){#fig:002 width=70%}


## Шаг 3

Перейдём к генерации ключей, начнем с ssh (уже сгенерирован) и pgp

![Сгенерированный ключ ssh](image/3.jpg){#fig:003 width=70%}

![Сгенерированный ключ pgp](image/4.jpg){#fig:004 width=70%}

## Шаг 4 

После чего создаем учетную запись на github:

![Домашняя страница, созданная учетная запись](image/5.jpg){#fig:005 width=70%}

## Шаг 5 

Добавим pgp ключ 

![добавленный ключ](image/6.jpg){#fig:006 width=70%}


## Шаг 6

Добавив ключ, закончим настройку git, авторизуемся в gh:

![настройка и авторизация](image/7.jpg){#fig:007 width=70%}

## Шаг 7 


![использованные команды](image/8.jpg){#fig:008 width=70%}

![репозиторий на github](image/9.jpg){#fig:009 width=70%}


## Конец

Спасибо за внимание! 



