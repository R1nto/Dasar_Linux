# DASAR DASAR LINUX

Dalam **CyberSecurity**, OS yang umum digunakan adalah Linux terutama **KALI LINUX** karena toolsnya yang lengkap. Jadi sekarang saya akan menjelaskan dasar-dasar menggunakan linux, tidak hanya Kali linux tetapi juga linux berbasis *Debian* lainnya.
tentu jika kalian sudah mengerti atau sudah menggunakan linux untuk waktu yang cukup lama, anda bisa melewati penjelasan ini

## Basic Command 

### Installing, Updating, Removing  
**sudo** singkatan dari _super user do_ artinya menjalankan command dengan root priviledge <br />
**apt/apt-get** singkatan dari _advance packaging tool_ command yang digunakan untuk menginstall, update, upgrade aplikasi sampai seluruh sistem linux<br />
**search**<br/>
**install**<br/>
**update** argumen yang terdapat dalam apt command, digunakan saat ingin meng update _package list index_<br />
**upgrade** argumen untuk memasang list yang sudah di update<br/>
**autoremove**<br/>
***Usage***<br/>
```console
sudo apt update
sudo apt upgrade
sudo apt search appname
sudo apt install appname
sudo apt autoremove appname
```
###I/O

**touch**
```
touch filename.file
```

