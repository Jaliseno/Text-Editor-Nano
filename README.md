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

#### 2. Shortcut Text Editor Nano
&nbsp; &nbsp; Berikut adalah beberapa shortcut umum yang digunakan dalam text editor Nano:
- **Menyimpan File**

&nbsp; Setelah mengedit atau membuat file, kita dapat menggunakan shortcut keyboard di bawah ini untuk menyimpan file dengan perubahan tanpa menutupnya.
```
Ctrl + O
```
- **Keluar dari Text Editor Nano**

&nbsp; Banyak pengguna baru yang terus berjuang untuk keluar dari text editor Nano dengan benar. Jadi, untuk itu Anda bisa menggunakan shortcut keyboard di bawah ini:
```
Ctrl + X
```
Sebelum keluar dari editor, jika ada perubahan yang belum disimpan, maka Nano akan meminta Anda untuk menyimpannya sebelum keluar.

- **Memindahkan kursor**

&nbsp; Untuk memilih baris pada editor atau teks tertentu, kita dapat memindahkan kursor menggunakan tombol panah atau mouse

- **Mengedit Teks**:

&nbsp; Tidak seperti editor VIM, Anda tidak perlu menekan tombol `INSERT` untuk menambahkan teks ke file seperti editor teks GUI Linux pada umumnya, kita dapat langsung mengetik atau menghapus teks.

- **Memotong, Menyalin & Menempel di Text Editor Nano**

&nbsp; Untuk memudahkan kita dalam menyalin, memotong dan menempel text pada text editor Nano. Anda bisa menggunakan shortcut keyboard di bawah ini:
```
Ctrl + K: Memotong (cut) teks dari posisi kursor ke akhir baris.
Ctrl + U: Memotong (cut) teks dari posisi kursor ke awal baris.
Ctrl + Y: Menempelkan (paste) teks yang telah dipotong atau disalin.
Ctrl + C: Menyalin teks yang dipilih.
```

- **Undo & Redo di Text Editor Nano**

&nbsp; Untuk memudahkan kita dalam mengurungkan dan mengulangi pengeditan text pada text editor Nano. Anda bisa menggunakan shortcut keyboard di bawah ini:
```
Alt + U untuk membatalkan perubahan terakhir.
Alt + R untuk mengulangi perubahan terakhir.
```

- **Mencari dan Mengganti**

&nbsp; Untuk memudahkan kita dalam mencari dan mengganti script pada text editor Nano. Anda bisa menggunakan shortcut keyboard di bawah ini:
```
Ctrl + W untuk mencari teks tertentu dalam file di Nano editor.
Ctrl + R untuk mengganti teks tertentu dalam file.
```

- **Bantuan**

&nbsp; Apabila Anda mengalami kesulitan pada saat menggunakan text editor Nano, maka Anda dapat melihat halaman bantuan text editor Nano dengan menggunakan shortcut keyboard di bawah ini:
```
Ctrl + G untuk menampilkan halaman bantuan Nano Editor dengan daftar perintah.
```

- **Keluar dengan Menyimpan atau Membuang Perubahan**

&nbsp; Setelah Anda melakukan perubahan atau menambahkan file baru dan menggunakan shortcut keyboard `Ctrl + X`, maka nantinya Anda diberikan tiga pilihan yaitu dengan menekan huruf `Y` (Untuk Menyimpan), `C` (Untuk Membatalkan keluar) dan `N` (Untuk tidak menyimpan perubahan).


