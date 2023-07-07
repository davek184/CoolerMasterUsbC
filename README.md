# Cooler Master Novatouch Daughterboard USB-C
USB-C Daughterboard for Cooler Master Novatouch. Fits in the stock case without any changes.  

![PCB2](/assets/pcbFrontBack.jpg)
![PCBInstalled](/assets/pcbInstalled.jpg)
![PCBInstalled2](/assets/pcbInstalled2.jpg)

## Disclaimers
* Norbatouch unknown if compatible.  (Should but cannot say for sure)
* Might work with other Cooler Master boards that use USB-Micro and the same daughterboard
* Use at your own risk

# Cable
* JST SH to PH cable
* 5 pin
* 150mm long
* Good start cable https://www.aliexpress.us/item/3256804552474270.html (pinnout needs to be custom though see below)
* Custom Pinout
  
![Cable](/assets/CablePinout.jpg) 
![Cable](/assets/Cablev2.jpg)


# Manufacturing
<details>
  <summary>JLCPCB</summary>
 
  * Files: [/manufacturing](/manufacturing)
  * **1mm thick** (NOT Standard 1.6mm)
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

# Acknowledgments 
* https://github.com/nekotato for validating compatibility and requesting this
* https://github.com/Gouty for initial measurements from repo: https://github.com/Gouty/CM-Keyboard_USB-Breakout
