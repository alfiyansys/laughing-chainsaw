# laughing-chainsaw
Aircrack-ng wrapper, wifi jammer scripted tool for ubuntu

Punya tetangga mengganggu? Berisik dan mabar sampai malam? 

Steps:
- Create config, by copying from example file
- Config your wifi interface
- Run init.sht, for initial config (this will cause selected wifi card unmanaged by NetworkManager)
- Run dump.sht, for scan surrounding wireless AP
- Add your target to two additional variables on config, BSSID and channel number
- Run jam.sht, for jamming the AP
- Run deinit.sht, for returning wifi device to 'normal mode'


---
Inspired by https://www.securitynewspaper.com/2020/11/24/revenge-your-neighbors-by-jamming-any-wifi-in-a-block-3-ways-to-creating-a-wifi-jammer-blocker-without-any-special-hardware/
