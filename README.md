<!-- phisher -->



<p align="center">
  <img src="https://img.shields.io/badge/Author-Dark_c0mrade-cyan?style=flat-square">
  <img src="https://img.shields.io/badge/Open%20Source-Yes-cyan?style=flat-square">
  <img src="https://img.shields.io/badge/Written%20In-Bash-cyan?style=flat-square">
</p>

<p align="center">A beginners friendly, Automated phishing tool with 30+ templates.</p>

##

<h3><p align="center">Disclaimer</p></h3>

<i>Any actions and or activities related to <b>Phisher</b> is solely your responsibility. The misuse of this toolkit can result in <b>criminal charges</b> brought against the persons in question. <b>The contributors will not be held responsible</b> in the event any criminal charges be brought against any individuals misusing this toolkit to break the law.

<b>This toolkit contains materials that can be potentially damaging or dangerous for social media</b>. Refer to the laws in your province/country before accessing, using,or in any other way utilizing this in a wrong way.

<b>This Tool is made for educational purposes only</b>. Do not attempt to violate the law with anything contained here. <b>If this is your intention, then Get the hell out of here</b>!

It only demonstrates "how phishing works". <b>You shall not misuse the information to gain unauthorized access to someones social media</b>. However you may try out this at your own risk.</i>

##

### Features

- Latest and updated login pages.
- Mask URL support 
- Beginners friendly
- Multiple tunneling options
  - Localhost
  - Ngrok (With or without hotspot)
  - Cloudflared (Alternative of Ngrok)


### Installation
- Just, Clone this repository -
```
$ git clone https://github.com/theDarkc0mrade/phisher
```

- Change to cloned directory and run `phisher.sh` -
```
$ cd phisher
$ bash phisher.sh
```
- On first launch, It'll install the dependencies and that's it. `phisher` is installed.
### If something not working 

- Mannually install cloudflared from this site -
``
https://developers.cloudflare.com/cloudflare-one/connections/connect-apps/install-and-setup/installation
``
- Then unzip file and move to /phisher/.server/ -
```
$ mv cloudflared "path/to/phisher"
```
- Mannually install ngrok from this site -
``
https://ngrok.com/download
``
- Then unzip file and move to /phisher/.server/ -
```
$ mv ngrok "path/to/phisher"
```






### Dependencies

**`Zphisher`** requires following programs to run properly - 
- `php`
- `wget`
- `curl`
- `git`
- `ngrok`
- `cloudflared`


> All the dependencies will be installed automatically when you run `phisher` for the first time.

> Supported Platform : **`Termux`**, **`Ubuntu/Debian/Kali/Parrot`**, **`Arch Linux/Manjaro`**, **`Fedora`**, **`MacOS`**





### Original repo name :   [**Zphisher**](https://github.com/htr-tech/zphisher)

>  I added feature to the supported Platform :  **`MacOS`**
> IF something not working you need to do :

> 1 install manually ngrok and move ngrok to phisher/.server

> 2 cd phisher/.server && ./ngrok "your auth token"

> 3 install manually cloudflared and move cloudflared to phisher/.server

### Special Thanks :

- [**Aditya Shakya**](https://github.com/adi1090x)
- [**Tahmid Rayat**](https://github.com/htr-tech)
- [**1RaY-1**](https://github.com/1RaY-1)
- [**Yisus7u7**](https://github.com/Yisus7u7)
- [**TheLinuxChoice**](https://twitter.com/linux_choice)
- [**DarksecDevelopers**](https://github.com/DarksecDevelopers)
- [**Moises Tapia**](https://github.com/MoisesTapia)
