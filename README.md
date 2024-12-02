# LAPORAN PRAKTIKUM 6

# CODE PROGRAM DAFTAR NILAI

## Step 1 : Inisialisasi Data

Tambahkan variabel data_mahasiswa sebagai list kosong yang digunakan untuk menyimpan data mahasiswa, setiap elemen dalam list adalah dictionary yang berisi informasi mahasiswa berupa Nilai Mahasiswa untuk kasus ini :

![gambar](https://github.com/M-Rakha/Labpy06/blob/374318d947c28613268d2a3a13751015dc87dee5/Cuplikan%20layar%202024-12-02%20201418.png)

## Step 2 : Fungsi tambah()

Fungsi ini untuk menambahkan data mahasiswa baru yang akan diproses sebagai :

- Meminta pengguna memasukkan nama dan nilai mahasiswa.
- Data yang dimasukkan disimpan dalam bentuk dictionary {"nama": nama, "nilai": nilai}.
- Dictionary ini ditambahkan ke dalam list data_mahasiswa menggunakan .append().

![gambar](https://github.com/M-Rakha/Labpy06/blob/70b1c499657cb562d3753e291c9e18fcbb9d1013/Cuplikan%20layar%202024-12-02%20202534.png)

## Step 3 : Fungsi tampilkan()

Fungsi ini digunakan untuk menampilkan data nilai mahasiswa ke dalam data_mahasiswa. Tujuan dapat menampilkan seluruh data mahasiswa. Menu ini mampu mengecek apakah data_mahasiswa kosong, Jika tidak kosong data ditampilkan dalam bentuk tabel sesuai data yang telah ditambahkan, Menggunakan enumerate untuk memberikan nomor pada setiap mahasiswa dalam daftar :

![gambar](https://github.com/M-Rakha/Labpy06/blob/f821be5bd864138bd3116716016438a197d0efd2/Cuplikan%20layar%202024-12-02%20202754.png)

## Step 4 : Fungsi hapus(nama)

Menghapus data mahasiswa berdasarkan nama yang dimasukan/input, sebagai proses menggunakan list comprehension untuk membuat daftar baru yang tidak berisi mahasiswa dengan nama yang dimasukkan, variabel data_mahasiswa diperbarui dengan daftar baru ini :

![gambar])(https://github.com/M-Rakha/Labpy06/blob/bd8ffa4c1c81f6f42e0883088c37106aad980d87/Cuplikan%20layar%202024-12-02%20202956.png)

## Step 5 : Fungsi ubah(nama)

Fungsi yang akan mengubah nilai mahasiswa berdasarkan nama yang dimasukan/input, mencari data mahasiswa dengan nama tertentu di dalam data_mahasiswa. Jika data ditemukan, maka nilai mahasiswa tersebut diperbarui sesuai input pengguna :

![gambar](https://github.com/M-Rakha/Labpy06/blob/afb565e68b9b4e42449ee1b75d5fa68aa50f7042/Cuplikan%20layar%202024-12-02%20203209.png)

## Step 6 : Fungsi menu()

Menyediakan Tampilan menu sebagai opsi pengguna, menggunakan perulangan while untuk terus menampilkan menu namun untuk menghentikan program masukan break sebagai perhentian :

Pilihan menu:

- 1: Memanggil fungsi tambah().
- 2: Memanggil fungsi tampilkan().
- 3: Memanggil fungsi hapus(nama).
- 4: Memanggil fungsi ubah(nama).
- 5: Menghentikan program.

![gambar](https://github.com/M-Rakha/Labpy06/blob/59538a06fb09fddd161ce4374a5a9d2a8f03cd61/Cuplikan%20layar%202024-12-02%20204224.png)

![gambar](https://github.com/M-Rakha/Labpy06/blob/b57c3236828450e9d494684d7eeea6a7c5e7530a/Cuplikan%20layar%202024-12-02%20204249.png)

## Step 7 : Closed Program

Pakai menu() untuk memulai sebuah program ketika dirun :

![gambar](https://github.com/M-Rakha/Labpy06/blob/16ff634ec615b66a2756237ce6e4e10f9a4cb24d/Cuplikan%20layar%202024-12-02%20204522.png)

## Step 8 : Run Program

Tahap akhir adalah uji coba code program yang sudah dibuat dengan mencoba berbagai kemungkinan yang ada.

### Case 1 :

Kondisi pertama kita akan coba melihat tabel dengan inputkan 2 tampa menambahkan data/masih kosong, maka akan ditampilkan isi tabel masih belum ada datanya, akan ditampilkan 'Belum ada Data Mahasiswa' :

![gambar](https://github.com/M-Rakha/Labpy06/blob/3ebf36c70a43f9fb34c2d45693a02f74ba7e0a51/Cuplikan%20layar%202024-12-02%20204820.png)

### Case 2 :

Kondisi kedua selanjutnya mencoba menambahkan data mahasiswa pada tabel, dengan menginputkan 1 untuk menambahkan data mahasiswa.

Untuk perawalan, mencoba memasukan satu data mahasiswa :
- Nama : MUHAMMAD RAKHA GHANI
- Nilai : 89

![gambar](https://github.com/M-Rakha/Labpy06/blob/c5f1aa4b04e6b8f812a7ed02cfa4095bec2b9ba5/Cuplikan%20layar%202024-12-02%20205343.png)

### Case 3 :

Selanjutnya, kondisi ketiga kembali dengan menginputkan 2 untuk melihat daftar data mahasiswa pada tabel, namun dari kondisi sebelumnya yang sudah menambahkan data mahasiswa saya coba tambahkan 3 data mahasiswa lagi. maka akan terlihat pada isi tabel :

![gambar](https://github.com/M-Rakha/Labpy06/blob/528103978b9b01cdd0e5b243e6ac1c27bef6efe7/Cuplikan%20layar%202024-12-02%20210126.png)

### Case 4 :

Masuk kondisi keempat kita akan coba mengubah data, ada data yang salah diinputkan pada Nilai Mahasiswa 89 diubah menjadi 90, sebelum itu inputkan 4 untuk mengubah maka akan ditampilkan daftar nilai tabel dan diminta untuk memasukan nama mahasiswa yang ingin diubah data nilai -nya. User diminta memasukan kembali data valid yang akan diubah.

Coba memasukan data mahasiswa berikut :
- Nama : MUHAMMAD RAKHA GHANI
- Nilai : 90




