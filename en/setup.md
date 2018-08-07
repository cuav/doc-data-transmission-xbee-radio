# setup

---

#### Factory matched: {#出厂已配对：}

The factory default is airspeed 200K, interface rate is 57600, peer-to-peer broadcast mode

If you need to modify the configuration, please refer to the software configuration guide. Generally, you only need to modify the VID to achieve the effect of isolation from communication with other modules. For example, if you modify other configurations, familiarize yourself with the documentation and then modify it carefully.

#### Connect with flight controller: {#与飞控连接：}

PixHack: Radio Interface Plugged into Flight Control

Pixhawk: plug into the flight controller's telem1 or telem2 interface

#### Ground station use: {#地面站使用：}

In theory, the ground stations of the PIX are compatible. Please select 57600 baud rate when connecting.

Note whether the driver is installed correctly and whether the port number is selected.

If using a mobile OTG connection, the distance may be short because OTG power is not enough

## Power requirements:

The ground end must ensure that the usb port power supply current is greater than 250MA, and independent power supply is recommended if conditions permit \(some old notebooks/cell phones/tablets may not move\).

### Apply to other systems:

If only the wireless data transmission module is used, please follow the interface definition and the system connection \(RX-TX TX-RX GND-GND\)

The default standard interface rate is 57600. The required interface baud rate can be changed according to the requirements.

### Use the tutorial:

http://doc.cuav.net/tutorial/copter/optional-hardware/radio/usb-xbee.html

