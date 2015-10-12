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

* **Структура проекта:**
  :doc:`Общее описание <general/project-structure>` |
  :doc:`Система бандлов <general/bundles>` |
  :doc:`Управление внешними зависимостями <general/dependencies>`

* :doc:`RequireJS и система путей в CordJS <general/requirejs>`

* :doc:`Роутинг <general/routes>`

* :doc:`Сервисы и dependency injection <general/di>`

* **Ключевые концепции:**
  :ref:`Непротивление асинхронности <key-concepts-async>` |
  :ref:`Изоморфность <key-concepts-isomorph>`


Виджет --- главная сущность в CordJS
====================================

Вероятно, самая главная часть этой документации, поскольку подавляющая часть кода проекта на CordJS --- код виджетов.
Здесь наиболее полная информация о том, как программировать виджеты.

* :doc:`Обзор подсистемы виджетов <widget/overview>`
* :ref:`Описание жизненного цикла виджета <widget-life-cycle>`
* :doc:`Главный класс виджета <widget/main-class>`
* :doc:`Шаблон виджета <widget/template>`
* :doc:`Класс-поведение (behaviour) <widget/behaviour>`
* :doc:`Работа с CSS <widget/css>`


Модель --- гибкая абстракция для работы с данными через REST API
================================================================

* :doc:`Ознакомление с концепцией "репозиторий-коллекция-модель" <model/intro>`

* **API подсистемы моделей:**
  :doc:`Репозиторий <model/api-repo>` |
  :doc:`Коллекция <model/api-collection>` |
  :doc:`Модель <model/api-model>`

* :doc:`Связка с виджетами (binding) <model/widget-binding>`
* :doc:`Под капотом: API <model/low-level-api>`


Под капотом
===========

Про особенности внутренней реализации:

* :doc:`Доморощенный Рromise - Future <utils/future>`


CLI-инструмент ``cordjs``
=========================

* :doc:`Обзор <cli/overview>`
* :doc:`Описание команд для сборки проекта <cli/build>`
* :doc:`Как пользоваться в процессе разработки <cli/run>`
* :doc:`Оптимизатор и сборка релизов <cli/optimize>`


Contributing
============

* :doc:`Как писать эту документацию <contributing/writing-documentation>`


Индексы и Таблицы
=================

* :doc:`Подробное оглавление <contents>`
* :doc:`glossary`
* :ref:`genindex`
* :ref:`search`
