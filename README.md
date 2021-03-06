# resin-heater
A Project to warm the resin in an SLA 3d printer. 

12v Resin Vat Heater
====================
Reason:
-------

Formlabs heats the resin on their high end SLA resin printers.  It is known that most resins print faster when warm, and some not at all when cold.

Parts:
------
DC 12V Programmable Heating/Cooling Thermostat
https://smile.amazon.com/gp/product/B07K68JJY1

12V 7W Flexible Polyimide Heater Plate Adhesive PI Heating Film 25mmx50mm
https://smile.amazon.com/gp/product/B07P2RJDPL

Panel mount 5.5 mm x 2.1mm 30V 10A DC Power Jack
https://smile.amazon.com/gp/product/B07C46XMP

Multi pin water tight connector
https://smile.amazon.com/gp/product/B01LCV8ZMA

Assembly:
---------

To be covered in another doc, or left to the reader.

Result:
-------
Keeping the temps at ~85f has seen more consistent printing. No failed prints since install, and possibly better aging of the FEP film. (lower viscosity resulting in less release stretch?) This method is likely more power efficient than the space heater designs seen elsewhere as the two heaters combined draw ~1a @ 12v. It also adds less heat to the surrounding room, important on hot summer days. 

Testing:
--------

Tests will be done at room temp ~70f/21c and with the resin heater on at ~90f/32c.  The target printer is an Anycubic Photon, so I will use the photon-resin-calibration tests found here: https://github.com/altLab/photon-resin-calibration
