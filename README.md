# linuxkurulumPWN3D

Releasing all files that linuxkurulum scripts uses & downloads.

Basicly using this script will compromise your system & data, due to encrypted bash code and you have to login as root to run script. Yeah even your passwd could be changeable ;)

##### NOTE THAT: 

This repository is entire clone of linuxkurulum script&file servers. 

You can clone everything except README.md to use script without any connection to linuxkurulum servers.
 
#### Redirect lkserver.linuxkurulum.codes to YOURIP or YOURSITE and be sure directory structure is correct with my repo. Put all files at / on webserver.

#### They still changing your hosts file to remove their block but im sure you will find a way (like i do).

## More Deep

They compiled every bash file to obfuscate their code. And if you try to run menusc with only ./menusc you will get this:



```bash
----------
[Turkish]
----------
Merhaba Kullanıcımız
Bu dosyayı merak etmiş olmalısın bu gayet normal,
Tersine mühendislik yapma arzunuzun farkındayız.
Kendine iyi bak seni çok seviyoruz.
LinuxKurulum Ekibi
----------
[English]
----------
Hello our user
You must have wondered about this file.
We are aware of your desire to reverse engineer.
Take care of yourself We love you very much.
Team Linuxkurulum

```
So how to do. Each file have unique password to run. All of them hidden inside mainsc and mainsc have password to that hidden inside linuxkurulum.


#### Long story short. Mark them as executable first.

| Script Name  | Run Command  | Description |
| :------------ |:---------------:| ----- |
|menusc| ./menusc -gg 238904320|Main Menu|
|sinusbotyonet| ./sinusbotyonet -gg 9385144|Control SinusBot +BAN|
|sinusbotkur| ./sinusbotkur -gg 837539|Install SinusBot +BAN|
|nosinusbotyonet| ./nosinusbotyonet -gg 9385144|Control SinusBot -BAN|
|nosinusbotkur| ./nosinusbotkur -gg 837539|Install SinusBot -BAN|
|audiobotyonet2| ./audiobotyonet2 -gg 943085439|Control AudioBot|
|audiobotkur2| ./audiobotkur2 -gg 93583411|Install AudioBot|
|audiobotone2| ./audiobotone2 -gg 93583411|Install AudioBot Single|
|ts3serveryonet| ./ts3serveryonet -gg 99966654|Control TS3 Server|
|ts3server138| ./ts3server138 -gg 238049|Install TS3 Server+Crack|
|ts3server3210| ./ts3server3120 -gg 238049|Install TS3 Server|
|ts3server3110| ./ts3server3110 -gg 238049|Install TS3 Server|
|ts3server3102| ./ts3server3102 -gg 238049|Install TS3 Server|
|teayonet| ./teayonet -gg 3038943|Control TeaSpeak|
|teakur| ./teakur -gg 452343222|Install TeaSpeak Server|

All scripts will be removed after each run. You have to redownload them everytime or find a way to block them from deletion eh ;)

ALERT: menusc file does lot of sensitive info (of yours) transfer with lkserver.linuxkurulum.codes . Use other scripts to do your thing. 

## Whats going on ??

Simple, they check ur data and geolocate you. Even restrict your IP for no reason.

Log of mainsc

```
curl -s -4 lkserver.linuxkurulum.codes/ipcek.php
wget lkserver.linuxkurulum.codes/tarih.php -q -O -
sleep 0.01
clear

rm -fr /home/.linuxkurulum/menusc
curl -s -N -4 --head --request GET lkserver.linuxkurulum.codes/ok.license
grep 200 OK
curl -s --data tur=girisyapildi&ip=0.0.0.0 lkserver.linuxkurulum.codes/panel/islem.php
curl -s -N -4 --head --request GET lkserver.linuxkurulum.codes/panel/engelli/0.0.0.0.php
grep 200 OK
clear

rm -fr /home/.linuxkurulum/audiobotyonet2
curl -s -N -4 --head --request GET lkserver.linuxkurulum.codes/ok.license
grep 200 OK
clear
```

# COURTESY OF BYGALACOS


## License
I dont have any, like they dont...
