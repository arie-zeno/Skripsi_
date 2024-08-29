# Mata Kuliah Pengembangan Open Source
Pada mata kuliah Pengembangan Open Source perangkat lunak yang dibutuhkan selama pembelajaran adalah **Code Editor / IDE dan XAMPP** .



 ## Installasi Visual Studio Code
 Unduh paket installasi pada halaman [Visual Studio Code](www.code.visualstudio.com). Kemudian install paket tersebut dengan perintah `dpkg -i namafile.deb`, berikut gambar saat installasi  Visual Studio Code :  
 ![idle python](img/img_1.png)
 
 Kemudian berikut adalah gambar dari software visual studio code setelah terinstall :

![vscode](img/img_2.png)

## Installasi XAMPP

Kunjungi halaman [XAMPP](https://www.apachefriends.org) untuk mengunduh paket installasi xampp.

![xampp](img/img_3.png)

Ubah permissions file agar bisa dieksekusi dengan perintah `chmod 755 xampp-linux-*-installer.run`

![xampp](img/img_4.png)

Kemudian eksekusi installer dengan perintah `sudo ./xampp-linux-*-installer.run` maka jendela setup installasi akan muncul.

![xampp](img/img_5.png)

Setelah selesai setup, xampp akan terinstall pada folder /opt/lampp


Untuk menjalankan service xampp melalui CLI dapat menggunakan perintah `sudo /opt/lampp/lampp start`. Untuk memeriksa service apakah sudah berjalan gunakan perintah ` sudo /opt/lampp/lampp status`. Kemudian untuk menghentikan service xampp dapat menggunakan perintah `sudo /opt/lampp/lampp stop`.

![xampp](img/img_6.png)

Untuk menjalankan service xampp dengan GUI jalankan perintah `sudo /opt/lampp/manager-linux-x64.run`

![xampp](img/img_8.png)



[<<< Kembali](../../README.md)
