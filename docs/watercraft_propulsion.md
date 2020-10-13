WatercraftPropulsion
====================

Brief Description
-----------------

Adds a propulsion system to a `HydroRigidBody`
Properties
----------

Vector3 direction

Vector3 origin

float   value

Description
-----------

This can be used to add prop or jet drives, bow thrusters, or more to a `HydroRigidBody` -based watercraft.  The propulsion system will only provide thrust when its origin is underwater.

Property Descriptions
---------------------

* Vector3 **direction**

The direction that the propulsion system will push the watercraft.

* Vector3 **origin**

The location of the propulsion system.

* float **value**

The amount of thrust applied by the propulsion system.