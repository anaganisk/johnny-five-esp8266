# Homebot (A simple example to control arduino using johhny-five over WiFi using ESP8266)
## Under development

### *important commands*
```bash
python esptool.py --port /dev/ttyUSB0 erase_flash
python esptool.py -p /dev/ttyUSB0 write_flash 0x00000 0x00000.bin 0x40000 0x40000.bin
```
### Defaults
* baud rate 57600
* host localhost
* port 41234
