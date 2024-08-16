# *EFI OC Laptop-Acer-E1-572-6_BR471*
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Gilberto-Mascena/Laptop-Acer-E1-572)
[![license](https://img.shields.io/github/license/Gilberto-Mascena/Laptop-Acer-E1-572)](https://github.com/Gilberto-Mascena/Laptop-Acer-E1-572/blob/main/LICENSE.md)
[![GitHub stars](https://img.shields.io/github/stars/Gilberto-Mascena/Laptop-Acer-E1-572)](https://github.com/Gilberto-Mascena/Laptop-Acer-E1-572/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/Gilberto-Mascena/Laptop-Acer-E1-572)](https://github.com/Gilberto-Mascena/Laptop-Acer-E1-572/issues)
[![tag](https://img.shields.io/github/v/release/Gilberto-Mascena/Laptop-Acer-E1-572)](https://github.com/Gilberto-Mascena/Laptop-Acer-E1-572/releases)
![release-date](https://img.shields.io/github/release-date/Gilberto-Mascena/Laptop-Acer-E1-572)
![size](https://img.shields.io/github/repo-size/Gilberto-Mascena/Laptop-Acer-E1-572)

---

## *Operating systems*

<img align="right" src="./img/banner.png" alt="photo NoteBook Acer" width="330">

<div>
  <img src="./img/macos-big-sur-icon.png" alt="logo macOS Big Sur" width="55">
  <img src="./img/macos-monterey-icon.png" alt="logo macOS Monterey" width="55">
</div>

---

_**My Setup**_

 - _**Notebook**_
   - [*ACER E1-572-6_BR471*](https://www.acer.com/br-pt/support?search=40545129395;NX.MEVAL.019;E1-572&filter=global_download)
 - _**CPU**_
   - *Core I3 4010U*
 - _**GPU**_
   - *Intel HD Graphics 4400*
 - _**Memory**_
   - *2x8GB 16GB*
 - _**SSD Sata**_
   - *Kingston SA400S37 120G SATA3 2.5 SSD*
 - _**Network**_
   - *Broadcom NetXtreme BCM57786*
 - _**WI-FI / Bluetooth**_
   - *Atheros AR9565*       

---

<a name="ancora"></a>
## Navigation
- [*What works*](#ancora1)
- [*Screenshot*](#ancora2)
- [*Kexts used, (all Releases)*](#ancora3)
- [*Recommended tools*](#ancora4)
- [*Intel BIOS Settings*](#ancora5)
- [*Thanks*](#ancora6)
- [*License* ](#ancora7)

---

<a id="ancora1"></a>
## *What works*

- [x] *Video (onbord HDMI).*
- [x] *Sound*
- [x] *Network*
- [x] *WI-FI*
- [X] *Bluetooth*
- [x] *USB*
- [X] *Sleep*

[Top](#ancora)

---

<a id="ancora2"></a>
## *Screenshot* 

![about](./img/about.png)
## *Memory (Upgraded to 16GB)*
![memory](./img/memory.png)
## *Sound*
![sound](./img/sound.png)
## *Network and WI-FI*
![network](./img/network-wi-fi.png)
## *Bluetooth*
![bluetooth](./img/bluetooth.png)
## *Opencore version*
![opencore](./img/opencore-version.png)
## *Hackintool peripherals*
![peripherals](./img/peripherals.png)
## *USB port mapping*
![usb-mapping](./img/USB-mapping.png)

[Top](#ancora)

---

<a id="ancora3"></a>
## *Kexts used, (all Releases)*

- *[`WhateverGreen.kext`](https://github.com/acidanthera/WhateverGreen)*
- *[`Lilu.kext`](https://github.com/acidanthera/Lilu)*
- *[`VirtualSMC`](https://github.com/acidanthera/VirtualSMC), only: `VirtualSMC.kext`, `SMCProcessor.kext`, `SMCBatteryManager.kext` and `SMCSuperIO.kext`*.
- *[`IntelMausi.kext`](https://github.com/acidanthera/IntelMausi)*
- *[`CpuTscSync.kext`](https://github.com/acidanthera/CpuTscSync)*
- *[`CPUFriend`](https://github.com/acidanthera/CPUFriend)*
- *`CPUFriendDataProvider.kext`*
- *[`AppleALC.kext`](https://github.com/acidanthera/AppleALC)*
- *`USBMap.kext`*
- *[`RestrictEvents.kext`](https://github.com/acidanthera/RestrictEvents)*
- *[`VoodooPS2Controller.kext`](https://bitbucket.org/RehabMan/os-x-voodoo-ps2-controller/downloads/)*
- *[`RTCMemoryFixup.kext`](https://github.com/acidanthera/RTCMemoryFixup/releases)*
- *[`AppleBCM57XXEthernet.kext`](https://github.com/unitedastronomer/AppleBCM57XXEthernet/releases/tag/Kext1)*
- *[`AirPortAtheros40-AR9565`](https://github.com/qiqco/Atheros-Wi-Fi-Hackintosh-macOS/blob/main/AirPortAtheros40-AR9565.zip)*
- *[`HS80211Family.kext`](https://github.com/qiqco/Atheros-Wi-Fi-Hackintosh-macOS/blob/main/HS80211Family.kext.zip)*

[Top](#ancora)

---

<a id="ancora4"></a>
## *Recommended tools*

* Recommendation 1
  * *Use [`GenSMBIOS`](https://github.com/corpnewt/GenSMBIOS), to generate new serials for your SMBIOS in order to avoid conflicts with iServices.*
* Recommendation 2
  * *Use [`ProperTree`](https://github.com/corpnewt/ProperTree), to edit your config.plist.*     
* Recommendation 3
  * *Use [`USBMap`](https://github.com/corpnewt/USBMap), to map your USB ports, starting from OC 0.9.3, they can be mapped with XHCIPortLimit enabled in config.plist + [`USBInjectAll`](https://github.com/Sniki/OS-X-USB-Inject-All/releases).*
* Recommendation 4
  * *Extract your DSDT from windows.*
  * *Use [`SSDTTime`](https://github.com/corpnewt/SSDTTime), to generate your SSDT patches.*    
* Recommendation 5
  * *Use [`MaciASL`](https://github.com/acidanthera/MaciASL), to compile your SSDT patches on mac.*

[Top](#ancora)

---

<a id="ancora5"></a>
## *Intel BIOS Settings*

- [*OpenCore Install Guide*](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/haswell.html#intel-bios-settings)

[Top](#ancora)

---

<a id="ancora6"></a>
## *Thanks*

- [*Acidanthera*](https://github.com/acidanthera)
- [*CorpNewt*](https://github.com/corpnewt)
- [*CrisHotpatch*](https://t.me/crishotpatch)
- [*Dortania*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html)
- [*Dicas do Mateus*](https://www.youtube.com/c/DicasdoMateus)
- [*Gabriel Luchina*](https://www.youtube.com/c/GabrielLuchina)
- [*unitedastronomer*](https://github.com/unitedastronomer)
- [*qiqco*](https://github.com/qiqco)
- *And others*

[Top](#ancora)

---

<a id="ancora7"></a>
## *License*

*The* [*MIT License*](LICENSE.md) (*MIT*)

*Copyright :copyright: 2020* 

[Top](#ancora)

---