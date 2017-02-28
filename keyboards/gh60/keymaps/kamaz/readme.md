
```bash
lsusb | grep Atmel
```

```bash
sudo dfu-programmer atmega32u4 erase
```

```bash
sudo dfu-programmer atmega32u4 flash ../../.build/gh60_kamaz.hex
```
