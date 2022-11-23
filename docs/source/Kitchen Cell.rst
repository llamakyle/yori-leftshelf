Kitchen Cell
============

.. _Left Shelf:

Left Shelf
----------

The left shelf houses the majority of the modified kitchen appliances including the :ref:`Salamander-Broiler` (for high temperature short duration cooking), the :ref:`Convection-Oven` (for general baking operations), the :ref:`Pasta-Cooker` (for boiling water, cooking and steaming), and the :ref:`Deep-Fryer` (for frying).

.. _Salamander-Broiler:
Salamander Broiler
^^^^^^^^^^^^^^^^^^
**General Info**

*Max Temp: 200C Min Temp: 24C

**Key Frames:**

.. csv-table:: Appliance Key Frames
   :header: "Frame ID", "X (mm)", "Y (mm)", Z (mm)
   :widths: 30, 15, 15, 15

   "Upper Shelf Inserted", 100, 100, 100
   "Upper Shelf Removed", 100, 100, 100
   "Lower Shelf Inserted", 100, 100, 100
   "Lower Shelf Removed", 100, 100, 100
   
**Modifications:**

*Replaced external knobs with servo motors to control electrical functions.
*Implanted K-Type thermocouple to top heating element
*Replaced internal shelving with more easily navigable ones.

**Setup:**

*Mounted to the shelf via an angle bracket mounted beneath the device.
*The ventilation hood is mounted via screws to the top of the salamander broiler.
 
**Future Work?:**

*May be useful to replace shelves with a rising platform for more control over cooking.
   *Modifying a small aluminum scissor lift with a motor would be a fairly straightforward solution.
*Making the ventilation mount system more robust (ie. having more specific screw holes rather than the vent it currently uses).
   *If sticking with shelves, replace plastic ones with modified aluminum brackets.



Convection-Oven
^^^^^^^^^^^^^^^
**General Info**

*Max Temp: 450C Min Temp: 24C

**Key Frames:**

.. csv-table:: Appliance Key Frames
   :header: "Frame ID", "X (mm)", "Y (mm)", Z (mm)
   :widths: 30, 15, 15, 15

   "Door Closed", 100, 100, 100
   "Door Opened", 100, 100, 100
   "Pan Inserted", 100, 100, 100
   "Pan Removed", 100, 100, 100
   
**Modifications:**

*Replaced external knobs with analog solid state relay to control heating element and fan.
*Implanted K-Type thermocouple into the cooking chamber.
*Attached rotating tool plate for door manipulation.

**Setup:**

*Mounted to the shelf via an angle bracket mounted beneath the device.
*The ventilation hood is mounted via screws drilled into the top of the oven.
 
**Future Work?:**

*Rotating tool plate will need to be finalized.
   *Modifying for proper april tag placement.
   *Adding magnets and guides for consitant alignment.
*Add internal metal alignment guides for pan insertion.
   *May also incorporate some form of temperature sensing to measure pan temperature.
   
   
.. _Pasta-Cooker:   
Pasta Cooker
^^^^^^^^^^^^
**General Info**

*Max Temp: 100C Min Temp: 24C
   *Machine temperatures are in F
*Requires timer to be on, so will always load a full timer when starting
*Goes to sleep if left idle for too long, so may need to implement a work around.

**Key Frames:**

.. csv-table:: Appliance Key Frames
   :header: "Frame ID", "X (mm)", "Y (mm)", Z (mm)
   :widths: 30, 15, 15, 15

   "Basket Inserted", 100, 100, 100
   "Basket Removed", 100, 100, 100
   "Basket Hanging", 100, 100, 100
   "Basket pre-Insert", 100, 100, 100
   
**Modifications:**

*Replaced external knobs with digital solid state relay for control of heating element.
*Implanted K-Type thermocouple inserted into water chamber.
*Added guides to help the alignment of inserted basket.

**Setup:**

*Mounted to the shelf via an 8020 beam  screwed into the back face of the appliance.
*The ventilation hood is mounted above and behind the appliance.

 
**Future Work?:**

*Replace current plastic guides with metal ones.
   *May need to be modified slightly for machinability and to include fluid pumping.
*Possibly replace the fume hood mounting wih one that can be lowered over the water tank for steaming
   *Simple raising and lowering would work though  consideration for condensation and cleanliness may be needed.
*Implement fluid replacement system
   *Perastaltic pump for filling and solenoid valve for drainage
   
   
.. _Deep-Fryer:   
Deep Fryer
^^^^^^^^^^
**Key Frames:**

.. csv-table:: Appliance Key Frames
   :header: "Frame ID", "X (mm)", "Y (mm)", Z (mm)
   :widths: 30, 15, 15, 15

   "Basket Inserted", 100, 100, 100
   "Basket Removed", 100, 100, 100
   "Basket Hanging", 100, 100, 100
   "Basket pre-Insert", 100, 100, 100
   
**Modifications:**

*Replaced external knobs with digital solid state relay for control of heating element.
*Implanted K-Type thermocouple inserted into oil chamber.
*Added guides to help the alignment of inserted basket.

**Setup:**

*Mounted to the shelf via an 8020 beam screwed into the back face of the appliance.
*The ventilation hood is mounted above and behind the appliance.

 
**Future Work?:**

*Replace current plastic guides with metal ones.
   *May need to be modified slightly for machinability and to include fluid pumping.
*Implement fluid replacement system
   *Perastaltic pump for filling and solenoid valve for drainage

**Shelf Hardware**
^^^^^^^^^^^^^^^^^^
**Key Frames:**

.. csv-table:: Appliance Key Frames
   :header: "Frame ID", "X (mm)", "Y (mm)", Z (mm)
   :widths: 30, 15, 15, 15

   "Origin", 100, 100, 100

**Setup:**

*Can be divided into its two shelves and two sides for flat shipping.

 
**Future Work?:**

*Make some physical connection to the main body of YORI for easier alignment.
   *Can also be helpful for cable and fluid management.
*Make a propper mounting system for the electrical components
*If possible maybe make or find quick connect system to replace some angle brackets.

**Exhaust System**
^^^^^^^^^^^^^^^^^^

**Setup:**

*Series of standard connectors between duct elements.
*Hand tighten hose clamps to connect the components.

 
**Future Work?:**

*Make an attachment point on the shelf.
*Include additional filter to protect the fan from any physcial debris.


.. _Right Shelf:

Right_Shelf
-----------


