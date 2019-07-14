# Linux Testing

Based on https://wiki.debian.org/SynapticsTouchpad

```sh
egrep -i 'synap|alps|etps|elan' /proc/bus/input/devices
```

Package **xserver-xorg-input-libinput** is installed by default.

Old package is not installed **xserver-xorg-input-synaptics**
