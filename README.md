# raspberrypi-laptop-project
Embed a raspberry pi in an old laptop, DIY version of PiTop

# Laptop Used
Asus F3S

### Touchpad

Touchpad Synaptics 920-000241-02 RevA

![Touchpad synaptics](https://github.com/microcontrollersig/raspberrypi-laptop-project/raw/master/touchpad-synaptics-920-000241-02.jpg)

PS/2 signalling used.



T10: clock

T11: data

T23: GND

T22: 5V

[Synaptics Manual](https://github.com/telmich/gpm/blob/master/doc/specs/synaptics/www.synaptics.com/decaf/utilities/ACF126.pdf)

###### Key Facts from Synaptics Manual 

SECTION 3.1
![PS/2 System diagram](https://github.com/microcontrollersig/raspberrypi-laptop-project/blob/master/ps2systemdiagram.png)

![PS/2 Cable Pinout](https://github.com/microcontrollersig/raspberrypi-laptop-project/raw/master/ps2cablepinout.png)

![PS/2 ultra thin connector](https://github.com/microcontrollersig/raspberrypi-laptop-project/raw/master/ps2ultrathinconnector.png)

![PS/2 submini connector](https://github.com/microcontrollersig/raspberrypi-laptop-project/blob/master/ps2subminiconnector.png)

![PS/2 Mini Module Connector](https://github.com/microcontrollersig/raspberrypi-laptop-project/blob/master/ps2minimoduleconnector.png)

### Checklist

###### TOUCHPAD

- [x] Identify test points that correspond to 5v, GND, clock and data
- [x] Read clock T10 on oscilloscope and observe square wave
- [ ] Write an Arduino sketch and observe movements (try https://github.com/kristopher/PS2-Mouse-Arduino or variant)
- [ ] Hook touchpad to a ** PS/2(female) to USB adapter ** to a Linux machine and see if touchpad is identified
