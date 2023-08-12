# Cooler Master Novatouch Daughterboard USB-C
USB-C Daughterboard for Cooler Master Novatouch. Fits in the stock case without any changes.  

![PCB2](/assets/pcbFrontBack.jpg)
![PCBInstalled](/assets/pcbInstalled.jpg)
![PCBInstalled2](/assets/pcbInstalled2.jpg)

## Disclaimers
* Norbatouch compatible if using 2 m3 nuts as washers.
* Might work with other Cooler Master boards that use USB-Micro and the same daughterboard
* Use at your own risk
* This will only give USB-C connection for the keyboard. Programmability requires a full, custom PCB.

# Cable
* JST SH to PH cable
* 5 pin
* 150mm long
* Good start cable
  * https://www.aliexpress.us/item/3256804552474270.html
  * "Same Direction" so only 2 wires need to be swapped after receiving
  * See pinout diagram

 
## Novatouch Pinout
![Cable](/assets/CablePinout.jpg) 
![Cable](/assets/Cablev2.jpg)
!(/assets/novatouchcable.jpg)

## Masterkeys Pro S / Rapid-i Pinout
diagrams tbd
!(/assets/proSrapidIcable.jpg)

# Revisions
* 1.1 Lets not dwell on version 1.1 other than it paved the way for version 1.2 :)
* 1.2 Worked successfully with Novatouch and Norbatouch
* 1.3 Updated design to include extra size for manufacturing along with a dummy resistor on the backside
* 1.4 Removed extra rails manufacturing because they wanted to charge extra claiming 2 designs in one file

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
* [Nekotato](/https://github.com/nekotato) for validating compatibility and requesting this
* [Gouty](/https://github.com/Gouty) for initial measurements from repo: https://github.com/Gouty/CM-Keyboard_USB-Breakout
