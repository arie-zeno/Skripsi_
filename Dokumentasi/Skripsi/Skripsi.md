# Mata Kuliah Skripsi
Pada mata kuliah Skripsi perangkat lunak yang dibutuhkan selama pembelajaran adalah **Office dan Mendeley** .

## Installasi Office
Secara bawaan ubuntu 22.04 sudah terinsall software libreOffice untuk keperluan pembuatan dokumen. Berikut adalah gambar dari software libreOffice :
- LibreOffice Writer (Software pembuat kata)
![Writer](img/img_1.png)

- LibreOffice Calc (Software pembuat angka)
![calc](img/img_2.png)

- LibreOffice Impress (Software pembuat presentasi)
![Impress](img/img_3.png)
 
 - LibreOffice Math (Software untuk formula matematika)
![Math](img/img_4.png)

 - LibreOffice Draw (Software untuk menggambar)
![Draw](img/img_5.png)

## Installasi Mendeley
Untuk software mendeley versi desktop dapat di install melalui paket flapak, namun secara bawaan flatpak belum terinstall pada sistem operasi ubuntu.

### Installasi Flatpak
Untuk menginstall flatpak ketikkan perintah `sudo apt install flatpak` kemudian tambahkan repository flathub dengan perintah `flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo`.

Setelah menginstall flatpak kunjungi https://flathub.org kemudian cari 'mendeley' untuk melihat perintah installasinya.

![Draw](img/img_6.png)

install mendeley dengan perintah `flatpak install flathub com.elsevier.MendeleyDesktop`. 

![Draw](img/img_7.png)


Pada saat pertama kali membuka software mendeley akan diminta login terlebih dahulu.

![mendeley](img/img_8.png)

Berikut adalah gambar mendeley pada sistem operasi ubuntu.

![mendeley](img/img_9.png)

## Mengintegrasikan LibreOffice Writer dengan mendeley
Untuk mengintegrasikan LibreOffice Writer dengan mendeley buka terlebih dahulu libreOffice Writer kemudian pada tab tools pilih extension manager atau tekan shortcut `CTRL + ALT E`.

![mendeley](img/img_10.png)

tambahkan extension mendeley dengan mengklik tombol `add` kemudian pilih mendeley extension yang berada pada `/var/lib/flatpak/app/com.elsevier.MendeleyDesktop/current/active/files/extra/share/mendeleydesktop/openOfficePlugin/Mendeley-x.xx.x.oxt`.

![mendeley](img/img_11.png)

Setelah itu buka kembali libreOffice Writer dan mendeley sudah terintegrasi dengan libreOffice Writer.

![mendeley](img/img_12.png)


[<<< Kembali](../../README.md)
