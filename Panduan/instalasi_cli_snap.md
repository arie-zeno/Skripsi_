# Instalasi Aplikasi di Ubuntu  Menggunakan CLI dengan SNAP
## Tujuan
Setelah menyelesaikan bab ini pembaca diharapkan dapat:
- Menginstal perangkat lunak menggunakan CLI pada Ubuntu dengan SNAP.

## Langkah-Langkah Instalasi Melalui CLI dengan FLATPAK
1. **Memastikan Flatpak Terinstal**<br>
   Pada ubuntu 22.04 LTS secara bawaan sudah terinstall snap, untuk memastikan dapat menggunakan perintah `snap version` pada terminal.
   <center> 

   ![icon](img/snap_ver.png)

   </center>

2. **Mencari Aplikasi di Snapcraft**<br>
   Untuk mencari aplikasi yang diinginkan, buka situs [Snapcraft](https://snapcraft.io/store) di browser, disana anda dapat menjelajahi aplikasi yang tersedia.

   <center> 

   ![icon](img/snap_browser.png)

   </center>


3. **Menginstall Aplikasi dengan Snap**<br>
   Setelah menemukan aplikasi di Snapcraft, salin script instalasi yang ditampilkan, dan gunakan perintah tersebut untuk instalasi. Sebagai contoh, untuk menginstal **freeCAD** menggunakan `sudo snap install freecad`.

   <center> 

   ![icon](img/snap_instal_script.png)

   </center>

   Kemudian snap akan mendownload aplikasi beserta dependensinya dan menginstalnya secara otomatis.

   <center> 

   ![icon](img/snap_proses.png)

   </center>

4. **Instalasi Selesai**<br>
   Setelah proses selesai, aplikasi siap digunakan. Aplikasi yang telah diinstal dapat ditemukan di menu Applications, atau bisa langsung dibuka melalui terminal dengan mengetik nama aplikasi.

<div style="display: flex; justify-content: space-between;">

<span>

[Sebelumnya](./instalasi_cli_flatpak.md) 

</span>

<span>

[Selanjutnya](./instalasi_deb_gui_ubuntu_software.md) 

</span>

</div>