# ArchLinux-Alarmpi-adsb
</br>

## STEP 1 of 3: Install dump1090-fa </br>

```
sudo pacman -S --needed git

git clone https://github.com/abcd567a/dump1090-fa-arch.git  

cd dump1090-fa-arch  

makepkg -si
```
</br></br>

## STEP 2 of 3: Install FlightRadar24 feeder </br>

### (A) On Arch Linux:  </br>

```
## Option 1: fr24feed_1.0.24-5_i386
sudo pacman -S --needed wget
sudo bash -c "$(wget -O - https://raw.githubusercontent.com/abcd567a/ArchLinux-Alarmpi-adsb/master/ArchLinux-install-fr24feed_1.0.24-5_i386.tgz.sh)"

## Option 2: fr24feed_1.0.18-5_amd64
sudo pacman -S --needed wget
sudo bash -c "$(wget -O - https://raw.githubusercontent.com/abcd567a/ArchLinux-Alarmpi-adsb/master/ArchLinux-install-fr24feed_1.0.18-5_amd64.tgz.sh)"
``` 

### (B) On Alarmpi:
```
sudo pacman -S --needed wget
sudo bash -c "$(wget -O - https://raw.githubusercontent.com/abcd567a/ArchLinux-Alarmpi-adsb/master/Alarmpi-install-fr24feed_1.0.24-7_arm.sh)"
```
</br></br>

## STEP 3 of 3: Install Planefinder feeder </br>

### (A) On Arch Linux: </br>

```
## Will be posted shortly
``` 

### (B) On Alarmpi:
```
sudo pacman -S --needed wget
sudo bash -c "$(wget -O - https://raw.githubusercontent.com/abcd567a/ArchLinux-Alarmpi-adsb/master/Alarmpi-install-pfclient_4.1.1_armhf.sh)"
```

