# UAP_Adsis_E

Nama		: Muhammad Dayfit Al Rashad

NIM		: 215150701111013

Kelas		: ADSIS-E

<p align="center"><b>UAP ADSIS</b></p>

1. Buat direktori dengan nama UAP-Adsis, isi dengan file txt dengan format penamaan catatannya-<nama kamu>.txt, kemudian isi file txt tersebut dengan nama dan NIM kamu. Kemudian atur permission view-only pada file tersebut untuk user biasa. Tunjukkan bukti berupa screenshot yang menunjukkan bahwa file tersebut berhasil diatur permissionnya menjadi view-only untuk user biasa.

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.001.png" >
</p>
<p align="center">Gambar 1.1</p>
 



<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.002.png" >
</p>
<p align="center">Gambar 1.2</p>


 

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.003.png" >
</p>
<p align="center">Gambar 1.3</p>


**Penjelasan :** 

Pada Gambar 1.1 merupakan pembuatan direktori menggunakan perintah “mkdir” yang mana direktorinya bernama “UTP-Adsis”, Kemudian membuat file baru dengan nama “dayfit.txt” dengan menggunakan perintah “touch”. Lalu memindahkan file yang baru dibuat  ke direktori “UTP-Adsis”. Kemudian pada gambar 1.2 melakukan perubahan file permission dengan perintah “sudo chmod 400 dayfit.txt” dan mengecek  bahwa file tersebut telah diubah permissionnya dengan perintah “ls – l dayfit.txt” terlihat pada gambar bahwa pengubahan permission menjadi view only telah berhasil. Pada gambar 1.3 melakukan  pengisian  nama dan NIM pada file dayfit.txt dengan perintah “sudo nano dayfit.txt”


2. Lakukan konfigurasi alamat IP address sementara pada sistem dan default gateway. (petunjuk 192.168.56.x | x adalah nomor absen)

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.004.png" >
</p>
<p align="center">Gambar 2.1</p>

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.005.png" >
</p>
<p align="center">Gambar 2.2</p>

**Penjelasan :**

konfigurasi alamat IP address sementara pada sistem dan default gateway. Dengan mengubah IP address untuk ens33 menjadi  192.168.56.8 pada Gambar 2.1. Lalu menambahkan default gateway dengan perintah “sudo route add default gateway 192.168.56.8 pada Gambar 2.2

3. Lakukan Instalasi Webmin lalu buatlah user bernama nama anda, lalu buat group Adsis\_(kelas masing-masing) dan masukkan nama anda di group

**ScreenShot :**

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.006.png" >
</p>
<p align="center">Gambar 3.1</p>

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.007.png" >
</p>
<p align="center">Gambar 3.2</p>



<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.008.png" >
</p>
<p align="center">Gambar 3.3</p>

  
<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.009.png" >
</p>
<p align="center">Gambar 3.4</p>
  
<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.010.png" >
</p>
<p align="center">Gambar 3.5</p>


**Penjelasan :**

Melakukan pembuatan user baru  (gambar 3.1 & 3.2), Pembuatan group Adsis\_E (Gambar 3.3 dan 3.4), Pemasukkan user ke dalam group Adsis\_E (Gambar 3.5) 

  
4. Lakukan ping ke alamat ip anda dan coba lakukan reject dan drop di webmin, lalu analisis apa yang terjadi?

**Screenshot :** 
  
  

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.011.png" >
</p>
<p align="center">Gambar 4.1</p>

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.012.png" >
</p>
<p align="center">Gambar 4.2</p>

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.013.png" >
</p>
<p align="center">Gambar 4.3</p>
  
 <p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.014.png" >
</p>
<p align="center">Gambar 4.4</p>

**Penjelasan :**

Pada gambar 4.1 melakukan pengecekan ping terhadap IP address dimana ping berjalan. Kemudian melakukan drop dan reject pada webmin pada gambar 4.2. Setelah melakukan reject dan drop webmin menjadi lost connection pada gambar 4.3, itu terjadi Ketika menggunakan fitur "reject" atau "drop" pada Webmin untuk menolak atau menjatuhkan koneksi dari suatu alamat IP, itu akan menyebabkan koneksi yang ada saat ini dengan alamat IP tersebut terputus. Hal ini terjadi karena tindakan "reject" atau "drop" menghentikan komunikasi dengan alamat IP tersebut secara langsung. Lalu ketika melakukan pengecekan ping kembali maka ping tidak akan berjalan pada gambar 4.4



5. Buatlah perintah otomatis yang berfungsi untuk ping [www.filkom.ub.ac.id](http://www.filkom.ub.ac.id/)

**Screenshot :**

 <p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.015.png" >
</p>
<p align="center">Gambar 5.1</p>

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.016.png" >
</p>
<p align="center">Gambar 5.2</p>

<p align="center">
  <img src="https://github.com/dayfitmuhrashad/UAP_Adsis_E/blob/main/images/Aspose.Words.65a08ee3-505f-40ad-9f84-f665dc6dd402.017.png" >
</p>
<p align="center">Gambar 5.3</p>


**Penjelasan :**

Untuk melakukan edit  tabel cron pada sistem Linux digunakan perintah sudo crontab -e pada gambar 5.1. Tabel cron adalah file yang berisi daftar task yang dijadwalkan untuk dijalankan secara otomatis pada waktu yang ditentukan pada gambar 5.2. pada file cron , saya mengatur pesan otomatis untuk ping filkom.ub.ac.id yaitu “\*/ 1 \* \* \* \* ping filkom.ub.ac.id” yang artinya akan mengecek ping filkom setiap 1 menit sekali. Kemudian pada gambar 5.3 memasukkan perintah ps -aux | grep ping yang  digunakan untuk menampilkan informasi proses yang sedang berjalan pada sistem dan mencari proses yang terkait dengan ping, maka akan muncul ping yang dikirimkan ke filkom.ub.ac.id setiap 1 menit sekali.
