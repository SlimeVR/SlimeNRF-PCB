## notes

You need a segger jlink programmer to use this, USB dfu does not come with the initial bootloader of isp, and nrf52832 has no USB connectivity. nRF52840-dk development kit can be used, and also can double as a dongle for the trackers.

# slimenrfaux

Revision 1

isp1807-lr (nrf52840), icm42688 or compatible, mmc5983ma

* USB untested
* Charger is hard to solder
* LED with default resistor is too dim

pcb|3d
--|--
![pcb](../../blob/main/images/slimenrfaux.png)|![3d](../../blob/main/images/slimenrfaux_3d.png)

# slimenrfaux2

Revision 2

isp1507-ax (nrf52832), icm42688 or compatible, mmc5983ma

* Untested

pcb|3d
--|--
![pcb](../../blob/main/images/slimenrfaux2.png)|![3d](../../blob/main/images/slimenrfaux2_3d.png)

# slimenrfdock

dock test pcb

charging for 8 devices at 300mA, max power draw 2.4A

* Untested

pcb|3d
--|--
![pcb](../../blob/main/images/slimenrfdock.png)|![3d](../../blob/main/images/slimenrfdock_3d.png)
