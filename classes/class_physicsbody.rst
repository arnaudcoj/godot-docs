.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the PhysicsBody.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_PhysicsBody:

PhysicsBody
===========

**Inherits:** :ref:`CollisionObject<class_collisionobject>` **<** :ref:`Spatial<class_spatial>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Inherited By:** :ref:`RigidBody<class_rigidbody>`, :ref:`VehicleBody<class_vehiclebody>`, :ref:`StaticBody<class_staticbody>`, :ref:`KinematicBody<class_kinematicbody>`

**Category:** Core

Brief Description
-----------------

Base class for all objects affected by physics in 3D space.

Member Functions
----------------

+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`add_collision_exception_with<class_PhysicsBody_add_collision_exception_with>`  **(** :ref:`Node<class_node>` body  **)**                   |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`    | :ref:`get_collision_layer<class_PhysicsBody_get_collision_layer>`  **(** **)** const                                                             |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`  | :ref:`get_collision_layer_bit<class_PhysicsBody_get_collision_layer_bit>`  **(** :ref:`int<class_int>` bit  **)** const                          |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`    | :ref:`get_collision_mask<class_PhysicsBody_get_collision_mask>`  **(** **)** const                                                               |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`  | :ref:`get_collision_mask_bit<class_PhysicsBody_get_collision_mask_bit>`  **(** :ref:`int<class_int>` bit  **)** const                            |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`remove_collision_exception_with<class_PhysicsBody_remove_collision_exception_with>`  **(** :ref:`Node<class_node>` body  **)**             |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_collision_layer<class_PhysicsBody_set_collision_layer>`  **(** :ref:`int<class_int>` layer  **)**                                      |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_collision_layer_bit<class_PhysicsBody_set_collision_layer_bit>`  **(** :ref:`int<class_int>` bit, :ref:`bool<class_bool>` value  **)** |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_collision_mask<class_PhysicsBody_set_collision_mask>`  **(** :ref:`int<class_int>` mask  **)**                                         |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| void                     | :ref:`set_collision_mask_bit<class_PhysicsBody_set_collision_mask_bit>`  **(** :ref:`int<class_int>` bit, :ref:`bool<class_bool>` value  **)**   |
+--------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

- :ref:`int<class_int>` **collision_layer** - The physics layers this area is in.
			Collidable objects can exist in any of 32 different layers. These layers work like a tagging system, and are not visual. A collidable can use these layers to select with which objects it can collide, using the collision_mask property.
			A contact is detected if object A is in any of the layers that object B scans, or object B is in any layer scanned by object A.
- :ref:`int<class_int>` **collision_mask** - The physics layers this area can scan for collisions.

Description
-----------

PhysicsBody is an abstract base class for implementing a physics body. All \*Body types inherit from it.

Member Function Description
---------------------------

.. _class_PhysicsBody_add_collision_exception_with:

- void  **add_collision_exception_with**  **(** :ref:`Node<class_node>` body  **)**

Adds a body to the list of bodies that this body can't collide with.

.. _class_PhysicsBody_get_collision_layer:

- :ref:`int<class_int>`  **get_collision_layer**  **(** **)** const

.. _class_PhysicsBody_get_collision_layer_bit:

- :ref:`bool<class_bool>`  **get_collision_layer_bit**  **(** :ref:`int<class_int>` bit  **)** const

.. _class_PhysicsBody_get_collision_mask:

- :ref:`int<class_int>`  **get_collision_mask**  **(** **)** const

.. _class_PhysicsBody_get_collision_mask_bit:

- :ref:`bool<class_bool>`  **get_collision_mask_bit**  **(** :ref:`int<class_int>` bit  **)** const

.. _class_PhysicsBody_remove_collision_exception_with:

- void  **remove_collision_exception_with**  **(** :ref:`Node<class_node>` body  **)**

Removes a body from the list of bodies that this body can't collide with.

.. _class_PhysicsBody_set_collision_layer:

- void  **set_collision_layer**  **(** :ref:`int<class_int>` layer  **)**

.. _class_PhysicsBody_set_collision_layer_bit:

- void  **set_collision_layer_bit**  **(** :ref:`int<class_int>` bit, :ref:`bool<class_bool>` value  **)**

.. _class_PhysicsBody_set_collision_mask:

- void  **set_collision_mask**  **(** :ref:`int<class_int>` mask  **)**

.. _class_PhysicsBody_set_collision_mask_bit:

- void  **set_collision_mask_bit**  **(** :ref:`int<class_int>` bit, :ref:`bool<class_bool>` value  **)**


