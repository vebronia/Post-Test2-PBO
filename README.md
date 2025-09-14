# Post-Test2-PBO Perlengkapan Alat Olahraga
| Nama                      | NIM           | Kelas             |
|---------------------------|---------------|-------------------|
|  Vebronia vitania Lusi    | 2409116112    | Sistem Informasi C|

**DESKRIPSI PROGRAM**

Program ini merupakan sistem sederhana berbasis Java untuk mengelola data perlengkapan olahraga. Data disimpan menggunakan ArrayList dan dikelola melalui menu pilihan. Pengguna dapat:
Menambah data properti dengan validasi agar ID unik dan jumlah hanya angka.
Menampilkan semua data yang tersimpan.
Mengupdate data berdasarkan ID.
Menghapus data berdasarkan ID.
Mencari data berdasarkan ID atau nama properti.
Program akan terus berjalan sampai pengguna memilih menu keluar.

**STRUKTUR PACKAGES**

<img width="248" height="113" alt="image" src="https://github.com/user-attachments/assets/531042a2-9120-4618-8dde-1133cb9a26ce" />

**Fungsi Packages ServiceProperti.java**
Ini adalah kelas layanan (service class) yang:
Mengelola daftar properti olahraga (alat olahraga), Menggunakan ArrayList untuk menyimpan objek Properti, Menggunakan Scanner untuk input dari pengguna lewat CLI (Command Line Interface), Menyediakan fitur lengkap: CRUD + Search.

**Fungsi AlatOlahraga.java**

Ini adalah kelas utama (main class) yang: Menjadi titik masuk program (method main()), Menyediakan menu interaktif berbasis console (CLI), Menggunakan Scanner untuk membaca input dari pengguna, Menggunakan objek ServiceProperti untuk menjalankan fitur: Tambah data, Tampilkan data, Update data, Hapus data, Cari data, Mengatur looping menu hingga user memilih keluar (pilihan = 0)

**Fungsi Properti.java**
Ini adalah kelas model (data class) yang: Mewakili satu data properti olahraga 
Menyimpan tiga atribut utama: id → ID unik dari properti,
nama → Nama alat olahraga, jumlah → Jumlah unit yang tersedia.
Menyediakan:
Constructor untuk membuat objek Properti baru.
Getter dan Setter untuk mengakses dan memodifikasi data.
toString() untuk mencetak data dalam format rapi saat dipanggil di console.

**TAMBAH PERLENGKAPAN**

<img width="158" height="156" alt="image" src="https://github.com/user-attachments/assets/f8252f47-9d2e-4285-ba28-067bb0b76b3b" />

Langkah:
1.Program menampilkan menu utama dengan 5 pilihan.
2.Pilih menu 1 untuk Tambah Perlengkapan.
3.Masukan id perlengkapan
4.Masukkan nama perlengkapan, misalnya: Shuttlecock.
5.Masukkan jumlah, misalnya: 10.
Data otomatis tersimpan ke dalam ArrayList.

**TAMPILKAN PERLENGKAPAN**

<img width="255" height="172" alt="image" src="https://github.com/user-attachments/assets/a7a45a9a-1c0d-408a-a0b3-40e97f4440d0" />

Langkah:
1.Pilih menu 2 untuk Tampilkan Perlengkapan.
2.Program akan mengecek apakah daftar perlengkapan kosong atau tidak.
3.Jika ada data, tampilkan semua perlengkapan beserta jumlahnya.

**UPDATE PERLENGKAPAN**

<img width="204" height="167" alt="image" src="https://github.com/user-attachments/assets/1cfce6ba-adbb-4bab-8bfb-eac5272c91c1" />

Langkah:

1.Pilih menu 3 untuk Update Perlengkapan.
2.Program meminta nomor atau ID perlengkapan yang ingin diupdate.
3.Masukkan misalnya 190 (Ring basket).
4.Masukkan nama baru, misalnya Net Bulu tangkis.
5.Masukkan jumlah baru, misalnya 2.
6.Program akan mengganti data lama dengan data baru dan menampilkan pesan berhasil.

**MENGHAPUS PERLENGKAPAN**

<img width="229" height="143" alt="image" src="https://github.com/user-attachments/assets/cd222a06-af62-4ff5-b0e0-cffe138748f0" />

Langkah:
1.Pilih menu 4 untuk Hapus Perlengkapan.
2.Program meminta nomor atau ID perlengkapan yang ingin dihapus. Masukkan misalnya 112 (shutle kock).
3.Program menghapus data dan menampilkan pesan: "Perlengkapan berhasil dihapus".

**MENCARI PERLENGKAPAN**

<img width="263" height="138" alt="image" src="https://github.com/user-attachments/assets/e623dd73-8faf-40c6-985b-bf5f20b035b0" />

Langkah:
1.Pilih menu 5 untuk Cari Perlengkapan.
2.Masukkan kata kunci atau ID nya, misalnya 190.
3.Program menampilkan semua data yang cocok dengan kata kunci, baik ID maupun nama.

**KELUAR**

<img width="406" height="172" alt="image" src="https://github.com/user-attachments/assets/bb66623d-1ab4-4926-bc9f-672ddf41fff8" />

Langkah:
1.Pilih menu 0 untuk Keluar.
2.Program otomatis berhenti.





