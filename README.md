# Cooler Master Novatouch Daughterboard USB-C
USB-C Daughterboard for Cooler Master Novatouch. Fits in the stock case without any changes.  Also fits Norbatouch, Masterkeys Pro S & Rapid-i.

![PCB2](/assets/pcbFrontBack.jpg)

## Disclaimers
* Norbatouch compatible if using 2 m3 nuts as washers.
* Use at your own risk
* This will only give USB-C connection for the keyboard. Programmability requires a custom full PCB.

# Cable
* JST SH to PH cable
* 5 pin
* 150mm long
* Good start cable
  * https://www.aliexpress.us/item/3256804552474270.html
  * "Same Direction" so only 2 wires need to be swapped after receiving. Plug in SH (small end) first. swap the D- and D+ wire on the PH end.
  * See pinout diagram
    
## Novatouch Pinout  
![Cable](/assets/CablePinout.jpg)
![Novatouch](/assets/novatouchcable.JPG)

## Masterkeys Pro S Pinout
![CablePros](/assets/masterkeysprosrapidIPinout2.png)
![ProS](/assets/proSrapidIcable.JPG)

## Rapid-i Pinout


# Recommended Hardware

* M2 x 4mm wafer head screw/laptop screw. For mounting CMDB into stock Novatouch case. https://www.aliexpress.us/item/3256801240948974.html 
* M3 x 0.5mm 6mm hex screw, 3mm hex nut. For mounting CMDB into Norbatouch. Add o-ring or washer if still sitting too low in port opening. 

# Installation Photos

<details>
 <summary>Stock Novatouch</summary>
 
![PCBInstalled](/assets/pcbInstalled.jpg) ![PCBInstalled2](/assets/pcbInstalled2.jpg)

</details>

<details>
 <summary>Norbatouch PC</summary>

![mountedinnorbatouch](/assets/mountedinnorbatouch.png) ![norbatouchpcportview](/assets/norbatouchpcportview.png) ![withm3nuts](/assets/withm3nuts.png)

</details>

<details>
 <summary>Norbatouch Aluminum </summary>
 
![norbatouch_alu_portview](/assets/norbatouch_alu_portview.jpeg)
 
</details>

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
* PixelPusher for validating compatibility in Novatouch, Masterkeys Pro S & Rapid-i.
