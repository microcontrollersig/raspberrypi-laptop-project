# Linux Testing

Based on https://wiki.debian.org/SynapticsTouchpad

```sh
egrep -i 'synap|alps|etps|elan' /proc/bus/input/devices
```

```sh
cat /proc/bus/input/devices | grep -I touchpad
```

Package **xserver-xorg-input-libinput** is installed by default.

Old package is not installed **xserver-xorg-input-synaptics**

Try

```sh
evtest
```

or

```sh
xinput list
```

```sh
xinput set-prop "SynPS/2 Synaptics TouchPad" "Device Enabled" 0
```

```sh
xinput set-prop "SynPS/2 Synaptics TouchPad" "Device Enabled" 1
```



## Testing

https://unix.stackexchange.com/questions/388963/how-can-i-enable-disable-the-synaptics-touchpad-in-debian-9-with-libinput
