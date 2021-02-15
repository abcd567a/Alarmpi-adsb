# Alarmpi-adsb
### The details below describbe how to install following items on Alarmpi OS on Rapberry Pi:
**1 - Decoder (dump1090-fa)** </br>
**2 - Flightradar24 Feeder (fr24feed)** </br>
**3 - Planefinder Feeder (pfclient)** </br>
**4 - Flightaware Feeder (piaware)** </br>

</br>

## (1) - Install Decoder - dump1090-fa (on Armv7 and AArch64 OS)</br>

##  https://github.com/abcd567a/dump1090-fa-arch/blob/master/README.md

</br></br>

## (2) - Install FlightRadar24 feeder - fr24feed (on Armv7 OS ONLY): </br>

```
sudo pacman -Sy --needed wget
sudo bash -c "$(wget -O - https://raw.githubusercontent.com/abcd567a/Alarmpi-adsb/master/Alarmpi-install-fr24feed_armv7.sh)"
```
</br></br>

## (3) - Install Planefinder feeder - pfclient (on Armv7 and AArch64 OS): </br>

```
sudo pacman -Sy --needed wget
sudo bash -c "$(wget -O - https://raw.githubusercontent.com/abcd567a/Alarmpi-adsb/master/Alarmpi-install-pfclient_armhf.sh)"
```
</br></br>

## (4) - Install Flightaware feeder - piaware (on Armv7 and AArch64 OS): </br>

## https://github.com/abcd567a/piaware-arch/blob/main/README.md

</br>
</br>
