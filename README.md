# sumnode-pi-os

## See Releases for download file 

An out of the box Sumcoin Super-Node for Raspberry Pi made for running a GB ATM's or other Node services.

### Preview

![Image](https://raw.githubusercontent.com/sumcoinlabs/sumcoin-pi-os/master/images/Desktop1.jpeg)


![Image](https://raw.githubusercontent.com/sumcoinlabs/sumcoin-pi-os/images/Desktop2.jpeg)

## An out of the box Raspberry Pi Image with Sumcoin v17 Binaries loaded using Raspbian OS.

* Prepare the SD Card being written to 
#### MAKE SURE your SD card is at *least* 32 GB and formatted to ms-dos FAT32 - IF your SD card is larger than that it MUST be formatted or it will not work!!
SD Card Formatter Tools
https://www.sdcard.org/downloads/formatter/

### Get the zip image, save it on your SD card, unzip and delete the zip folder.
* Download the image from this release

### Write the Image
* Write to a Micro SD card using your favorite program.
Here's a helpful Video using Windows
"How to write an image to an SD card - Raspberry Pi Beginner's Guide"
https://www.youtube.com/watch?v=D2TISpT7yLI


* Plug into your Pi.

Sumcoin will load automatically with a unique wallet.dat to the home directory.
(You can change this location to external drive also)

### Configuration 
Navigate to .sumcoin in home dir to configure your ATM or other service in sumcoin.conf
(if you don't see it, press control-H to show hidden folders)

### Port Forwarding !
**Make sure to open ports 3332 and 3333 on your Modem/Network for full Node functionality.

### Verify
See if it's showing (can take an hour for the site to see)
http://www.sumnode.io/

Tailor made for General Bytes ATM's, but usable for any other service as well.

