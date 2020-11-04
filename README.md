# mac os-BigSur-thinkpad-x250
### OpenCore 0.63 for MacOS BigSur Beta 1-10, and 11.0.1 beta 1 
###  hibernate problem ,so don't forget completely turn off hibernate 

sudo pmset -a sleep 0

sudo pmset -a hibernatemode 0

sudo pmset -a disablesleep 1

sudo rm -f /var/vm/sleepimage

sudo pmset hibernatefile /dev/null

### download https://github.com/teddytaod/macos-BigSur-thinkpad-x250/releases/
![image](https://github.com/teddytaod/macos-BigSur-thinkpad-x250/blob/master/BigSur-beta6.png)
## wifi and Bluetooth NO work
