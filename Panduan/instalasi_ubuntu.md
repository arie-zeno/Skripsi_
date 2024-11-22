# Instalasi Sistem Operasi Ubuntu
## Tujuan
Setelah menyelesaikan bab ini pembaca diharapkan dapat:
- Memahami langkah-langkah dasar dalam instalasi sistem operasi Ubuntu.
- Menyiapkan lingkungan yang sesuai untuk instalasi Ubuntu pada perangkat keras.
- Melakukan instalasi sistem operasi Ubuntu pada PC/Laptop.

Ubuntu adalah salah satu distribusi Linux yang populer, digunakan secara luas karena kemudahan penggunaannya dan dukungan komunitas yang besar. Pada bab ini anda akan mempelajari bagaimana mengunduh, menyiapkan, dan instalasi Ubuntu pada PC/Laptop.

## Persiapan Instalasi
Sebelum melakukan instalasi, ada beberapa hal yang perlu disiapkan :
- **Spesifikasi Minimum:**
  - Prosesor : Dual-core 2 GHz
  - RAM : 4 GB (direkomendasikan 8 GB)
  - Penyimpanan : 25 GB ruang kosong
  - USB flash drive (minimal 8 GB)
  - Koneksi internet (opsional)

- **Mengunduh ISO Ubuntu:**
  1. Buka situs resmi Ubuntu di [http://ubuntu.com](http://ubuntu.com).
  2. Pilih versi Ubuntu yang diinginkan, misalnya Ubuntu Desktop.
  3. Klik link yang tersedia untuk mendapatkan file ISO.

  <center>    

  ![ubuntu](./img/download_ubuntu.png)

  </center> 

- **Membuat Bootable USB** <br>
  Untuk membuat bootable USB dapat mengikuti langkah-langkah pada halaman [Pembuatan Bootable USB](bootable_usb.md).

## Langkah-Langkah Instalasi Sistem Operasi Ubuntu


1. **Booting dari USB**<br>
   - Sambungkan USB bootable ke Laptop/PC.
   - Restart komputer dan masuk ke BIOS/UEFI dengan menekan tombol seperti F2, F12, atau Del. Tombol akses BIOS/UEFI dapat dilihat pada tabel berikut : <br>
  
     | Merk Laptop/PC | Tombol Akses |
     | :----: | -----|
     | Acer   | F1, F2, atau CTRL+ALT+ESC   |
     | ASUS   | f2   |
     | Axioo   | f2   |
     | Dell   | F2, Del, F12, F1, F3, atau Fn+F1   |
     | Fuijitsu   | f2   |
     | HP/Compaq   | ESC, F10, atau F1   |
     | Lenovo   | F2 atau Fn+F2   |
     | MSI   | Del   |
     | Samsung   | f2   |
     | Sony Vaio   | F1, F2, atau F3   |
     | Toshiba   | F2, ESC+F1, atau F2+power   |
     | Zyrex   | Del atau Esc   |

   - Ubah urutan booting agar USB menjadi prioritas pertama.
   - Simpan pengaturan dan keluar dari BIOS/UEFI.

2. **Memulai Instalasi**<br>
   - Setelah komputer melakukan booting dari USB, pilih Install Ubuntu.
     <center> 

     ![icon](img/ubuntu_install.png)

     </center>
   - Pilih bahasa yang akan digunakan dan klik Continue.
  
3. **Pengaturan Instalasi**<br>
   - Keyboard Layout: Pilih tata letak keyboard yang sesuai dan tekan Continue.
     <center> 

     ![icon](img/ubuntu_keyboard.png)

     </center>

   - Updates and Other Software: Pilih apakah ingin menginstall pembaruan dan perangkat lunak pihak ketiga selama instalasi seperti codec multimedia.
     <center> 

     ![icon](img/ubuntu_pembaruan.png)

     </center>
   - Installation Type : 
     - Install Ubuntu alongside [OS lama] untuk dual boot.
     - Erase disk and install Ubuntu untuk menggantikan sistem operasi yang ada.
     - Something else untuk membuat kustomisasi partisi instalasi secara  manual.
     <center> 

     ![icon](img/ubuntu_instalasi_tipe.png)

     </center>
     Klik Install Now untuk memulai proses instalasi.
   - Time Zone: Pilih zona waktu sesuai lokasi dan klik Continue.
     <center> 

     ![icon](img/ubuntu_zona_waktu.png)

     </center>
4. **Konfigurasi Pengguna**<br>
   - Masukkan nama pengguna dan password yang diinginkan.
   - Pilih metode login, apakah otomatis atau manual kemudian klik Continue.
     <center> 

     ![icon](img/ubuntu_pengaturan_user.png)

     </center>
5. **Proses Instalasi dan Penyelesaian**<br>
   - Setelah semua pengaturan selesai, proses instalasi akan dimulai.
     <center> 

     ![icon](img/ubuntu_proses_instal.png)

     </center>
   - Tunggu hingga instalasi selesai. Setelah itu klik Restart Now.
   - Lepaskan USB ketika komputer melakukan restart.

 
<div style="display: flex; justify-content: space-between;">

<span>

[Sebelumnya](../Panduan.md) 

</span>

<span>

[Selanjutnya](./pengenalan_ubuntu_desktop.md) 

</span>

</div>