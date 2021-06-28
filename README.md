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

* Terminal Tab Yardımlı Önerme <br>
.bashrc'nin sonuna aşağıdaki satır eklenir.
```sh
bind TAB:menu-complete
```

* Anaconda Kurulumu
Anaconda sitesinde talimatlara göre kurulur.

Sonra
```
conda update conda
conda update anaconda
```
Aktif edilmiş env'in terminalde isminin gözükmemesi için;
```
conda config --set changeps1 false
```
Terminalin otomatik olarak base env ile başlamsını kapatmak için;
```
conda config --set auto_activate_base false
```

* Alt Tab yaparken Ubuntu 18.04'te uygulamaları ayrı ayrı açma

Settings > Devices > Keyboard > Switch Windows == ALT + TAB


* Pycharm Kurulumu
```
sudo snap install pycharm-community --classic
```


* Discord Kurulumu
```
sudo snap install discord
```

* Snap Paketlerini Güncelleme
```
sudo snap refresh
```



