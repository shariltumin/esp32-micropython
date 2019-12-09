# Micropython firmwares that support esp32.

**LATEST** - The latest firmware is under 20191209 MicroPython v1.11-631-gb76f0a73b-kaki5.
The firmware was compiled without help, web-repl and upip modules.

To flash the firmware.bin follow the steps below:
1. connect GPIO0 to GND
2. press reset or pull out/ push in USB serial adapter
3. run erase.sh, to erase flash memory
4. press reset or pull out/ push in USB serial adapter
5. run flash.sh to upload the firmware.bin to flash memory
6. disconnect GPIO0 from GND

Read [my blog](https://kopimojo.blogspot.com/).

