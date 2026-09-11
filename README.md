# Samsung-I9105p-s2vep-Flashable-boot.img Image

DISCLAIMER:
THIS IS AN DOWNSTREAM BUILD OF THE POSTMARKETOS KERNEL BOOT IMAGE WHICH MAY HAVE MANY MORE BUGS THAN YOU CAN IMAGINE. HAVE A BACKUP BEFORE FLASHING THIS AND TRY AT YOUR OWN RISK.

Installing a custom Operating System on a Galaxy S2 Plus (s2vep, i9105p) will require the bootloader to be unlocked, which may VOID your warranty and may delete all your data. Before proceeding further you may consider backup all data on the phone. You are the only person doing changes to your phone and I cannot be held responsible for the mistakes done by you.

KNOWN BUGS:
XFCE4 will not work under any circumstances because the old 3.0.X kernel can NOT understand newer code.
System randomly Restarting or SSH disconnecting without warning.

WORKING:
LXQT desktop enviroment, MATE and LXDE

DESCRIPTION:
This Kernel is a working (tested by me) build for the Galaxy S2 Plus/s2vep its a active linux kernel that allows you to boot PostmarketOS of the SD card or the internal DATA Partition since most of the PmBootstrap System builds are too big for the internal Partitions you can flash it onto the SD card.
There is a whole Tutorial on that in the PMOS wiki.

FLASHING PROCESS:
Download the Boot.img, 7zip from https://www.7-zip.org/ and Odin3 from https://odinflash.com/
Step 1: 
Install and Open 7z, Right-click on the Boot.img and navigate over to 7z > , Then click add to Archive <img width="622" height="567" alt="image" src="https://github.com/user-attachments/assets/0f5bb9eb-9d82-4ecb-984b-56944aa90ae3" />
Select Tar as the Archive format and dont touch anything else.
Then click ok, it will prompt you in wich folder you want to save the boot.img.tar

Step 2:
Extract odin from its zip and run the Odin3.x.x.exe file.
 
Step 3:
Connect the Samsung i9105p to your PC in download mode.
Odin will reconize it as COM : 5 
Click on AP and then select your boot.img.tar file.
<img width="874" height="641" alt="image" src="https://github.com/user-attachments/assets/df4f78d0-cf61-421d-8892-74842c9d80e5" />


BEFORE YOU CLICK "Start"
MAKE SURE YOU BACKED UP ALL FILES OF YOUR DEVICE YOU ARE WILLING TO RISK I WILL NOT BE MADE LIABLE FOR ANY BRICKED DEVICES, THERMONUCLEAR WARS OR DATA LOSS.

Wait till it prompts DONE! then disconnect your device.

Then install Pmbootstrap on your Linux System/ or WSL (windows subsystem for linux) the tutorial for that will be found on the PostmarketOS wiki.

FUNCTIONALITIES:
Wifi does work but you will have to always start it up manually through SSH or Terminal.
Touch does work Flawlessly and Apps run quite Smooth 
I also got Luanti and OpenTTD to work
<img width="2621" height="3495" alt="1789124146711" src="https://github.com/user-attachments/assets/f94b45d7-07f9-4d4f-8a6a-40fd9d28b5f5" />
<img width="2491" height="3321" alt="1789124146651" src="https://github.com/user-attachments/assets/dbfc7b12-70d8-4c7c-8cb9-c4d20135bbdc" />
<img width="3000" height="4000" alt="1789124146750" src="https://github.com/user-attachments/assets/b29b1971-433a-49b5-a1d8-876b8d7cf109" />

