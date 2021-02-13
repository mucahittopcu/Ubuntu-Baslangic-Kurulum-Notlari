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

* Nvidia Driver Kurulumu
```sh
sudo ubuntu-drivers autoinstall
```

* Anaconda Kurulumu
Anaconda sitesinde talimatlara göre kurulur.

Sonra
```
conda update conda
conda update anaconda
```
Aktif edilmiş env'in terminalde gözükmemesi için;
```
conda config --set changeps1 false
```
Terminalin otomatik olarak base env ile başlamsını kapatmak için;
```
conda config --set auto_activate_base false
```


