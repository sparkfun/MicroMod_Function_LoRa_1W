SparkFun MicroMod LoRa Function Board
========================================

[![SparkFun MicroMod LoRa Function Board](https://cdn.sparkfun.com/assets/parts/1/8/0/4/0/18573-SparkFun_MicroMod_LoRa_Function_Board-01.jpg)](https://www.sparkfun.com/products/18573)

[*SparkFun MicroMod LoRa Function Board (DEV-18573)*](https://www.sparkfun.com/products/18573)

The SparkFun MicroMod LoRa Function Board provides LoRA and LoRaWAN capabilities to your MicroMod project. It is intended to be used in conjunction with a MicroMod Processor Board and a MicroMod Main Board, which provides the electrical interface between a processor board and the Function Board(s).

The LoRa Function Board utilizes the 915M30S LoRa module from EBYTE, which is a 1W (30dBm) transceiver based around the SX1276 from Semtech. There is a robust edge mount RP-SMA connector for large LoRa (915MHz) antennas; with modification, a U.FL connector is also available. We've successfully tested a 12 miles line-of-sight transmission with this module (test was performed under ideal conditions; individual user results may vary).

With the MicroMod standardization, users no longer need to cross-reference schematics with datasheets, while fumbling around with jumper wires. Simply, match up the function board's M.2 edge connector to the slot of the M.2 connector on the main board and secure the function board with screws.


Repository Contents
-------------------

* **/Firmware** - Arduino example code from the tutorial
* **/Hardware** - Eagle design files (.brd, .sch)
* **/Hardware/Production** - Production panel files (.brd)

Documentation
--------------

* **[E19-915M30S Datasheet](https://github.com/sparkfun/MicroMod_Function_LoRa_1W/blob/main/Documents/E19-915M30S_Usermanual_EN_v1.20.pdf)** - Datasheet for the LoRa module
  * **[SX1276 Datasheet](https://cdn.sparkfun.com/assets/7/7/3/2/2/SX1276_Datasheet.pdf)** - Datasheet for the transceiver the LoRa module is based on
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/1996)** - Basic hookup guide
* **[SparkFun External EEPROM Arduino Library](https://github.com/sparkfun/SparkFun_External_EEPROM_Arduino_Library)** - Arduino library for the EEPROM
* **[RadioLib Arduino Library](https://github.com/jgromes/RadioLib)** - Arduino library for peer-to-peer communication with the LoRa module

Product Versions
----------------

* [DEV-18573](https://www.sparkfun.com/products/18573)- Initial release


Version History
---------------

* v1.0 - Initial Release


License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_<COLLABORATION CREDIT>_
