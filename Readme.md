# Setting up a Raspberry Pi home server

My setup consists of a Raspberry Pi 4 - 8GB version, the Argon One m.2 case with a 1TB SATA SSD.


### Boot from SSD
Flash a SD card with Raspberry Pi Imager with the USB Boot bootloader selected. Flash it on the PI (wait for the green light to go-off in a rythm).
Connect the SSD (USB port at base of Argon) to your PC and flash a copy of Raspbian onto it. Connect to the Pi and boot

## Securing your RPi
Disable Root login
Disable Password authentication
Install fail2ban
Install logwatch #optional

## Installing Pre-requisites
Install docker using the convenience scripts from [here]()


## Deploying Apps
We will begin by deploying Portainer.

### Portainer
### Traefik
### Authelia
### LLDAP
