SISTEM MANAJEMEN PERPUSTAKAAN DIGITAL

DESKRIPSI PROGRAM Program ini merupakan aplikasi berbasis Java yang digunakan untuk membantu pengelolaan data buku perpustakaan. Sistem dibuat menggunakan konsep struktur data dan algoritma seperti CRUD, searching, sorting, dan file handling. Program berjalan melalui console atau terminal dan menggunakan file txt sebagai media penyimpanan data.

FITUR PROGRAM

Tambah data buku
Menampilkan seluruh data buku
Edit data buku berdasarkan ID
Hapus data buku menggunakan soft delete
Cari buku berdasarkan nama menggunakan Linear Search
Cari buku berdasarkan ID menggunakan Binary Search
Cari buku berdasarkan kategori
Sorting data berdasarkan ID
Sorting data berdasarkan judul buku
Sorting data berdasarkan stok buku
Update status buku
Menampilkan statistik data buku
Save data ke file txt
Load data dari file txt
BAHASA DAN TOOLS

Bahasa Pemrograman: Java
Java Development Kit (JDK) versi 8 atau lebih baru
CARA MENJALANKAN PROGRAM

Pastikan Java JDK sudah terinstall pada komputer.

Simpan file program dengan nama: ProjekPerpus.java

Buka terminal atau command prompt pada folder project.

Compile program menggunakan perintah: javac ProjekPerpus.java

Setelah proses compile berhasil, jalankan program menggunakan perintah: java ProjekPerpus

CARA PENGGUNAAN PROGRAM Setelah program dijalankan, akan muncul menu utama sistem manajemen perpustakaan digital. Pengguna dapat memilih menu sesuai kebutuhan dengan memasukkan nomor pilihan yang tersedia.

MENU PROGRAM :

Tambah Data Buku
Tampilkan Semua Buku
Edit Data Buku Berdasarkan ID
Hapus Data Buku Berdasarkan ID
Cari Buku Berdasarkan Nama
Cari Buku Berdasarkan ID
Cari Buku Berdasarkan Kategori
Urutkan Buku Berdasarkan ID
Urutkan Buku Berdasarkan Judul
Urutkan Buku Berdasarkan Stok
Update Status Buku
Status Ketersediaan Buku
Statistik Data Buku
Save Data Buku
Load Data Buku
Keluar
PENYIMPANAN DATA Program menggunakan file dataBuku.txt untuk menyimpan data buku. Data disimpan menggunakan format: id;judul;kategori;stok;status

CONTOH DATA : 1;Algoritma dan Pemrograman;Teknologi;10;tersedia Fitur save data digunakan untuk menyimpan data ke file txt, sedangkan fitur load data digunakan untuk membaca kembali data dari file tersebut.

CATATAN

Program berjalan berbasis console atau terminal.
Program belum menggunakan database.
Pastikan file dataBuku.txt berada pada folder yang sama dengan file Java.
Program menggunakan array dengan kapasitas maksimal 100 data buku.
Jika file data tidak ditemukan, sistem akan menampilkan pesan error sesuai kondisi program.
