<p align="center">
  <img src="https://raw.githubusercontent.com/btd1337/elementary-full-icon-theme/master/logo.png"><br>
  <b>Urutau Icons</b><br><br>
  A package of icons that transforms the third-party icons with the elementary appearance. Built from the original Urutau that seems to no longer be maintained.<br><br>
</p>

## Installation:

### Requirements

 - Elementary icon theme: https://github.com/elementary/icons _Note: Already installed by default in elementary OS_

### First Installation?

Install Git if you don't already have it installed.

On Ubuntu/Elementary/Debian:

    $ sudo apt install git

On Fedora/CentOS/RedHat:

    $ sudo dnf install git

Clone the repository (or download files):  

    $ sudo git clone https://github.com/GabePoel/Urutau-Plus.git /usr/share/icons/Urutau-Plus

Set theme:  

    $ gsettings set org.gnome.desktop.interface icon-theme "Urutau-Plus"

Or just change in using Elementary Tweaks or Gnome Tweaks.

### Update?

    $ cd /usr/share/icons/Urutau-Plus
    $ sudo git pull

### Uninstall?

    $ gsettings set org.gnome.desktop.interface icon-theme "elementary"
    $ sudo rm -R /usr/share/icons/Urutau-Plus
