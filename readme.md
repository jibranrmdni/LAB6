# TUGAS PRAKTIKUM 7
# Data Diri

Nama : JIbran ramdani

NIM : 312410419

Kelas : TI,24.A.3

# Flowchart 

![Cuplikan layar 2024-12-02 190840](https://github.com/user-attachments/assets/5dda95c8-e2a1-47a2-a135-fbdf45764457)


# input dan outpu dari Praktikum 7

## 1. input tambah data 

![Cuplikan layar 2024-12-02 192813](https://github.com/user-attachments/assets/1dd56920-66a6-4705-a3a7-897711953af1)


## 2. input tampilkan data
![Cuplikan layar 2024-12-02 193143](https://github.com/user-attachments/assets/835c39aa-e954-41df-8445-d148566e2cba)


## 3. input hapus data

![Cuplikan layar 2024-12-02 194017](https://github.com/user-attachments/assets/fb8b7a81-cb83-4e04-a3c0-e4b45f9bdc88)



## 4.  input ubah data

![image](https://github.com/user-attachments/assets/77d51d4a-cf36-4821-936f-549f0bdfca30)



# Penjelasan Algoritma:

## Program ini merupakan aplikasi manajemen data mahasiswa dengan beberapa fungsi utama:

1. Struktur Data:
   - Menggunakan list `data_mahasiswa` untuk menyimpan data mahasiswa
   - Setiap mahasiswa disimpan sebagai dictionary dengan dua kunci: 'nama' dan 'nilai'

2. Fungsi Utama:
   a. `tambah()`:
      - Memungkinkan pengguna menambahkan data mahasiswa baru
      - Meminta input nama dan nilai
      - Menyimpan data ke dalam list `data_mahasiswa`

   b. `tampilkan()`:
      - Menampilkan seluruh data mahasiswa yang tersimpan
      - Jika tidak ada data, menampilkan pesan khusus
      - Menampilkan data dalam format tabel dengan nomor urut

   c. `hapus(nama)`:
      - Menghapus data mahasiswa berdasarkan nama
      - Menggunakan list comprehension untuk membuat list baru tanpa nama yang dimaksud

   d. `ubah(nama)`:
      - Mengubah nilai mahasiswa berdasarkan nama
      - Mencari mahasiswa dengan nama tertentu
      - Memperbarui nilai jika nama ditemukan

   e. `menu()`:
      - Fungsi utama yang menjalankan program
      - Menampilkan menu pilihan
      - Menggunakan loop while untuk terus menampilkan menu
      - Memproses pilihan pengguna dengan percabangan (if-elif)
      - Memberikan opsi untuk keluar dari program

3. Alur Kerja Program:
   - Program dimulai dengan memanggil fungsi `menu()`
   - Pengguna dapat memilih berbagai operasi
   - Program akan terus berjalan hingga pengguna memilih keluar


