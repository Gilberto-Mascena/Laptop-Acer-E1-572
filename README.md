[English](https://github.com/Gilberto-Mascena/Laptop-Acer-E1-572/blob/main/README.md) | 
[Português Brasileiro](https://github.com/Gilberto-Mascena/Laptop-Acer-E1-572/blob/main/README-pt_br.md)

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

<div align="left">  
  <img width="100" src="./img/macos-catalina-icon.png" alt="macOS Catalina icons"> 
  <img width="100" src="./img/macos-big-sur-icon.png" alt="macOS Big Sur icons">   
</div>

<div>
  <img align="right" src="./img/banner-acer.png" alt="photo NoteBook Acer" width="320">
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
   - *Kingston SA400S37 120GB SATA3 2.5 SSD*
 - _**WI-FI / Bluetooth**_
   - *Atheros AR9565*
>[!WARNING]  
> _Not supported on macOS Monterey_ 

##
 - _**Network**_
   - *Broadcom NetXtreme BCM57786*

<a name="anchor"></a>

## _Topic navigation_

- [*What works*](#anchor1)
- [*Screenshot*](#anchor2)
- [*Kexts used, (all Releases)*](#anchor3)
- [*Recommended tools*](#anchor4)
- [*Intel BIOS Settings*](#anchor5)
- [*Thanks*](#anchor6)
- [*License* ](#anchor7)

---

<a id="anchor1"></a>

<details><summary><h2>What works</h2></summary>

- [x] *Video (onbord HDMI).*
- [x] *Sound*
- [x] *Network*
- [x] *WI-FI*
- [X] *Bluetooth*
- [x] *USB*
- [X] *Sleep*

[Top](#anchor)
</details>

<a id="anchor2"></a>

## Screenshots

![about](./img/about.png)

<details><summary><h2>Memory (Upgraded to 16GB)</h2></summary>

![memory](./img/memory.png)
</details>

<details><summary><h2>Sound</h2></summary>

![sound](./img/sound.png)
</details>

<details><summary><h2>Network and WI-FI</h2></summary>

![network](./img/network-wi-fi.png)
</details>

<details><summary><h2>Bluetooth</h2></summary>

![bluetooth](./img/bluetooth.png)
</details>

<details><summary><h2>Opencore version</h2></summary>

![opencore](./img/opencore-version.png)
</details>

<details><summary><h2>Hackintool peripherals</h2></summary>

![peripherals](./img/peripherals.png)
</details>

<details><summary><h2>USB port mapping</h2></summary>

![usb-mapping](./img/USB-mapping.png)

[Top](#anchor)
</details>

<a id="anchor3"></a>

<details><summary><h2>Kexts used, (all Releases)</h2></summary>

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

[Top](#anchor)
</details>

<a id="anchor4"></a>

<details><summary><h2>Recommended tools</h2></summary>

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

[Top](#anchor)
</details>

<a id="anchor5"></a>

<details><summary><h2>Intel BIOS Settings</h2></summary>

- [*OpenCore Install Guide*](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/haswell.html#intel-bios-settings)

[Top](#anchor)
</details>

## [_Creating macOS Installer on Windows or Linux_](https://github.com/Gilberto-Mascena/How-to-create-a-macOS-installer-without-a-Mac)

<a id="anchor6"></a>

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

[Top](#anchor)

<a id="anchor7"></a>

## *License*

*The* [*MIT License*](LICENSE.md) (*MIT*)

### Gilberto | Dev _2020_ 

[Top](#anchor)

---