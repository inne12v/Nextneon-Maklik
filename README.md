# Nextneon-Maklik
This is still in beta testing. Do not use this as an daily driver.

<h1>Intro</h1>

Welcome to Nextneon Maklik.
I build an Linux distro based on Ubuntu using Cubic.
Because i didn't change all files in the disk, you will see very much details of that it is just a little change of ubuntu.
I am working on that, but this project is not just because so that it is really very different from ubuntu, but it is made for people who need an intro to open-source software.
Most of the software *i* installed is open-source.
It has many apps installed, so this is not recommended on old laptops.
There are apps installed such as VScodium, Bottles, Audacity, Flameshot, Lollypop, etc.
Because i use an compression format which has results in really big iso's, you get an really big iso.
For the real source (because i just changed things in the terminal) check out: https://github.com/ubuntu
It's theme is changing. I am working on arcmenu and dash-to-panel.
It's now straight-out an ubuntu theme, but i am tweaking it to a more windows-like experience, but i am keeping the dock on the dock.
![alt text](https://lh3.googleusercontent.com/pw/AP1GczPRKlWq-vbU8St8J6sbwTbqqEoEWYnfAgnipkdCGUnlpHtKx1pkVbhWhtVFb5VkUV8vt1cJ97rK1TNyIrSGTUTswE6nDKmWyVajbf9vuUJJF4LFKKgAUbFZoQnHSFHKWz52kqIfzQ-ayx6Rc9GUPd7I=w1276-h797-s-no?authuser=0)
![alt text](https://lh3.googleusercontent.com/pw/AP1GczP8U0eKK-A_ul24ahTZ1mrDqPmIns42VaTC7629nXq76AQkdnfuSavYJXZlIY69AGOrPrdb14JlaxkiwKO2AmV_6S0wyuMd6MaZAc0EN9DOTmxGde06qUdTTKiorMUYNkNzOTwefgKznrdnQwl9Lu59=w1279-h796-s-no?authuser=0)

download it on: https://mega.nz/file/6VMWwZyI#YzO2DyiUhCRFcmc1llU4Fyry6OX5r-tX0dPadCxP8Hc

<h1>Installation</h1>
First, go to the link above. Download the iso file.
<h2>VM (virtualbox/VMware workstation) Recommended</h2>
This is a good option if you just wanna test it. 
<h4>VMware or virtualbox?</h4>
you can choose between vmware workstation and virtualbox.
I am gonna choose for virtualbox, but feel free to use vmware workstation.
Download virtualbox: https://www.virtualbox.org/wiki/Downloads
Download VMware workstation: https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion (Download workstation) (need an account, feel free to use another website to download the installer)
Install the program you just downloaded.
Click 'New'
Give it a name, the folder can just stay the same, and click iso image, 'other', and select the iso image (often in Downloads)
Select as OS type Linux, and as Version 'Ubuntu (64 bit)'. 
<h5>Configure to virtual machine</h5>
Configure with minimal 4GB of ram, 4 cpu's, Check the box of EFI, and select create new hard disk.
After it's done, start the machine.
Wait until it booted...
Follow the steps in the installation program (hint: test the keyboard out before selecting it), and if you have some expensive hardware or so, check the box 'Install third-party programs and drivers for hardware' or something like that.
When you are done, select restart.
The computer will restart, but first shows a message 'please remove the installation media, then press enter' just press enter.
Now you succesfully installed it.
You can follow the introduction program at startup, but you can close it.

<h2>Tryout or install on a usbstick</h2>
<h4>Windows</h4>
click the windows-button+r, and type 'msinfo32' and hit enter.
Search for bios-mode and remember what stands there 'legacy' or 'uefi'.
go to rufus.ie, download the latest version.
Open the program (no install required) and Drag&drop the iso to rufus.
Select a usb-stick, and select GPT if you had uefi where in the program we opened before, and select MBR if you had legacy before.
Click the start button and wait. after you see 'ready', it's done.
After that, follow the steps from "after writing the usb"
<h4>Linux</h4>
Depending on your distro, you will need to install etcher.
go to: https://github.com/balena-io/etcher/releases
download your installation file. 
First, open terminal. type in: uname -m.
if you see as output X86 = x86, X86_64 = amd64 or aarch64 = arm64.
Ubuntu, Debian, Linux mint, Zorin etc.: download the .deb file with x86 if the output was x86, the .deb file with amd64 if the output was x86_64 and the .deb file with arm64 if the output was aarch64.
Fedora, Oracle linux, opensuse, PclinuxOS etc.: download the .rpm file with x86 if the output was x86, the .rpm file with amd64 if the output was x86_64 and the .rpm file with arm64 if the output was aarch64.
Search on google if your distro has RPM or DEB, otherwise download the .appimage
Install the file.
Open the program, select the iso, select the usb drive, and click flash.
After that's done, follow the steps from "after writing the usb"
<h4>mac</h4>
go to: https://github.com/balena-io/etcher/releases
download the .dmg file and install it.
Open the program.
Open the program, select the iso, select the usb drive, and click flash.
After that's done, follow the steps from "after writing the usb"
<h3>After writing the usb.</h3>
Reboot and press in one of this keys (maybe with an fn button):
Acer: Del, F2 or F12
Asus: F9 or esc
Dell: F12
HP: Esc or F10
Lenovo: F1 or F2
Samsung: F2
(source: wikihow)
Select: 'EFI: USB', Boot from usb-stick, EFI: <name of the usb stick here>
Wait until it boots.
You can try it out, or install it. For install, follow the next steps (for tryout you can just keep it like this, and reboot to your old operating system without things installed):
Follow the steps in the installation program (hint: test the keyboard out before selecting it), and if you have some expensive hardware or so, check the box 'Install third-party programs and drivers for hardware' or something like that.
When you are done, select restart.
The computer will restart, but first shows a message 'please remove the installation media, then press enter' just press enter.
Now you succesfully installed it.
You can follow the introduction program at startup, but you can close it.



Succes with installing and trying!
