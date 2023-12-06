# Text-Editor-Nano
&nbsp; &nbsp; Hai Rekan CloudKilat, Menindaklanjuti pembahasan tentang [Menguasai Editor Teks Linux: Mendalami Nano, Vi dan Vim.](https://github.com/Jaliseno/Text-Editor-Linux). Maka pada knowledge base ini akan membahas tuntas tantang Text Editor Nano.

## Instalasi
&nbsp; &nbsp; Secara default text editor ini terinstall pada sistem operasi Ubuntu, namun untuk sistem operasi lain perlu dilakukan instalasi terlebih dahulu dan berikut baris perintah untuk instalasinya:


#### Sistem Operasi Debian
```
apt update -y
apt install nano -y
```
#### Sistem Operasi CentOS
```
yum update -y
yum install nano -y
```
#### Sistem Operasi AlmaLinux & Rocky Linux
```
dnf update -y
dnf install nano -y
```

&nbsp; &nbsp; Silakan ditunggu hingga proses instalasi selesai, biasanya proses update dan instalasi text editor nano ini hanya membutuhkan waktu kurang dari 5 Menit.

## Implementasi
#### 1. Membuka Text Editor Nano
&nbsp; &nbsp; Untuk menggunakan text editor nano yang telah terinstal, Anda dapat membuat file baru untuk menambahkan konten yang Anda inginkan atau mengedit file yang sudah ada pada sistem Linux Anda.
&nbsp; &nbsp; Untuk melakukan perubahan atau penambahan file Anda dapat menjalankan perintah `nano` diikuti dengan nama file yang akan Anda buat, sebagai contoh kami akan membuat file dengan nama `cloudkilat.txt` dan berikut baris perintahnya:
```
nano cloudkilat.txt
```
&nbsp; &nbsp; Sama halnya dengan membuat file baru, apabila Anda ingin melakukan edit file tertentu menggunakan text editor nano maka Anda dapat menjalankan perintah `nano` diikuti nama file yang akan diedit. Sebagai contoh kami akan melakukan perubahan pada file `kilatvm.txt` dan berikut baris perintahnya:

```
nano kilatvm.txt
```
&nbsp; &nbsp; Untuk menyimpan perubahan dan keluar dari Text Editor Nano dengan menekan `CTRL+X` kemudian tekan `Y` dan diakhiri dengan menekan `Enter`.

#### 2. Melakukan Percobaan Edit pada File wp-config.php


