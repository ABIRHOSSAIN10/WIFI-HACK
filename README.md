## [OneShot](https://github.com/drygdryg/OneShot) installer for [Termux](https://play.google.com/store/apps/details?id=com.termux)
### Setup
```
$ pkg update && pkg upgrade

$ pkg install git python

$ git clone https://github.com/Mahfuz-THBD/Wifi_Hack_Installer

$ cd Wifi_Hack_Installer

$ python Installer.py

```
### Run
Disable Wi-Fi in the system settings and run:
```
sudo python OneShot/oneshot.py -i wlan0 -K
```
### How to update OneShot
To check for updates and update, run the following command:
```
(cd OneShot && git pull)
```
