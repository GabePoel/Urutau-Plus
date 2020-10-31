<p align="center">
  <img src="https://raw.githubusercontent.com/btd1337/elementary-full-icon-theme/master/logo.png"><br>
  <b>Urutau Icons</b><br><br>
  A package of icons that transforms the third-party icons with the elementary appearance.<br><br>
</p>

![First Screenshot](https://raw.githubusercontent.com/btd1337/elementary-full-icon-theme/master/preview/img1.jpeg)  

![Second Screenshot](https://raw.githubusercontent.com/btd1337/elementary-full-icon-theme/master/preview/img2.jpeg)

![Third Screenshot](https://raw.githubusercontent.com/btd1337/elementary-full-icon-theme/master/preview/img3.jpeg)

![Fourth Screenshot](https://raw.githubusercontent.com/btd1337/elementary-full-icon-theme/master/preview/img4.jpeg)  

## Installation:

### Requirements

 - Elementary icon theme: https://github.com/elementary/icons _Note: Already installed by default in elementary OS_

### First Installation?

Install Git if you don't already have it installed.

    $ sudo apt install git

Clone the repository (or download files):  

    $ sudo git clone https://github.com/btd1337/urutau-icons.git /usr/share/icons/urutau-icons

Set theme:  

    $ gsettings set org.gnome.desktop.interface icon-theme "urutau-icons"

### Update?

    $ cd /usr/share/icons/urutau-icons
    $ sudo git pull

### Uninstall?

    $ gsettings set org.gnome.desktop.interface icon-theme "elementary"
    $ sudo rm -R /usr/share/icons/Urutau-Plus
