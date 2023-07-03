# Cooler Master Novatouch Daughterboard USB-C
USB-C Daughterboard for Cooler Master Novatouch. (Might work with other Cooler Master boards)
![PCB2](/assets/pcbFrontBack.jpg)
TOOD: Photo Installed

# Cable
* JST SH to PH cable
* 5 pin
* 150mm long
* **Same direction**
* https://www.aliexpress.us/item/3256804552474270.html
![Cable](/assets/Cable.jpg) 

# Manufacturing
<details>
  <summary>JLCPCB</summary>
 
  * [/manufacturing](/manufacturing)
  * **Must be 1mm thick** (NOT Standard 1.6mm)
  * SMD Assembly is **Standard** not economic due to USB connector
  * Confirm Parts Placement: **Yes**
</details>
<details>
  <summary>BOM</summary>

| LCSC part # | Description        | Value | Package  | Amount |
| ----------- | ------------------ | ----- | -------- | ------ |
| C67381      | Connector (USB)    |       | SMD      | 1      |
| C136657     | Connector(JST SH)  | 5 pin | TH       | 1      |
| C7519       | ESD                |       | SOT23-6  | 1      |
| C261942     | Fuse               |       | 0805     | 1      |
| C597300     | Capacitor          | 4.7nF | 0805     | 1      |
| C212411     | Resistor           | 5.1K  | 0805     | 1      |
</details>

# Thanks
* Thanks for https://github.com/nekotato for requesting this
* https://github.com/Gouty for initial measurements from repo: https://github.com/Gouty/CM-Keyboard_USB-Breakout
