# *EFI OC Laptop-Acer-E1-572 macOS Big Sur*

![tag](https://img.shields.io/github/v/release/Gilberto-Mascena/Laptop-Acer-E1-572)
![release-date](https://img.shields.io/github/release-date/Gilberto-Mascena/Laptop-Acer-E1-572)
![size](https://img.shields.io/github/repo-size/Gilberto-Mascena/Laptop-Acer-E1-572)
![license](https://img.shields.io/github/license/Gilberto-Mascena/Laptop-Acer-E1-572)
##

## *Sistema Operacional*

<img align="right" src="./Imagens/banner.png" alt="Foto NoteBook Acer" width="330">

_**macOS**_  _**Big Sur 11.7.10**_

## 

_**Meu Laptop**_

##

 - _**Laptop**_
   - [*ACER E1-572-6_BR471*](https://www.acer.com/br-pt/support?search=40545129395;NX.MEVAL.019;E1-572&filter=global_download)
 - _**CPU**_
   - *Core I3 4010U*
 - _**GPU**_
   - *Intel HD Graphics 4400*
 - _**Memória Ram**_
   - *1x2GB + 1x4GB Total 6GB*
 - _**SSD Sata**_
   - *Kingston SA400S37 120G SATA3 2.5 SSD*
 - _**Rede**_
   - *Broadcom NetXtreme BCM57786*
 - _**WI-FI / Bluetooth**_
   - *Atheros AR9565*
##

## *O que funciona*

- [x] *Video (onbord via HDMI).*
- [x] *Áudio*
- [x] *Rede*
- [x] *WI-FI*
- [X] *Bluetooth*
- [x] *USB*
- [X] *Sleep*
##

## *Captura de telas*
 
![about](./Imagens/about.png)
![Captura de Tela 2022-08-22 às 00 33 47](https://user-images.githubusercontent.com/103699861/185834958-248b77b0-6b24-4daa-8e6a-491e9293b582.png)
![Captura de Tela 2022-08-22 às 00 35 22](https://user-images.githubusercontent.com/103699861/185834964-bd57d1cd-0aaf-4d20-81b7-31dd45014314.png)
##

## *Kexts usadas, (todas versões Releases)*

- *[`WhateverGreen.kext`](https://github.com/acidanthera/WhateverGreen)*
- *[`Lilu.kext`](https://github.com/acidanthera/Lilu)*
- *[`VirtualSMC`](https://github.com/acidanthera/VirtualSMC), somente: `VirtualSMC.kext`, `SMCProcessor.kext`, `SMCBatteryManager.kext` e `SMCSuperIO.kext`*.
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
##

## *Utilização*

* Recomendação 1
  * *Use [`GenSMBIOS`](https://github.com/corpnewt/GenSMBIOS), para gerar novos seriais para sua SMBIOS afim de evitar conflitos com iServices.*
* Recomendação 2
  * *Use [`ProperTree`](https://github.com/corpnewt/ProperTree), para editar sua config.plist.*     
* Recomendação 3
  * *Use [`USBMap`](https://github.com/corpnewt/USBMap), para mapear suas portas USB, apartir do OC 0.9.3, pode ser mapeadas com XHCIPortLimit habilitada no config.plist + [`USBInjectAll`](https://github.com/Sniki/OS-X-USB-Inject-All/releases).*
* Recomendação 4
  * *Extrair sua DSDT a partir do windows.*
  * *Use [`SSDTTime`](https://github.com/corpnewt/SSDTTime), para gera seus patches de SSDT.*    
* Recomendação 5
  * *Use [`MaciASL`](https://github.com/acidanthera/MaciASL), para compilar seus patches de SSDT.*
##

## *Agradecimentos*

- [*Acidanthera*](https://github.com/acidanthera)
- [*CorpNewt*](https://github.com/corpnewt)
- [*CrisHotpatch*](https://t.me/crishotpatch)
- [*Dortania*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html)
- [*Dicas do Mateus*](https://www.youtube.com/c/DicasdoMateus)
- [*Gabriel Luchina*](https://www.youtube.com/c/GabrielLuchina)
- [*unitedastronomer*](https://github.com/unitedastronomer)
- [*qiqco*](https://github.com/qiqco)
- *E outros*
##

## *Licença*

*The* [*MIT License*](LICENSE.md) (*MIT*)

*Copyright :copyright: 2020* 
##