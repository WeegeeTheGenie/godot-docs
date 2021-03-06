:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the NavigationObstacle.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_NavigationObstacle:

NavigationObstacle
==================

**Inherits:** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

3D Obstacle used in navigation for collision avoidance.

Description
-----------

3D Obstacle used in navigation for collision avoidance. The obstacle needs navigation data to work correctly. This can be done by having the obstacle as a child of a :ref:`Navigation<class_Navigation>` node, or using :ref:`set_navigation<class_NavigationObstacle_method_set_navigation>`. ``NavigationObstacle`` is physics safe.

Methods
-------

+-------------------------+----------------------------------------------------------------------------------------------------------------------+
| :ref:`Node<class_Node>` | :ref:`get_navigation<class_NavigationObstacle_method_get_navigation>` **(** **)** const                              |
+-------------------------+----------------------------------------------------------------------------------------------------------------------+
| void                    | :ref:`set_navigation<class_NavigationObstacle_method_set_navigation>` **(** :ref:`Node<class_Node>` navigation **)** |
+-------------------------+----------------------------------------------------------------------------------------------------------------------+

Method Descriptions
-------------------

.. _class_NavigationObstacle_method_get_navigation:

- :ref:`Node<class_Node>` **get_navigation** **(** **)** const

Returns the :ref:`Navigation<class_Navigation>` node that the obstacle is using for its navigation system.

----

.. _class_NavigationObstacle_method_set_navigation:

- void **set_navigation** **(** :ref:`Node<class_Node>` navigation **)**

Sets the :ref:`Navigation<class_Navigation>` node used by the obstacle. Useful when you don't want to make the obstacle a child of a :ref:`Navigation<class_Navigation>` node.

