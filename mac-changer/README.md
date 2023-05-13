# A Simple MAC Address changer

## Description
This program is a simple mac address changer. It works in the terminal, preferably linux.

## Technologies
* Python

## Setup
1. Run the following in the terminal:
```
ifconfig
```
The results at the ether interface is the mac address.

2. Change file permissions:
```
chmod +x mac-changer.py
```

3. Enter your new mac address in the format "AB:CD:EF:GH:IJ:KL" (but replace them with numbers and letters):
```
./mac-changer.py -i eth0 -m <new-mac-address>
```
or
```
./mac-changer.py --interface eth0 --mac <new-mac-address>



