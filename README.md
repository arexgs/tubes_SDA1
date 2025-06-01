Untuk menjalankan program Daisuke Clinic yang telah di modularisi ke dalam beberapa file

> ![Screenshot 2025-05-30 185927](https://github.com/user-attachments/assets/7cfb4cd5-2274-4593-b898-dc83bd2f026b)

Untuk memulai program
1. Buka Terminal untuk mengcompile program

   > ![Screenshot 2025-05-30 190146](https://github.com/user-attachments/assets/d20c3f65-f297-43ce-bec7-bedb8227c655)

2. Compile semua program java dengan:

    > ![image](https://github.com/user-attachments/assets/4836b01b-7507-47be-a114-77a923320a00)

3. Setelah di compile jalankan file Main

   > ![image](https://github.com/user-attachments/assets/866ff1df-d2c0-44ae-8c03-8bd77c5a79ea)


Program saat dijalankan:

•	Setelah di compile. Program akan mengoutput tampilan Selamat Datang dan 13 Menu Utama (termasuk menu keluar).
 
> ![image](https://github.com/user-attachments/assets/544d0208-c81d-4e69-b6a5-b96ae373b5d6)

### •	**Menu 1. Kelola dokter**
 
> ![image](https://github.com/user-attachments/assets/df7bfe3a-cc0c-4d44-8d20-899193143c5e)

Pada menu ini memiliki beberapa pilihan:
#### 1.	Tambah Dokter --> Menu ini digunakan untuk menambahkan dokter baru
 
> ![image](https://github.com/user-attachments/assets/6a270107-06a6-428d-9133-9ca79259a236)

Menu ini akan meminta pengguna untuk memasukkan ID Dokter, Nama, Umur, Alamat, Telepon, Spesialisasi, dan Jadwal Praktik.
 
> ![image](https://github.com/user-attachments/assets/b6dda4b9-7621-4e14-afe3-1ca83b349c94)

Namun jika pengguna memasukkan ID Dokter yang sudah ada program akan memberi tau jika sudah ada dokter dengan ID tersebut.

#### 2.	Lihat Semua Dokter --> Menu ini menampilkan semua dokter yang ada di RS ini
 
> ![image](https://github.com/user-attachments/assets/9e71c0dc-6736-4c09-a6e2-0542814e797c)

Menu ini akan menampilkan nama dokter secara terurut berdasarkan abjad namanya, dan diikuti dengan ID Dokter, Spesialis, dan Ketersediaannya.

#### 3.	Cari Dokter --> Menu ini digunakan untuk mencari dokter 

> ![image](https://github.com/user-attachments/assets/10923aa5-a141-498b-abbd-93f30486df6c)

Saat kita memasukkan nama atau ID Dokter, maka program akan memberi tahu apakah ditemukan atau tidak. Jika ditemukan maka akan menampilkan Nama (ID Dokter) – Spesialis – Ketersediaannya serta Jadwalnya

> ![image](https://github.com/user-attachments/assets/c3248e17-eaa9-4ada-acdc-4e401d377d7d)

Namun, jika kita memasukkan nama atau ID Dokter yang tidak ada, maka program akan memberi tahu jika dokter tidak ditemukan.

#### 4.	Update Status Ketersediaan --> Mengubah Status Ketersediaan Dokter

> ![image](https://github.com/user-attachments/assets/0c8067e4-8aa8-4f16-9cf3-1ed6716c3d44)

Saat mengubah status dari Tersedia menjadi Tidak Tersedia, maka masukkan huruf ‘T’.
 
> ![image](https://github.com/user-attachments/assets/1fc1cf4b-d434-475b-85e1-fc5b62a28feb)

Untuk mengubah status dari Tidak Tersedia menjadi Tersedia, maka masukkan huruf ‘Y’.

#### 0.	Kembali --> Digunakan untuk kembali ke menu utama.


### **•	Menu 2. Kelola Pasien**

> ![image](https://github.com/user-attachments/assets/10343fc7-899b-4c31-98a9-8314de325400)
 
Pada menu ini memiliki beberapa pilihan:
#### 1.	Daftar Pasien Baru --> Digunakan untuk menambahkan pasien baru

> ![image](https://github.com/user-attachments/assets/18a04d1b-685c-4dcf-9e27-0ccc5e73152d)

Saat mendaftarkan pasien baru, pengguna disuruh untuk mengisi Nama, Umur, Alamat, Telepon, Riwayat Medis, Golongan darah, dan pasien pun berhasil didaftarkan.

> ![image](https://github.com/user-attachments/assets/9f254158-9bce-45de-a26d-69b2da1f455e)

Namun jika pengguna memasukkan ID Pasien yang sudah ada program akan memberi tau jika sudah ada pasien dengan ID tersebut.

#### 2.	Lihat Semua Pasien --> Untuk melihat semua pasien yang ada

> ![image](https://github.com/user-attachments/assets/90108fec-390e-4b1e-b27d-eacaf834fad9)

Pada menu ini akan menampilkan semua pasien yang ada beserta dengan jam masuk RS dan golongan darahnya.

#### 3.	Cari Pasien --> Untuk mencari pasien

> ![image](https://github.com/user-attachments/assets/19edeeab-8eb4-4749-bdad-b79df708cf79)

Pada menu ini pengguna akan disuruh untuk memasukkan nama atau ID Pasien. Jika ditemukan maka akan menampilkan Nama Pasien (ID Pasien) – Tanggal Masuk RS – Golongan darah dan Riwayat Medisnya.

> ![image](https://github.com/user-attachments/assets/fc92960d-cc50-495b-8a3f-9cc632addbbc)

Namun, jika kita memasukkan nama atau ID Pasien yang tidak valid, maka program akan memberi tahu jika Pasien tidak ditemukan.

#### 0.	Kembali --> Digunakan untuk kembali ke menu utama


### •	Menu 3. Kelola Perawat
 
> ![image](https://github.com/user-attachments/assets/1fcfd7f6-6ee2-49a6-898e-2ae8bab216d9)

Pada menu ini memiliki beberapa pilihan:
#### 1.	Tambah Perawat : Untuk menambah perawat

> ![image](https://github.com/user-attachments/assets/882636f5-d3c2-423c-bc3e-68b919a77df9)

Saat menambahkan perawat baru, pengguna disuruh untuk mengisi ID, Nama, Umur, Alamat, Telepon, Shift, Departemen, dan perawat pun berhasil didaftarkan.

> ![image](https://github.com/user-attachments/assets/3f1b60e8-7721-447e-877f-1a4d293cb55c)

Namun jika pengguna memasukkan ID Perawat yang sudah ada program akan memberi tau jika sudah ada perawat dengan ID tersebut.
#### 2.	Lihat Semua Perawat : Untuk melihat semua perawat

> ![image](https://github.com/user-attachments/assets/b7d32830-2b91-4384-a755-da192c81fe2d)

Pada menu ini akan menampilkan Nama Perawat (ID Perawat) – Departmen – dan Shiftnya.
#### 3.	Cari Perawat : Mencari Perawat

> ![image](https://github.com/user-attachments/assets/0e9c20db-5dfb-4669-ab11-1bc5af5502f9)

Pada menu ini pengguna akan disuruh untuk memasukkan nama atau ID Perawat. Jika ditemukan maka akan menampilkan Nama Perawat (ID Perawat) – Departmen – dan Shiftnya.
 
> ![image](https://github.com/user-attachments/assets/c83a7921-c3d4-4d7d-855d-012687ed3360)

Namun, jika kita memasukkan nama atau ID Perawat yang tidak valid, maka program akan memberi tahu jika Perawat tidak ditemukan.
#### 0.	Kembali : Digunakan untuk kembali ke menu utama


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
#### 3.	Update Status Janji Temu

 > ![image](https://github.com/user-attachments/assets/0d09eaf7-e8a0-4555-883a-50e5dec42028)

Menu ini digunakan untuk mengupdate status janji temu dengan pilihan Pending, Selesai, dan Batal.
#### 4.	Lihat Janji Temu

 > ![image](https://github.com/user-attachments/assets/3f15609a-e2ab-47ae-9cfe-169128f32abd)

Menu ini digunakanuntuk melihat Janji Temu Pasien dengan memasukkan ID Pasien
#### 0.	Kembali : Digunakan untuk kembali ke menu utama

### •	Menu 5. Kelola Kamar

 > ![image](https://github.com/user-attachments/assets/3ae89081-23f6-46b9-b8fa-1b5a893d88be)

Pada menu ini memiliki beberapa pilihan:
#### 1.	Lihat Daftar Kamar

 > ![image](https://github.com/user-attachments/assets/743f7515-8992-48d9-8361-8929553d8fed)

Menu ini akan menampilkan nomor kamar, kelas kamar harga perhari dan status tersedia atau tidak.
#### 2.	Check-in Pasien

 > ![image](https://github.com/user-attachments/assets/8d64f601-f912-40b4-9679-cd09a3af232e)

Untuk Check-in Pasien akan disuruh untuk memilih kamar dan memasukkan ID Pasien yang terdaftar di sistem, jika berhasil akan menampilkan pesan bahwa pasien sudah berhasil check-in di kamar yang dipilih.

 > ![image](https://github.com/user-attachments/assets/0168b940-3c6d-4353-9575-d6653aeddbf5)

Jika memasukkan ID Pasien yang tidak terdaftar maka akan menampilkan Pasien tidak ditemukan.

 > ![image](https://github.com/user-attachments/assets/f29879e4-8b00-49f3-ad10-35e7831c1fc5)

Jika memasukkan Nomor Kamar yang tidak terdaftar maka akan menampilkan Kamar tidak ditemukan.
#### 3.	Check-Out Pasien

 > ![image](https://github.com/user-attachments/assets/e27c3c83-c9eb-4437-95fe-aba5dfd73a17)

Saat Check-Out Pasien, kita akan diminta untuk memasukkan nomor kamar yang digunakan dan jika digunakan maka akan menampilkan ID Pasien yang menggunakan dna check-out pun berhasil.

 > ![image](https://github.com/user-attachments/assets/499f8920-354a-4ab9-8266-11836c7f0f91)

Jika nomor kamar yang dipilih tidak ada pasien yang ada maka akan menampilkan pesan Kamar sudah kosong.

 > ![image](https://github.com/user-attachments/assets/b3fb1647-3247-4a21-aa55-d09e8e0ac1a4)

Jika memasukkan nomor kamar yang tidak terdaftar di sistem maka akan menampilkan kamar tidak ditemukan.
#### 0.	Kembali : Digunakan untuk kembali ke menu utama


### •	Menu 6. Kelola Rekam Medis
 
 > ![image](https://github.com/user-attachments/assets/a8b8d3d7-67ef-4f3a-a5e4-b06b7a669c31)

Pada menu ini memiliki beberapa pilihan:
#### 1.	Buat Rekam Medis Baru

 > ![image](https://github.com/user-attachments/assets/233ab26d-14df-485a-8dea-4f4ac0fc05ba)

Menu ini untuk membuat rekam medis baru dari pasien yang ada. Menu ini disuruh untuk memasukkan ID Pasien, ID Dokter, Diagnosis, Pengobatan, Catatan Tambahan, dan jika berhasil maka akan muncul ID Rekam Medis.

 > ![image](https://github.com/user-attachments/assets/7ac219ab-2979-4498-b05c-794cd1b5846e)

Jika memasukkan ID Pasien yang tidak terdaftar di sistem, maka akan menampilkan pesan Pasien dengan ID tersebut tidak ditemukan.

 > ![image](https://github.com/user-attachments/assets/22a9e0ae-f3ac-4fdd-b56d-f407a6a2b9b8)

Jika memasukkan ID Dokter yang tidak terdaftar di sistem, maka akan menampilka pesan Dokter dengan ID tersebut tidak ditemukan.
#### 2.	Lihat Rekam Medis Pasien

 > ![image](https://github.com/user-attachments/assets/8d89c453-1d7f-4d0e-baa8-8467df23a0d9)

Pada menu ini akan disuruh untuk memasukkan ID Pasien dan akan muncul rekam media pasien dengan ID tersebut.

 > ![image](https://github.com/user-attachments/assets/74bd14e6-55af-4a1d-b296-01ebd433f5cc)

Namun jika kita memasukkan ID Pasien yang belum di periksa atau memiliki rekam medis sebelumnya maka akan menampilkan peringatan tidak ada rekam medis untuk pasien tersebut.
#### 0.	Kembali : Digunakan untuk kembali ke menu utama


### •	Menu 7. Kelola Antrian Darurat
 
 > ![image](https://github.com/user-attachments/assets/2babfa9e-b478-4951-b4be-49cbe77cd59a)

Pada menu ini memiliki beberapa pilihan:
#### 1.	Tambah Pasien ke Antrian Darurat

 > ![image](https://github.com/user-attachments/assets/71965d58-efae-43f6-b3c2-a316e8b12c82)

Menu ini akan meminta untuk memasukkan ID Pasien dan akan menambahkannya ke antrian darurat yang harus segera ditangani.

 > ![image](https://github.com/user-attachments/assets/924ac07d-a7ba-4890-8395-a902ba6aee1b)

Namun jika kita memasukkan ID Pasien yang tidak ada pada sistem, maka akan menampilkan pesan bahwa pasien tidak ditemukan.
#### 2.	Proses Pasien Selanjutnya

 > ![image](https://github.com/user-attachments/assets/f4188c8a-a244-43f1-aebf-fd96669f84ed)

Menu ini akan menampilkan data pasien sesuai dengan urutan antrian darurat dan akan memproses penanganannya.
#### 3.	Lihat Antrian

 > ![image](https://github.com/user-attachments/assets/9b73e9fe-de29-4356-b60f-d73e57245bf9)

Menu ini akan menampilkan jumlah antrian pasien darurat dan juga menampilkan pasien darurat mana yang akan ditangani dengan menampilkan ID Pasiennya
#### 0.	Kembali : Digunakan untuk kembali ke menu utama


### •	Menu 8. Kelola Riwayat Operasi

 > ![image](https://github.com/user-attachments/assets/be35685e-aeed-4830-ac88-42e5e714701a)

Pada menu ini memiliki beberapa pilihan:
#### 1.	Tambah Riwayat Operasi

 > ![image](https://github.com/user-attachments/assets/8d21035f-87d9-459a-8c30-608def5ae511)

Pada menu ini pengguna akan disuruh untuk memasukkan ID Pasien yang akan dioperasi dan ID Dokter yang akan mengoperasi, serta prosedur operasi yang akan digunakan dan hasil operasinya, jika berhasil ditambahkan akan menampilkan pesan bahwa Riwayat operasi berhasil ditambahkan.
#### 2.	Lihat Riwayat Operasi Terakhir

 > ![image](https://github.com/user-attachments/assets/407b8c0a-eedf-4cf7-822d-8c0b77a1a605)

Pada menu ini akan menampilkan Riwayat terakhir operasi yang dilakukan dengan keterangan jam operasi, ID Pasien, ID Dokter, Prosedur, dan Hasilnya.
#### 3.	Lihat Semua Riwayat Operasi

 > ![image](https://github.com/user-attachments/assets/5bcf526c-7be4-4e15-8059-a5755fbd23a8)

Pada menu ini akan menampilkan semua Riwayat operasi yang telah dilakukan dengan keterangan jam operasi, ID Pasien, ID Dokter, Prosedur, dan Hasilnya
#### 0.	Kembali : Digunakan untuk kembali ke menu utama


### •	Menu 9. Cari Data

> ![image](https://github.com/user-attachments/assets/b9f7d66e-c9ff-4c2c-bf2d-625392c9b980)
Jika kita memasukkan kata kunci pada menu ini maka akan menampilkan hasil yang dicari.

> ![image](https://github.com/user-attachments/assets/fbcdd642-2157-4171-b585-b5fb43c32cfe)
Jika kita memasukkan kata kunci DOK maka program akan menampilkan hasil semua dokter yang ada di sistem.

 > ![image](https://github.com/user-attachments/assets/da858ed9-3ac6-481f-93ec-f5a5b1a06ee0)
Jika kita memasukkan kata kunci PAS, maka program akan menampilkan hasil semua pasien yang ada di sistem.

 > ![image](https://github.com/user-attachments/assets/e53d39fb-1414-40bb-835b-5060beb47757)
Jika kita memasukkan kata kunci PER, maka program akan menampilkan hasil semua perawat yang ada di sistem.

 > ![image](https://github.com/user-attachments/assets/60820186-a171-403b-b4c6-0d0f395d17d2)
Jika kita memasukkan kata kunci nama, maka program akan mencari dan menampilkan hasilnya, jika ada di sistem maka program akan menampilkan datanya.

 > ![image](https://github.com/user-attachments/assets/93384fcd-ba6e-4d02-9db4-1cc1c42f28ff)
Namun jika kita memasukkan kata kunci yang tidak ada di sistem, maka program akan memberi pesan bahwa tidak ditemukan data yang sesuai.

