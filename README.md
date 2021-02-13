# Ubuntu Baslangic Kurulum Notları

* Update ve Upgrade

```sh
sudo apt update
sudo apt upgrade
```
* Chrome Kurulumu

```sh
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb
cat /etc/apt/sources.list.d/google-chrome.list
```
* Nvidia Driver Install

```sh
sudo ubuntu-drivers autoinstall
```
