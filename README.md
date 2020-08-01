# hackintosh ASUS Vivobook S13 S330FN
Full Efi for Asus Vivobook S13 S330FN. Works on Catalina

![Awesome](https://github.com/deniro98/s330fn/blob/master/screenshot.png?raw=true)

Catalina Works Cool!

# System specification

    1.Name:           Asus Vivobook S13 S330FN-EY039T
    2.CPU:            Intel Core i5-8265U
    3.Graphic:        Intel UHD Graphics 630 2048 MB
    4.Wifi:           Intel Dual Band Wireless-AC 8265 - with bluetooth 
    5.Card Reader:    Realtek_CardReader(RTL8411B_RTS5226_RTS5227)
    6.Camera:         NO :)
    7.Audio:          Conexant Audio CX8050
    8.Touchpad:       ELAN1204
    9.Bios Version:   304

# Step to install

	0. get wired keyboard and mouse
	1. Replace your EFI to this EFI
	2. Install MAC OS
	3. Reboot.
	
	
# Run SIRI on S330FN

	1. Gen True SMBIOS and SN Number with Clover Configurator
	2. Install nullethernet.kext from Rehabman
	3. Reboot

# Know problems

1. [HDMI Reboot](https://github.com/deniro98/s330fn/issues/1]

# What is work?

    All works PERFECTLY!!
    Bluetooth works perfectly, thank's @zxystd
    Best 2G wifi with DWA131
    Touchpad perfect
    Keyboard perfect
    Screen works perfect
    it's really like Macbook PRO!
    
# Wifi Setup

1. Download realise  [itlwm](https://github.com/zxystd/itlwm) 
2. Edit itlwm.kext/Contents/Info.plist
3. set chown root:wheel itlwm.kext
4. set kextload itlwm.kext
