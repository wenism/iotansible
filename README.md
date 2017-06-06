# Ansible meets IOT

## Hardware
| Parts        | Qty           | 
| ------------- |:-------------:|
| [Raspberry Pi 3](http://au.element14.com/buy-raspberry-pi?rd=raspberry+pi+3)|n=5|
| Micro SD Card      | n      | 
| Portable WLAN router | 1     |
| 100MB Switch | 1      |
| Ethernet Cable | n + 1|
| USB to Micro USB cables | n + 1 for WLAN |
| [USB Power Hub](https://www.cablegeek.com.au/shop/power/desktop-chargers/anker-powerport-6-port-60w-usb-charger-au-version/?attribute_pa_colour=black&attribute_pa_packaging-type=premium&gclid=CjwKEAjwpdnJBRC4hcTFtc6fwEkSJABwupNi1fitDS8tOdTiM_sb5RR-esVWkm5S3d-c7vW3M_scjBoCRTfw_wcB) | 1 |
| [Multi Pi Stackable](https://www.modmypi.com/raspberry-pi/cases/multi-pi-stacker/multi-pi-stackable-raspberry-pi-case/) | 3 | 

## Software
- OS for Raspberry PI: Rasbian or HypriotOS
- SDFormatter for formatting your SD card
- Win32 Disk Imager for flashing

## Steps after assembling the hardware:
1. Download ISO (Rasbian or Hypriot)
2. Format SD Card
3. Flash ISO into SD card
4. Boot up and get the MAC address for each pi
5. Reserve IP address for each pi based on MAC address (at your WLAN's console)
6. Prepare your ansible host file
7. Ansible away!
