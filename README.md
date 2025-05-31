Untuk menjalankan program Daisuke Clinic yang telah di modularisi ke dalam beberapa file

Untuk memulai program
1. Buka Terminal untuk mengcompile program
2. Compile semua program java dengan:
3. Setelah di compile jalankan file Main

Program saat dijalankan:

•	Setelah di compile. Program akan mengoutput tampilan Selamat Datang dan 13 Menu Utama (termasuk menu keluar).
 
> ![image](https://github.com/user-attachments/assets/544d0208-c81d-4e69-b6a5-b96ae373b5d6)

### •	**Menu 1. Kelola dokter**
 
> ![image](https://github.com/user-attachments/assets/df7bfe3a-cc0c-4d44-8d20-899193143c5e)

Pada menu ini memiliki beberapa pilihan:
##### 1.	Tambah Dokter --> Menu ini digunakan untuk menambahkan dokter baru
 
> ![image](https://github.com/user-attachments/assets/6a270107-06a6-428d-9133-9ca79259a236)

Menu ini akan meminta pengguna untuk memasukkan ID Dokter, Nama, Umur, Alamat, Telepon, Spesialisasi, dan Jadwal Praktik.
 
> ![image](https://github.com/user-attachments/assets/b6dda4b9-7621-4e14-afe3-1ca83b349c94)

Namun jika pengguna memasukkan ID Dokter yang sudah ada program akan memberi tau jika sudah ada dokter dengan ID tersebut.

##### 2.	Lihat Semua Dokter --> Menu ini menampilkan semua dokter yang ada di RS ini
 
> ![image](https://github.com/user-attachments/assets/9e71c0dc-6736-4c09-a6e2-0542814e797c)

Menu ini akan menampilkan nama dokter secara terurut berdasarkan abjad namanya, dan diikuti dengan ID Dokter, Spesialis, dan Ketersediaannya.

##### 3.	Cari Dokter --> Menu ini digunakan untuk mencari dokter 

> ![image](https://github.com/user-attachments/assets/10923aa5-a141-498b-abbd-93f30486df6c)

Saat kita memasukkan nama atau ID Dokter, maka program akan memberi tahu apakah ditemukan atau tidak. Jika ditemukan maka akan menampilkan Nama (ID Dokter) – Spesialis – Ketersediaannya serta Jadwalnya

> ![image](https://github.com/user-attachments/assets/c3248e17-eaa9-4ada-acdc-4e401d377d7d)

Namun, jika kita memasukkan nama atau ID Dokter yang tidak ada, maka program akan memberi tahu jika dokter tidak ditemukan.

##### 4.	Update Status Ketersediaan --> Mengubah Status Ketersediaan Dokter

> ![image](https://github.com/user-attachments/assets/0c8067e4-8aa8-4f16-9cf3-1ed6716c3d44)

Saat mengubah status dari Tersedia menjadi Tidak Tersedia, maka masukkan huruf ‘T’.
 
> ![image](https://github.com/user-attachments/assets/1fc1cf4b-d434-475b-85e1-fc5b62a28feb)

Untuk mengubah status dari Tidak Tersedia menjadi Tersedia, maka masukkan huruf ‘Y’.

##### 0.	Kembali --> Digunakan untuk kembali ke menu utama.


### **•	Menu 2. Kelola Pasien**

> ![image](https://github.com/user-attachments/assets/10343fc7-899b-4c31-98a9-8314de325400)
 
Pada menu ini memiliki beberapa pilihan:
##### 1.	Daftar Pasien Baru --> Digunakan untuk menambahkan pasien baru

> ![image](https://github.com/user-attachments/assets/18a04d1b-685c-4dcf-9e27-0ccc5e73152d)

Saat mendaftarkan pasien baru, pengguna disuruh untuk mengisi Nama, Umur, Alamat, Telepon, Riwayat Medis, Golongan darah, dan pasien pun berhasil didaftarkan.

> ![image](https://github.com/user-attachments/assets/9f254158-9bce-45de-a26d-69b2da1f455e)

Namun jika pengguna memasukkan ID Pasien yang sudah ada program akan memberi tau jika sudah ada pasien dengan ID tersebut.

##### 2.	Lihat Semua Pasien --> Untuk melihat semua pasien yang ada

> ![image](https://github.com/user-attachments/assets/90108fec-390e-4b1e-b27d-eacaf834fad9)

Pada menu ini akan menampilkan semua pasien yang ada beserta dengan jam masuk RS dan golongan darahnya.

##### 3.	Cari Pasien --> Untuk mencari pasien

> ![image](https://github.com/user-attachments/assets/19edeeab-8eb4-4749-bdad-b79df708cf79)

Pada menu ini pengguna akan disuruh untuk memasukkan nama atau ID Pasien. Jika ditemukan maka akan menampilkan Nama Pasien (ID Pasien) – Tanggal Masuk RS – Golongan darah dan Riwayat Medisnya.

> ![image](https://github.com/user-attachments/assets/fc92960d-cc50-495b-8a3f-9cc632addbbc)

Namun, jika kita memasukkan nama atau ID Pasien yang tidak valid, maka program akan memberi tahu jika Pasien tidak ditemukan.

##### 0.	Kembali --> Digunakan untuk kembali ke menu utama


### •	Menu 3. Kelola Perawat
 
> ![image](https://github.com/user-attachments/assets/1fcfd7f6-6ee2-49a6-898e-2ae8bab216d9)

Pada menu ini memiliki beberapa pilihan:
##### 1.	Tambah Perawat  Untuk menambah perawat

> ![image](https://github.com/user-attachments/assets/882636f5-d3c2-423c-bc3e-68b919a77df9)

Saat menambahkan perawat baru, pengguna disuruh untuk mengisi ID, Nama, Umur, Alamat, Telepon, Shift, Departemen, dan perawat pun berhasil didaftarkan.

> ![image](https://github.com/user-attachments/assets/3f1b60e8-7721-447e-877f-1a4d293cb55c)

Namun jika pengguna memasukkan ID Perawat yang sudah ada program akan memberi tau jika sudah ada perawat dengan ID tersebut.
##### 2.	Lihat Semua Perawat  Untuk melihat semua perawat

> ![image](https://github.com/user-attachments/assets/b7d32830-2b91-4384-a755-da192c81fe2d)

Pada menu ini akan menampilkan Nama Perawat (ID Perawat) – Departmen – dan Shiftnya.
##### 3.	Cari Perawat  Mencari Perawat

> ![image](https://github.com/user-attachments/assets/0e9c20db-5dfb-4669-ab11-1bc5af5502f9)

Pada menu ini pengguna akan disuruh untuk memasukkan nama atau ID Perawat. Jika ditemukan maka akan menampilkan Nama Perawat (ID Perawat) – Departmen – dan Shiftnya.
 
> ![image](https://github.com/user-attachments/assets/c83a7921-c3d4-4d7d-855d-012687ed3360)

Namun, jika kita memasukkan nama atau ID Perawat yang tidak valid, maka program akan memberi tahu jika Perawat tidak ditemukan.
##### 0.	Kembali  Digunakan untuk kembali ke menu utama


### •	Menu 4. Kelola Janji Temu
 
 > ![image](https://github.com/user-attachments/assets/805be866-5b6d-4cf2-8481-c778e71b55a8)

Pada menu ini memiliki beberapa pilihan:
#### 1.	Buat Janji Temu Baru  Untuk membuat janji temu baru

>![image](https://github.com/user-attachments/assets/638c8fd1-d57c-4597-9868-740ae2e03a64)

Untuk membuat janji temu baru maka disuruh untuk memasukkan ID Pasien, ID Dokter, Tanggal dan Waktu, Keluhan, dan Janji temu pun berhasil dibuat dan ID Janji Temu akan muncul.

 > ![image](https://github.com/user-attachments/assets/2f2fca6c-ff7b-43a8-acd4-a71e8895724d)

Jika memasukkan ID Pasien atau ID Dokter yang tidak ada pada sistem, program akan menampilkan peringatan bahwa Pasien dan Dokter tidak ditemukan.
#### 2.	Lihat Semua Janji Temu 

 > ![image](https://github.com/user-attachments/assets/f4c4b528-0bf5-46f7-aa6c-003a30636b5e)

Menu ini akan menampilkan semua janji temu yang sudah didaftarkan pada menu buat janji temu baru. Pada Menu ini akan menampilkan ID Janji – ID Pasien – ID Dokter – Tanggal buat janji – Status Janji Temu.
#### 3.	Update Status Janji Temu 

 > ![image](https://github.com/user-attachments/assets/0d09eaf7-e8a0-4555-883a-50e5dec42028)

Menu ini digunakan untuk mengupdate status janji temu dengan pilihan Pending, Selesai, dan Batal.
#### 4.	Lihat Janji Temu

 > ![image](https://github.com/user-attachments/assets/3f15609a-e2ab-47ae-9cfe-169128f32abd)

Menu ini digunakanuntuk melihat Janji Temu Pasien dengan memasukkan ID Pasien
#### 0.	Kembali : Digunakan untuk kembali ke menu utama
