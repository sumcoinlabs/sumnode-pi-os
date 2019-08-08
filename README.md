# sumnode-pi-os

## Download Pi Image, Unzip, Load image to Micro SD Card

The Image is 8 GB and will take some time to download.



### What is this for?

An out of the box Sumcoin Super-Node for Raspberry Pi made for running a GB ATM's or other Node services.

Running your own Sumcoin Node adds security as an ATM Operator.   

### Overview

<img width="851" alt="Messages Image(2892912464)" src="https://user-images.githubusercontent.com/37975862/62030322-1b28fc80-b1a2-11e9-9675-f362fe11f60a.png">



## An out of the box Raspberry Pi Image with Sumcoin v17 Binaries loaded using Raspbian OS.

* Prepare the SD Card being written to 

## Format MUST be FAT32 for any size disk

Recommended disk size 

* Minimum - 32 GB
* Recommended - 128 GB +


#### MAKE SURE your SD card is at *least* 32 GB and formatted to ms-dos FAT32 - IF your SD card is larger than that it MUST be formatted or it will not work!!
SD Card Formatter Tools
https://www.sdcard.org/downloads/formatter/

### Get the zip image, save it on your SD card, unzip and delete the zip folder.
* Download the image from this release

### Write the Image - WINDOWS
* Write to a Micro SD card using your favorite program.
Here's a helpful Video using Windows
"How to write an image to an SD card - Raspberry Pi Beginner's Guide"
https://www.youtube.com/watch?v=D2TISpT7yLI

### Write the Image - MAC 
DOWNLOAD - ApplePi-Baker V2 
Platform: 	Mac OS X
Filename: 	ApplePi-Baker-v2.1.3.dmg
Version: 	2.1.3
Size: 	3.9 MiB
Date: 	June 2, 2019

Visit:
https://www.tweaking4all.com/software/macosx-software/applepi-baker-v2/#InstallingApplePiBaker


### You should now have the Sumnode Image

* Plug into your Pi.

Sumcoin will load automatically with a unique wallet.dat to the home directory.
(You can change this location to external drive also)

Preview
![FullSizeRender](https://user-images.githubusercontent.com/37975862/62030588-a1ddd980-b1a2-11e9-9639-bee75afca398.jpeg)

### Configuration 
Navigate to .sumcoin in home dir to configure your ATM or other service in sumcoin.conf
(if you don't see it, press control-H to show hidden folders)

#### You will need to Modify the 

* rpcuser
* rpcpassword
* rpcallowip

SAVE - Close, reload the Sumcoin Client

### Port Forwarding !
**Make sure to open ports 3332 and 3333 on your Modem/Network for full Node functionality.

### Verify
See if it's showing (can take an hour for the site to see)
http://www.sumnode.io/

Tailor made for General Bytes ATM's, but usable for any other service as well.

![FullSizeRender-2](https://user-images.githubusercontent.com/37975862/62030500-6cd18700-b1a2-11e9-9dcf-96c0e5c1cb6f.jpeg)
