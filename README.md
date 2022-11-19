# HP-x360-14-KabyLake-8250U-Hackintosh-BigSur

Please change the SMBIOS before using this EFI. Use Dortania OpenCore tutorial for that.

HP Pavilion x360 14
macOS BigSur 11.7
OpenCore 0.8.5

Specification:
---------------
- Intel Core i5 8250U (KabyLake R) with Intel UHD620 Graphics
- 16GB DDR4 2400MHZ Dual Channel
- 128GB M2 SATA SSD
- 1TB HDD SATA3
- 14" 1920x1080p IPS Touchscreen
- Wireless card: Intel 7265AC (I swapped the Realtek card)

Whats working:
------------
- CPU PowerManagement
- GPU and Graphics Acceleration
- Battery percentage
- Short sleep
- Restart
- Trackpad
- Audio
- WIFI and BT using Airportitlwm
- Apple Service including Facetime and iMessage
- All USB Port (2 Type A 3.1, 1 TypeC 3.1)
- All buttons and keyboard shortcut including the side volume

Not working:
------------
- Features that required Apple native wireless card
- Long sleep
- Shutdown (The machine won't turn off but the OS is already shut down, long press the power button for truly shutdown the machine)
- Touchscreen

Not tested yet:
---------
- HDMI Port
- SDCard slot

Feel free to fix the problem if you want and let me know.
