Маршрутизация
#######

.. php:namespace:: Cake\Routing

.. php:class:: Router

Маршрутизация предоставляет инструменты, которые показывают URL-адреса для действий 
контроллера. Определяя маршруты, вы можете разделить реализацию приложения и структуру 
его URL-адреса.

Маршрутизация в CakePHP также включает идею обратной маршрутизации, где массив параметров 
может быть преобразован в строку URL. С помощью обратной маршрутизации, вы можете изменить 
структуру URL вашего приложения, без необходимости обновлять весь код.

.. index:: routes.php

Краткий Обзор
==========

Этот раздел познакомит вас с наиболее часто используемыми маршрутами в CakePHP. Обычно, если вы 
хотите показать главную страницу, то добавьте эти строки в свой **routes.php** файл::

.. index:: :controller, :action, :plugin
.. index:: greedy star, trailing star
.. _connecting-routes:
.. _routes-configuration:

Connecting Routes
=================

.. _route-elements:

Route Elements
--------------

.. _named-routes:

Using Named Routes
------------------

.. index:: admin routing, prefix routing
.. _prefix-routing:

Prefix Routing
--------------

.. index:: plugin routing

Plugin Routing
--------------

.. index:: file extensions
.. _file-extensions:

Routing File Extensions
-----------------------

.. _resource-routes:

Creating RESTful Routes
=======================

.. _custom-rest-routing:

Custom Route Classes for Resource Routes
----------------------------------------

.. index:: passed arguments
.. _passed-arguments:

Passed Arguments
================

.. _redirect-routing:

Redirect Routing
================

.. _custom-route-classes:

Custom Route Classes
====================

.. toctree::
    :glob:
    :maxdepth: 1

    /development/dispatch-filters

.. meta::
    :title lang=ru: Routing
    :keywords lang=ru: controller actions,default routes,mod rewrite,code index,string url,php class,incoming requests,dispatcher,url url,meth,maps,match,parameters,array,config,cakephp,apache,router
