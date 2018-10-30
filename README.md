### xps-9570 hackintosh mojave


### preview

![system](./system.png)
![setting](./setting.png)
![power](./power.png)
![graphic](./graphic.png)
![usb](./usb.png)


### Device

	uhd display
	8750h
	dw1830
	16GB Ram

use the install efi to install Mac OS Majave(10.14) and boot into the system

then replace the EFI folder rebuild kextcache.(you may reboot severl times)

#### Working

	Intel Graphics accelleration(uhd630)
	wifi & bluetooth (dw1830)
	Audio
	brightlight control
	...

#### Not Working

	hdmi port
	sleep
    ...
	
	
	
ps: 

I have swipe the capslock and left ctrl,
replace a `VoodooPS2Controller.kext` can restore

	

