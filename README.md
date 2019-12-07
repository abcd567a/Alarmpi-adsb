# Alarmpi-adsb
</br>

## STEP 1 of 3: Install dump1090-fa </br>

```
sudo pacman -S --needed git

git clone https://github.com/abcd567a/dump1090-fa-arch.git  

cd dump1090-fa-arch  

makepkg -si
```
</br></br>

## STEP 2 of 3: Install FlightRadar24 feeder On Alarmpi:</br>

```
sudo pacman -S --needed wget
sudo bash -c "$(wget -O - https://raw.githubusercontent.com/abcd567a/Alarmpi-adsb/master/Alarmpi-install-fr24feed_1.0.24-7_arm.sh)"
```
</br></br>

## STEP 3 of 3: Install Planefinder feeder On Alarmpi:</br>

```
sudo pacman -S --needed wget
sudo bash -c "$(wget -O - https://raw.githubusercontent.com/abcd567a/Alarmpi-adsb/master/Alarmpi-install-pfclient_4.1.1_armhf.sh)"
```

