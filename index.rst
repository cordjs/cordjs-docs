.. CordJS documentation master file, created by
   sphinx-quickstart on Sat Mar 15 18:49:15 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

*************************
Обзор документации CordJS
*************************

Вы попали на сайт документарции фронтенд-фреймворка CordJS. Здесь собрана информация, которая позволит вам
разрабатывать приложения с использованием этого фреймворка.


Первые шаги
===========

Если вы новичок в разработке на CordJS, то вам сюда:

* **С нуля:**
  :doc:`Что за зверь такой? <intro/about>` |
  :doc:`Обзор возможностей <intro/overview>`

* **Начало работы:**
  :ref:`Установка <quickstart-install>` |
  :ref:`Создание нового проекта <quickstart-create-project>` |
  :ref:`Hello world! <quickstart-hello-world>` |
  :ref:`Добавим структуру <quickstart-layout>` |
  :ref:`Параметры и состояние виджета <quickstart-state>` |
  :ref:`Переходы между страницами <quickstart-page-transitions>` |
  :ref:`Динамическое поведение <quickstart-behaviour>`


Общая информация --- как всё работает
=====================================

Здесь вы найдёте общую информацию о том, из чего состоит проект на CordJS и как это всё друг с другом работает.

* **Ключевые концепции:**
  :doc:`Непротивление асинхронности <general/async>` |
  :doc:`Изоморфность <general/isomorph>` |
  :doc:`Главное - представление <general/view-first>` |
  :doc:`Инкапсуляция поведения в компоненте-виджете <general/incapsulation>`

* **Структура проекта:**
  :doc:`Общее описание <general/project-structure>` |
  :doc:`Система бандлов <general/bundles>` |
  :doc:`Управление внешними зависимостями <general/dependencies>`

* **requirejs и система путей в CordJS**

* **Роутинг:**

* **Сервисы и dependency injection:**


Виджет --- главная сущность в CordJS
====================================

* :doc:`Обзор подсистемы виджетов <widget/overview>`
* :ref:`Описание жизненного цикла виджета <widget-life-cycle>`
* :doc:`Главный класс виджета <widget/main-class>`
* :doc:`Шаблон виджета <widget/template>`
* :doc:`Класс-поведение (behaviour) <widget/behaviour>`
* Работа с CSS


Модель --- гибкая абстракция для работы с данными через REST API
================================================================

* Ознакомление с концепцией: репозиторий-коллекция-модель
* Чтение и запись данных.
* Связка с виджетами (binding).
* Под капотом: API.


Под капотом
===========

Про особенности внутренней реализации:

* :doc:`Доморощенный Рromise - Future <internals/future>`
* :doc:`Компиляция шаблонов с помощью dustjs <internals/dustjs>`
* :doc:`Coffee-script style guide <internals/styleguide>`


CLI-инструмент ``cordjs``
=========================

* Базовые функцкии
* Как пользоваться в процессе разработки
* Оптимизатор и сборка релизов


Contributing
============

* :doc:`Как писать эту документацию <contributing/writing-documentation>`


Индексы и Таблицы
=================

* :doc:`Подробное оглавление <contents>`
* :ref:`genindex`
* :ref:`search`
