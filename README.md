# raspberrypi-laptop-project
Embed a raspberry pi in an old laptop, DIY version of PiTop

# Laptop Used
Asus F3S

### Touchpad

Touchpad Synaptics 920-000241-02 RevA

T10: clock

T11: data

T23: GND

T22: 5V



### PS/2 connector


### Checklist

###### TOUCHPAD

- [x] Identify test points that correspond to 5v, GND, clock and data
- [x] Read clock T10 on oscilloscope and observe square wave
- [] Write an Arduino sketch and observe movements (try https://github.com/kristopher/PS2-Mouse-Arduino or variant)
- [] Hook touchpad to a ** PS/2(female) to USB adapter ** to a Linux machine and see if touchpad is identified
