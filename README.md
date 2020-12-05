# mac os-BigSur-thinkpad-x250
### OpenCore 0.63 for MacOS BigSur 11.0.1 
 

### The newest OC EFI, download https://github.com/teddytaod/macos-BigSur-thinkpad-x250/releases/
### update 20201205 fix earphone problem or no sound --https://github.com/chris1111/VoodooHDA-OC to download
### wireless(wifi usb)---https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter  to download


###  hibernate problem ,so don't forget completely turn off hibernate
sudo pmset -a sleep 0

sudo pmset -a hibernatemode 0

sudo pmset -a disablesleep 1

sudo rm -f /var/vm/sleepimage

sudo pmset hibernatefile /dev/null


![image](https://github.com/teddytaod/macos-BigSur-thinkpad-x250/blob/master/BigSur-beta6.png)
## wifi and Bluetooth NO work
