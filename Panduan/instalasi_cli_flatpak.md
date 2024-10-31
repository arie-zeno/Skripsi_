# Instalasi Aplikasi di Ubuntu  Menggunakan CLI dengan FLATPAK
## Tujuan
Setelah menyelesaikan bab ini pembaca diharapkan dapat:
- Menginstal perangkat lunak menggunakan CLI pada Ubuntu dengan FLATPAK.

## Langkah-Langkah Instalasi Melalui CLI dengan FLATPAK
1. **Memastikan Flatpak Terinstal**<br>
   Sebelum menggunakan Flatpak, pastikan paket Flatpak telah terinstal di sistem. Anda bisa menginstalnya dengan perintah `sudo apt install flatpak`. Agar dapat mengunduh aplikasi, tambahkan Flathub ke sistem Anda dengan perintah `flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo`

2. **Mencari Aplikasi di Flathub**<br>
   Untuk mencari aplikasi yang diinginkan, buka situs Flathub di browser Anda. Di sana, Anda dapat menjelajahi aplikasi yang tersedia, membaca deskripsi, dan mengonfirmasi ID aplikasi untuk instalasi.


3. **Install Aplikasi**<br>
   Setelah daftar paket diperbarui anda dapat melakukan instalasi aplikasi dengan perintah `apt install`. Sebagai contoh untuk instalasi VirtualBox jalankan perintah `sudo apt install virtualbox`, sistem akan mengunduh dan melakukan instalasi aplikasi beserta dependensinya.

   <center> 

   ![icon](img/install_vb.png)

   </center>

4. **Konfirmasi Instalasi**<br>
   Jika ada konfirmasi untuk melanjutkan instalasi, sistem akan menampilkan prompt yang meminta anda mengetik "**y**" (yes) untuk melanjutkan. Tekan y dan ***Enter*** untuk konfirmasi.
5. **Instalasi Selesai**<br>
   Setelah proses selesai, aplikasi siap digunakan. Aplikasi yang telah diinstal dapat ditemukan di menu Applications, atau bisa langsung dibuka melalui terminal dengan mengetik nama aplikasinya.

 
 <div style="display: flex; justify-content: space-between;">
  <a href="https://example.com">Sebelumnya</a>
  <a href="https://example.com">Selanjutnya</a>
</div>