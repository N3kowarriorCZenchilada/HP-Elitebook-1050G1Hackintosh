# HP-Elitebook-1050G1Hackintosh
HP Elitebook 1050G1Hackintosh based on Opencore 0.9.5

>Replace your nvme with nvme sata ssd, or look for compatible one with sucesfull installation.

#**Before Installation** 
Dont forget to hide TMP chip and disable legacy and SecureBoot in your bios.

1: Use SSDTTime to **generate device specific aspci** /Just replace mine

2: **Generate your own SMBIOS** for **MacBookPro15,2**

3: **Disable IntelBluetoothInjector.kext**, **IntelBluetoothFirmware.kext**, **IntelBTPatcher.kext**, **HibernationFixup.kext**  in config.plist

4: **Install AirportItlwm.kext** for your macOS version // or take specific release

5: Your hardware may warry: Use Opencore Configurator, Hackintoool, USBToolbx tool to **customize this EFI folder** to **your** specific **needs**

6: Create folder NVRAM in same directory as EFI folder


#**Working:**
Wifi - Bluetooth - Audio - Igpu - sleep

#**Doesnt work:**
Camera, sd card port, hdmi, and usbc to hdmi adapter

[**AirportItlwm**](https://github.com/OpenIntelWireless/itlwm/releases/)


