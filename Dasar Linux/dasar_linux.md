# DASAR DASAR LINUX

Dalam **CyberSecurity**, OS yang umum digunakan adalah Linux terutama **KALI LINUX** karena toolsnya yang lengkap. Jadi sekarang saya akan menjelaskan dasar-dasar menggunakan linux, tidak hanya Kali linux tetapi juga linux berbasis *Debian* lainnya.
tentu jika kalian sudah mengerti atau sudah menggunakan linux untuk waktu yang cukup lama, anda bisa melewati penjelasan ini

## How to use your terminal 

### Updating
Anggap saja kita baru meng-install Kali linux kita. Hal pertama yang harus dilakukan adalah mengupdate semua yang ada didalam linux. 
Kalau kalian ingin versi gui nya, applikasi yang bisa digunakan adalah **Update Manager**

Tapi karena dalam Kali linux tidak ada dan agar kita dapat membiasakan diri dengan terminal jadi kita akan mengupdate software kita lewat command
```
sudo apt update
```
atau
```
sudo  apt-get update
```
lalu akan muncul output seperti ini, inputkan password linux kalian 

![alt text](update.jpeg?raw=true)

jika update selesai akan muncul output seperti ini
dan kita masukkan command 
```
sudo apt ugrade
```
untuk meng-upgrade atau meng-install update-an software
akan muncul confirmasi seperti ini, kita  hanya perlu tekan y untuk yesatau n untuk no.
Atau kita bisa menggunakan shortcut seperti ini untuk otomatis input 'y'
```
sudo apt upgrade -y
```
saat upgrade dimhulai akan muncul output sepperti ini, tunggu hingga selesai

setelah upgrade selesai restart pc kalian dan lanjut ke penjelasan berikutnya

### SUDO

kita baru saja menggunakan command **sudo**,

