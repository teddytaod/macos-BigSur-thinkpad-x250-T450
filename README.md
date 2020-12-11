# mac os-BigSur-thinkpad-x250-T450
### OpenCore 0.63 for MacOS BigSur 11.0.1 
_____________________________________________________________________________________________________________
### (huge change in OC-0.63-V2 , delete wifi and bluetooth kext ,add wifi-usb kext,and now use VoodooHDA)
# have not released yet

_____________________________________________________________________________________________________________
### The newest OC EFI, download https://github.com/teddytaod/macos-BigSur-thinkpad-x250/releases/
### fix earphone problem or no sound --https://github.com/chris1111/VoodooHDA-OC to download
### wireless(wifi usb)---https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter  to download

###  hibernate problem ,so don't forget completely turn off hibernate
sudo pmset -a sleep 0

sudo pmset -a hibernatemode 0

sudo pmset -a disablesleep 1

![image](https://github.com/teddytaod/macos-BigSur-thinkpad-x250/blob/master/BigSur-beta6.png)
## wifi and Bluetooth NO work
