# Mata Kuliah Pemrograman Dasar 2
Pada mata kuliah Pemrograman Dasar 2 perangkat lunak yang dibutuhkan selama pembelajaran adalah **Code Editor / IDE, XAMPP dan Composer** .



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

# Installasi Composer
Untuk menginstall composer pada sistem operasi Ubuntu dapat menggunakan langkah-langkah berikut.

- ## Install PHP

    Untuk menginstall PHP gunakan perintah berikut.

    `sudo apt install php php-curl`
    
    Setelah menginstall PHP secara otomatis apache2 juga akan terinstall sehingga service apache2 statusnya akan running.

    Setelah itu periksa versi PHP yang sudah terinstall dengan perintah `php -V`.

![xampp](img/img_9.png)

- ## Download Composer

    Kemudian download composer dengan perintah `curl -sS https://getcomposer.org/installer -o composer-setup.php`, setelah itu install composer menggunakan perintah `sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer`.

![xampp](img/img_10.png)

    Cek versi composer untuk memastikan composer sudah terinstall pada sistem operasi dengan perintah `composer -V`.

![composer](img/img_11.png)



[<<< Kembali](../../README.md)