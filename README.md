# Laprak2_M.Daffa' al haq.s_028_TK4B

Nama : M.Daffa' al haq.s <br>
NIM : 09030282327028 <br>
Kelas : TK4B <br>
Program studi : Teknik komputer <br>

Judul praktikum :  IP Address Versi 4 (IPv4)

**ping ip dan transfer file menggunakan kabel LAN** <hr>

A. Alat yang digunakan :
1. Laptop <br>
   <img src="https://github.com/user-attachments/assets/87099e81-bf96-4ace-817f-c1261e9ce0de" alt="Image" width="300">

2. Kabel LAN <br>
   <img src="https://github.com/user-attachments/assets/ca6b5f9e-1acf-401c-8365-eb80b94d3a97" alt="Image" width="300">

B. Percobaan dan analisis :
- ping ip <br>
Ping antar laptop menggunakan kabel LAN digunakan untuk menguji konektivitas jaringan antara dua perangkat secara langsung. 
Langkah-langkah ping ip : <br>
  1). Pasang kabel LAN ke port LAN laptop 1 dan 2 <br>
      <img src="https://github.com/user-attachments/assets/87099e81-bf96-4ace-817f-c1261e9ce0de" alt="Image" width="300"> <br>
  2). Pilih tampilan network lalu klik kanan tekan "Open network & internet setting" <br>
      <img src="https://github.com/user-attachments/assets/ae855f00-ca58-48e4-ae33-98590c343e26" alt="Image" width="300"> <br>
  3). Pilih change adapter options <br>
      <img src="https://github.com/user-attachments/assets/8979ade4-2c9b-4974-82bd-67b2c8084495" alt="Image" width="300"> <br>
  4). Pilih ethernet lalu klik kanan pilih properties <br>
      <img src="https://github.com/user-attachments/assets/9d5e80f6-af0e-40ef-a781-4e2ecdc3edbf" alt="Image" width="300"> <br>
  5). Pilih ipv4 klik 2 kali <br>
      <img src="https://github.com/user-attachments/assets/88d2b012-30a1-4175-9c67-6038fdeb55f2" alt="Image" width="300"> <br>
  6). ubah ip dari automatic jadi use the following ip address, lalu masukkan ip 192.168.100.1 di laptop 1 dan 192.168.100.2 di laptop 2 lalu tekan ok <br>
      <img src="https://github.com/user-attachments/assets/863c40cd-969b-4737-9546-339e6120a5f1" alt="Image" width="300"> <br>
  7). untuk melakukan ping ip buka cmd lalu ketik ping 192.168.100.1 jika mau ping di laptop 2, 192.168.100.2 jika mau ping di laptop 1 <br>
      <img src="https://github.com/user-attachments/assets/b67d9b82-9828-464f-b634-b0ffa52dad26" alt="Image" width="300"> <br> <hr>


- transfer file <br>
Transfer file antar laptop menggunakan kabel LAN lebih cepat dibandingkan WiFi. <br>
Langkah-langkah transfer file : <br>
  1). masuk ke file explore <br>
      <img src="https://github.com/user-attachments/assets/1720c741-53b5-432d-81ee-841a5eae4fe4" alt="Image" width="300"> <br> 
  2). pilih file yang ingin di transfer klik kanan lalu pilih properties <br>
      <img src="https://github.com/user-attachments/assets/e91a7a96-8507-4738-882b-402e3a73b76b" alt="Image" width="300"> <br>
  3). pilih sharing lalu tekan advanced sharing <br>
      <img src="https://github.com/user-attachments/assets/e66fbbc1-76ae-4518-a12b-0268bcff4521" alt="Image" width="300"> <br>
  4). centang share this file lalu tekan permission <br>
      <img src="https://github.com/user-attachments/assets/96d429b6-f285-4609-a267-6ad4c69187f1" alt="Image" width="300"> <br>
  5). centang full control, apply, ok <br>
      <img src="https://github.com/user-attachments/assets/c4da4f90-d7e5-4b68-9ac4-a74a5b493347" alt="Image" width="300"> <br>
  6). pilih share <br>
      <img src="https://github.com/user-attachments/assets/e66fbbc1-76ae-4518-a12b-0268bcff4521" alt="Image" width="300"> <br>
  7). pilih everyone <br>
      <img src="https://github.com/user-attachments/assets/cb1f69a7-2a49-4613-b940-1aca15e3ab8d" alt="Image" width="300"> <br>
  8). Tekan add <br>
      <img src="https://github.com/user-attachments/assets/1a9abba8-3d78-485a-b5ba-2f4add011f1f" alt="Image" width="300"> <br>
  9). Lalu ubah dari read menjadi read/write <br>
      <img src="https://github.com/user-attachments/assets/8dc8a7d5-f218-4716-ac73-93b7138b302c" alt="Image" width="300"> <br>
  10). Tekan share lalu file akan langsung ke share ke laptop yang lain <br>
       <img src="https://github.com/user-attachments/assets/391e7ce6-3e4d-4673-84fa-3b2bf2970248" alt="Image" width="300"> <br>
  11). Lalu cek file di network apabila sudah ada maka transfer file berhasil <br>
       <img src="https://github.com/user-attachments/assets/202405a5-76d3-42c5-8bd8-5b3159270fd8" alt="Image" width="300"> <br>
       <img src="https://github.com/user-attachments/assets/68fbbb05-9b0a-4111-9bbe-4120812ce52e" alt="Image" width="300"> <br>

C. Kesimpulan : <br>
Penggunaan kabel LAN untuk ping IP dan transfer file antar laptop memberikan koneksi yang cepat dan stabil dibandingkan dengan jaringan nirkabel.

Ping IP digunakan untuk menguji konektivitas antara dua laptop yang terhubung melalui kabel LAN. Dengan mengatur IP Address statis, kita dapat memastikan bahwa kedua perangkat dapat saling berkomunikasi. Jika ping berhasil, berarti koneksi jaringan telah terjalin dengan baik.

Transfer file melalui LAN dapat dilakukan dengan berbagai metode, seperti file sharing Windows, FTP, atau software pihak ketiga. Metode file sharing Windows memungkinkan pengguna berbagi folder yang dapat diakses dari laptop lain melalui jaringan lokal. Alternatif lain, seperti FTP, dapat digunakan untuk pengelolaan file yang lebih fleksibel.

Keunggulan menggunakan kabel LAN adalah kecepatan transfer yang lebih tinggi, minim gangguan, dan konfigurasi sederhana dibandingkan dengan metode transfer file melalui jaringan WiFi atau perangkat penyimpanan eksternal.

Untuk memastikan keberhasilan koneksi dan transfer data, penting untuk melakukan pengaturan yang benar, seperti menonaktifkan firewall sementara jika diperlukan, mengaktifkan file sharing, dan memastikan kabel LAN dalam kondisi baik.
