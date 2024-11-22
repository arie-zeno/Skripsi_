# Instalasi Paket .deb di Ubuntu  Menggunakan CLI
## Tujuan
Setelah menyelesaikan bab ini pembaca diharapkan dapat:
- Menginstal paket .deb menggunakan CLI.

## Langkah-Langkah Instalasi Paket .deb dengan CLI
1. **Mengunduh File.deb**<br>
   Langkah pertama adalah mengunduh file .deb dari sumber terpercaya. Sebagai contoh, unduh aplikasi **Visual Studi Code** dari situs resminya, yaitu [code.visualstudio.com/download](https://code.visualstudio.com/download). Pastikan file tersimpan pada direktori yang mudah diakses, seperti **Downloads**.
   <center> 

   ![icon](img/download_vscode.png)

   </center>

2. **Buka Terminal dan Navigasi ke Folder Unduhan**<br>
   Setelah pengunduhan selesai, buka terminal dengan kombinasi tombol Ctrl + Alt + T, kemudian navigasikan ke folder tempat file .deb disimpan dengan perintah **cd ~/Downloads**.

3. **Install File .deb dengan dpkg**<br>
   Jalankan perintah **sudo dpkg -i nama_file.deb**, gantilah nama_file.deb menjadi nama file yang baru saja di download misalnya paket Visual Studio Code. Nama paket file Visual Studio Code  adalah **code_1.93.1-1726079302_amd64.deb**, sehingga untuk melakukan instalasi menggunakan perintah **sudo dpkg -i code_1.93.1-1726079302_amd64.deb**. 
   
   <center> 

   ![icon](img/dpkg_instal.png)

   </center>
4. **Perbaiki Dependensi (Jika Ada)**<br>
   Jika paket .deb memiliki dependensi yang belum terpasang, anda akan melihat pesan kesalahan. Untuk memperbaikinya jalankan perintah **sudo apt --fix-broken install** untuk instalasi dependensi yang diperlukan.

5. **Instalasi Selesai**<br>
   Setelah dependensi diperbaiki aplikasi siap digunakan. Buka dari menu Applications atau langsung dari terminal dengan mengetikkan nama aplikasi.

   


<div style="display: flex; justify-content: start;">

<span>

[Sebelumnya](./instalasi_deb_gui_gdebi.md) 

</span>



</div>