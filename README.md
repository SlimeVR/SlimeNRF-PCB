## notes

You need a segger jlink programmer to use this, USB dfu does not come with the initial bootloader of isp, and nrf52832 has no USB connectivity. nRF52840-dk development kit can be used, and also can double as a dongle for the trackers.

# slimenrf r3

Revision 3

E73-2G4M08S1C (nrf52840), icm42688 or compatible, mmc5983ma

https://oshwlab.com/sctanf/slimenrf3

# slimenrfaux2

Revision 2

isp1507-ax (nrf52832), icm42688 or compatible, mmc5983ma

* Uses nrf52832, no USB, SWD pins on dock connector instead
* No 0201 parts
* Removed onboard charger
* LED is brighter (sink instead of source)

pcb|3d
--|--
![pcb](../../blob/main/images/slimenrfaux2.png)|![3d](../../blob/main/images/slimenrfaux2_3d.png)

pcb before reflow|pcb with battery|tracker and case (![slimenrf_2.stl](../../blob/main/slimecase/slimenrf_2.stl))
--|--|--
![pcb before reflow](../../blob/main/images/IMG_20230423_154530.webp)|![pcb with battery](../../blob/main/images/IMG_20230422_233642.webp)|![tracker and case](../../blob/main/images/DSC_0067.webp)

# slimenrfauxaux2

Revision 2

icm42688 or compatible, mmc5983ma

pcb|3d
--|--
![pcb](../../blob/main/images/slimenrfauxaux2.png)|![3d](../../blob/main/images/slimenrfauxaux2_3d.png)

# slimenrfaux

Revision 1

isp1807-lr (nrf52840), icm42688 or compatible, mmc5983ma

* USB untested
* 0201 components are hard to solder
* Charger is hard to solder
* LED with default resistor is too dim

pcb|3d
--|--
![pcb](../../blob/main/images/slimenrfaux.png)|![3d](../../blob/main/images/slimenrfaux_3d.png)

finished pcb|pcb with battery|completed tracker (case: ![slimenrf_2_closed.stl](../../blob/main/slimecase/slimenrf_2_closed.stl))
--|--|--
![finished pcb](../../blob/main/images/IMG_20230327_203040.webp)|![pcb with battery](../../blob/main/images/IMG_20230402_175121.webp)|![completed tracker](../../blob/main/images/DSC_0383.webp)

# slimenrfauxaux

Revision 1

icm42688 or compatible, mmc5983ma

* 0201 components are hard to solder

pcb|3d
--|--
![pcb](../../blob/main/images/slimenrfauxaux.png)|![3d](../../blob/main/images/slimenrfauxaux_3d.png)

# slimenrfdock

dock test pcb

charging for 8 devices at 300mA, max power draw 2.4A

* Gets pretty hot if all 8 chargers are in use but it works fine

pcb|3d
--|--
![pcb](../../blob/main/images/slimenrfdock.png)|![3d](../../blob/main/images/slimenrfdock_3d.png)

completed charger pcb|charging dock (![slimenrfdock_2_6x_3pin.stl](../../blob/main/slimecase/slimenrfdock_2_6x_3pin.stl))
--|--
![completed charger pcb](../../blob/main/images/IMG_20230421_180853.webp)|![charging dock](../../blob/main/images/IMG_20230409_022839.webp)
