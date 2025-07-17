# Tugas_SBD

# 🎉  SISTEM CRUD "APLIKASI MANAJEMEN OBAT OBATAN APOTEK"

<img width="388" height="480" alt="Image" src="https://github.com/user-attachments/assets/30cb911c-0384-4654-9413-ad488137d6d9" />

🔹 Aplikasi Java pada gambar tersebut adalah aplikasi manajemen data obat sederhana dengan fungsi CRUD (Create, Read, Update, Delete). Aplikasi ini dibuat untuk memenuhi kebutuhan pengelolaan data obat secara digital, menggantikan metode manual yang kurang efisien, serta sebagai bagian dari latihan penerapan konsep pemrograman berorientasi objek dan GUI di Java.

# Tujuan Utama Aplikasi Manajemen Obat obatan Apotek Ini:

## ✅ Mencatat Data Obat dengan Rapi
Menyimpan informasi penting seperti kode obat, nama obat, kategori, dan kode satuan ke dalam sistem yang mudah diakses.

## 🧾 Mempermudah Pencarian dan Pengelompokan Obat
Dengan adanya kolom seperti kategori obat, pengguna bisa mengelompokkan obat berdasarkan jenis, misalnya: makanan, obat bebas, dll.

## ✍️ Mendukung Proses CRUD (Create, Read, Update, Delete)
Pengguna bisa:
- Menambahkan obat baru
- Mengedit data jika terjadi kesalahan
- Menghapus obat yang tidak digunakan
- Melihat semua data yang tersimpan dengan mudah

## 🕒 Menghemat Waktu dan Mengurangi Kesalahan Manual
Dibandingkan pencatatan manual, aplikasi ini membantu menghindari duplikasi data dan kesalahan penulisan.

## 📊 Menjadi Dasar untuk Sistem Manajemen Stok atau Penjualan Obat
Aplikasi ini bisa dikembangkan lebih lanjut menjadi sistem inventori lengkap yang mencatat stok, harga, dan transaksi obat.

## ✨ Fitur fitur
- Kolom Kode obat
- Kolom Nama Obat 
- Kolom Kategori obat
- Kolom Kode Satuan
- Tombol Tambah
- Tombol Edit
- Tombol Hapus
- Tombol Reset
- TABEL

## 🚀 Berikut beberapa penjelasan dari setiap Gambar dari database PHPMyAdmin

<img width="232" height="354" alt="Image" src="https://github.com/user-attachments/assets/4194b2bb-a357-4d1f-8bad-ea829bbf1805" />
<img width="853" height="591" alt="Image" src="https://github.com/user-attachments/assets/cf8b3bb2-2a3e-4e69-81ce-a4266ca4a9a2" />

#   Dari gambar ini saya menggunakan phpmyadmin sebagai Alat berbasis web ini untuk mengelola database MySQL dengan cara yang lebih mudah tanpa harus mengetikkan query SQL secara manual. Di dalam phpMyAdmin ini terdapat sebuah database bernama apotek. Ini adalah tempat penyimpanan data yang digunakan oleh aplikasi, Tabel ini yang berinteraksi langsung dengan aplikasi Java melalui koneksi database (misalnya dengan JDBC).

<img width="912" height="543" alt="Image" src="https://github.com/user-attachments/assets/2d650d5e-e8e9-4825-9dd5-960f223b50a6" />
<img width="911" height="648" alt="Image" src="https://github.com/user-attachments/assets/6fac2075-830b-47da-a5e2-4194b1e1e47c" />

##  Gambar tersebut menunjukkan tampilan **phpMyAdmin** yang sedang membuka tabel `obat` dari database bernama `apotek`. Dalam gambar ini, tampak bahwa tabel `obat` berisi delapan baris data yang mencatat berbagai informasi terkait obat-obatan. Setiap baris merepresentasikan satu data obat dengan empat kolom utama, yaitu `kode_obat`, `nama_obat`, `kategori_obat`, dan `kode_satuan`. Kolom `kode_obat` berisi kode unik untuk setiap obat seperti a001 atau b002, sedangkan `nama_obat` mencatat nama obat seperti “rhinos sr” atau “paracetamol”. Kolom `kategori_obat` menunjukkan jenis obat, misalnya “makanan” atau “obat bebas”, dan `kode_satuan` merepresentasikan kode satuan dari masing-masing obat.

##  Melalui tampilan ini, pengguna dapat mengedit, menyalin, atau menghapus setiap data menggunakan tombol yang tersedia pada sisi kiri setiap baris data. Data yang ditampilkan pada tabel ini berasal dari hasil query `SELECT * FROM obat`, yang berarti semua data dalam tabel `obat` ditampilkan secara lengkap. Tabel ini merupakan bagian penting dari aplikasi manajemen obat berbasis Java. Aplikasi tersebut berinteraksi langsung dengan database ini, sehingga semua aktivitas penambahan, pengeditan, dan penghapusan data yang dilakukan melalui aplikasi akan tercermin di dalam tabel ini. Dengan menggunakan phpMyAdmin, pengelolaan database menjadi lebih mudah tanpa perlu menulis perintah SQL secara manual.







