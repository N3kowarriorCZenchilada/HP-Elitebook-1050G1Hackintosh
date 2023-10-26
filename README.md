# HP-Elitebook-1050G1Hackintosh
HP Elitebook 1050G1Hackintosh based on Opencore 0.9.5
>Replace your nvme with nvme sata ssd, or look for compatible one with sucesfull installation.
<p>&nbsp;</p>
<p>&nbsp;</p>
Before Installation
(Dont forget to hide TMP chip and disable legacy + SecureBoot in your bios.)
<p>&nbsp;</p>
1: Use SSDTTime to **generate device specific aspci** /Just replace mine

2: **Generate your own SMBIOS** for **MacBookPro15,2**

3: **Install AirportItlwm.kext** for your macOS version // If you wanna install MacOS I dont have release for.

5: Your hardware may warry: USBToolbx tool to generate **UTBMap.kext** specific to your hardware.

6: After you boot to Opencore, clear NVRAM and reboot your laptop.

7: Start Installation
<p>&nbsp;</p>
<p>&nbsp;</p>
After Installation
<p>&nbsp;</p>
1: Re-enable kexts in config.plist:
>IntelBTPatcher.kext, IntelBluetoothInjector.kext, IntelBluetoothFirmware.kext, HibernationFixup.kext, RealtekCardReader.kext (If I manage to get card reader working)

2: Use tools like: hackintool, Opencore configurator to customize the installation to your needs and hardware specifics.
<p>&nbsp;</p>
<p>&nbsp;</p>
Big Sur
<p>&nbsp;</p>
>**Working:**

>Wifi - Bluetooth - Audio - Igpu - sleep

>**Doesnt work:**

>Camera, sd card port, hdmi, and usbc to hdmi adapter



