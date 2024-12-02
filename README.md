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




