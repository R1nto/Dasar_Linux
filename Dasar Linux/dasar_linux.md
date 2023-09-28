# DASAR DASAR LINUX

Dalam **CyberSecurity**, OS yang umum digunakan adalah Linux terutama **KALI LINUX** karena toolsnya yang lengkap. Jadi sekarang saya akan menjelaskan dasar-dasar menggunakan linux, tidak hanya Kali linux tetapi juga linux berbasis *Debian* lainnya.
tentu jika kalian sudah mengerti atau sudah menggunakan linux untuk waktu yang cukup lama, anda bisa melewati penjelasan ini

## Basic Command 

### Installing, Updating, Removing  
* **sudo**, singkatan dari _super user do_ artinya menjalankan command dengan root priviledge <br />
- **apt/apt-get**, singkatan dari _advance packaging tool_ command yang digunakan untuk menginstall, update, upgrade aplikasi sampai seluruh sistem linux<br />
+ **search**, argumen untuk mencari software<br/>
```console
sudo apt search keyword
```
- **install**, argumen untuk menginstall software<br/>
```console
sudo apt install appname
```
- **update**, argumen yang terdapat dalam apt command, digunakan saat ingin meng update _package list index_<br />
```terminal
sudo apt update
```
- **upgrade**, argumen untuk memasang list yang sudah di update<br/>
```console
sudo apt upgrade
```
- **autoremove**, <br/>
```console
sudo apt autoremove appname
```
> detailnya, gunakan **apt -h**<br/>

###I/O

**touch**
```
touch filename.file
```

