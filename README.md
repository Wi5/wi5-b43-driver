# wi5-b43-driver
b43 is the open source driver for 802.11b/g/n family of wireless chips that are produced by Broadcom. 
It is introduced in Linux 2.6.24 and supports  BCM4321 and BCM4322 as of Linux 2.6.38.
Our purpose is to run Odin Wi-5 in the AP's having BCM4321 and BCM4322 chipsets. In order to handle this, we need to modify b43 driver to 
enable the device sending Layer 2 ACK's for the frames sent by the STA's connected to the device. 
