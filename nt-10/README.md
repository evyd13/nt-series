# nt-10 daughterboard for Leopold keyboards

The nt-10 is a USB-C daughterboard designed to fit the Leopold range of keyboards.  
At the time of writing those are the:

- FC750r
- FC980m
- FC900r

## Installation

Upon removal of the old (probably Mini USB) daughterboard, carefully insert the nt-10 and make sure the USB-C connector fits the cutout in the case. If it does not fit, you can use a small file to increase the cutout size.

### Wiring

The wiring is as follows:

![Wiring of nt-10 daughterboard for Leopold keyboard](https://i.imgur.com/i2P6aoP.png)

You might have to swap the wires on some boards, I had to on the 980m. Lift up the tabs using tweezers or a small knife (don't hurt yourself!) and take out the wires, then press the tabs back down and insert the wires in the correct order.

## BOM

| LCSC part # | Description   | Value | Package  | Amount |
| ----------- | ------------- | ----- | -------- | ------:|
| C27834      | Resistor      | 5.1k  | 0805     | 2      |
| C261942     | Fuse          |       | 0805     | 1      |
| C7519       | ESD prot.     |       | SOT32-6  | 1      |
| C165948     | USB-C conn.   |       |          | 1      |
| C160404     | JST SH 1x4    |       |          | 1      |
| C392176     | PicoBlade 1x5 |       |          | 1      |

Use at your own risk.
