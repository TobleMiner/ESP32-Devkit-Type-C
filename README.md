ESP32 Devkit Type C
===================

**DISCLAIMER: I've not tested this design yet**

This PCB is a USB Type C enabled ESP32 development board. It is pin-compatible
with the ESP32 Devkit C but sports a slightly decreased width to fit on a
standard breadboard.

# Features

* USB Type C
* pin-compatible with ESP32 Devkit
* fits on standard breadboard
* onboard antenna

Furthermore this board is optimized for JLCPCB assembly, a Chinese SMT PCB
assembly service. All components on this board, except the USB Type C connector,
the push buttons and the pin headers can be assembled by them for around ~$8
including PCB manufacturing and components.

![Devkit on breadboard](/resources/revB_breadboard.png)

# Assembly

There is an
[interactive HTML BOM](https://tobleminer.github.io/ESP32-Devkit-Type-C/ibom.html)
to help you assemble the board.

Assuming you are using JLCPCB SMT assembly you will need to populate just the
following parts by hand:

| Reference  | Description            | LCSC                                                                                                                  |
|------------|------------------------|-----------------------------------------------------------------------------------------------------------------------|
| J1         | USB Type C connector   | [C167321](https://lcsc.com/product-detail/USB-Connectors_Jing-Extension-of-the-Electronic-Co-C167321_C167321.html)    |
| SW1, SW2   | RESET/BOOT push button | [C115357](https://lcsc.com/product-detail/Tactile-Switches_ALPS_SKRKAEE020_3-4-2-1-57N_C115357.html)    |
| J2, J3     | Pin headers            | [C2337](https://lcsc.com/product-detail/Pin-Header-Female-Header_BOOMELE-Boom-Precision-Elec-2-54mm-1x40P_C2337.html) |
