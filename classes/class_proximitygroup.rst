.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the ProximityGroup.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_ProximityGroup:

ProximityGroup
==============

**Inherits:** :ref:`Spatial<class_spatial>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

General purpose proximity-detection node.

Member Functions
----------------

+-------+-----------------------------------------------------------------------------------------------------------------------------------------+
| void  | :ref:`broadcast<class_ProximityGroup_broadcast>` **(** :ref:`String<class_string>` name, :ref:`Variant<class_variant>` parameters **)** |
+-------+-----------------------------------------------------------------------------------------------------------------------------------------+

Signals
-------

.. _class_ProximityGroup_broadcast:

- **broadcast** **(** :ref:`String<class_string>` name, :ref:`Array<class_array>` parameters **)**


Member Variables
----------------

  .. _class_ProximityGroup_dispatch_mode:

- :ref:`DispatchMode<enum_proximitygroup_dispatchmode>` **dispatch_mode**

  .. _class_ProximityGroup_grid_radius:

- :ref:`Vector3<class_vector3>` **grid_radius**

  .. _class_ProximityGroup_group_name:

- :ref:`String<class_string>` **group_name**


Enums
-----

  .. _enum_ProximityGroup_DispatchMode:

enum **DispatchMode**

- **MODE_PROXY** = **0**
- **MODE_SIGNAL** = **1**


Description
-----------

General purpose proximity-detection node.

Member Function Description
---------------------------

.. _class_ProximityGroup_broadcast:

- void **broadcast** **(** :ref:`String<class_string>` name, :ref:`Variant<class_variant>` parameters **)**


