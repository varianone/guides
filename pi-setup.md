# Setup fresh Raspberry PI

## set locale

```shell
sudo dpkg-reconfigure locales
```

## set timezone

```shell
sudo raspi-config
```

Down arrow to 4 Localisation Options and press Enter.

## setup green prompt for other user

```shell
sudo cp /home/pi/.bashrc /home/<new user>/
sudo cp /home/pi/.profile /home/<new user>/
```

## [disable sudo password for created user](https://www.mathworks.com/help/supportpkg/raspberrypi/ug/enable-passwordless-sudo-in-linux-on-raspberry-pi-hardware.html)
