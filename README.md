# Only tested with Bullseye!!

## Update your Keyboard Firmware! ( at least PicoCalc_BIOS_v1.2.bin)
https://github.com/clockworkpi/PicoCalc/wiki/Setting-Up-Arduino-Development-for-PicoCalc-keyboard#stm32cubeprogrammer

## What is it?
A LXpanel plugin which displays picocalcbattery status on the panel.
This is written for Raspbian but should work on any Linux using LXpanel.

To install plugin on the Raspberry Pi run either (32 bit)

	sudo cp picocalcbattery.so /usr/lib/arm-linux-gnueabihf/lxpanel/plugins/picocalcbattery.so

For 64 Bit you have to compile it.
    
Either restart or run `lxpanelctl restart` to make LXDE aware it is installed.

# compile
install lxpanel-dev
```
sudo apt install lxpanel-dev
```
execute compile.sh
```
>./compile.sh
```
<img width="630" height="714" alt="Screenshot 2025-10-02 010223" src="https://github.com/user-attachments/assets/698433aa-4c6b-4448-ad94-cb1f17be873b" />
<img width="797" height="670" alt="Screenshot 2025-10-02 010146" src="https://github.com/user-attachments/assets/c78d98fe-d354-4bfb-8bd4-2d9b7abe4169" />
