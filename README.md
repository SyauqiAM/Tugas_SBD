# Tugas_Sistem Basis Data 

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

# 🚀 Berikut beberapa penjelasan setiap Gambar dari database PHPMyAdmin

<img width="232" height="354" alt="Image" src="https://github.com/user-attachments/assets/4194b2bb-a357-4d1f-8bad-ea829bbf1805" /><img width="853" height="591" alt="Image" src="https://github.com/user-attachments/assets/cf8b3bb2-2a3e-4e69-81ce-a4266ca4a9a2" />

Dari gambar ini saya menggunakan phpmyadmin sebagai Alat berbasis web ini untuk mengelola database MySQL dengan cara yang lebih mudah tanpa harus mengetikkan query SQL secara manual. Di dalam phpMyAdmin ini terdapat sebuah database bernama apotek. Ini adalah tempat penyimpanan data yang digunakan oleh aplikasi, Tabel ini yang berinteraksi langsung dengan aplikasi Java melalui koneksi database (misalnya dengan JDBC).


<img width="912" height="543" alt="Image" src="https://github.com/user-attachments/assets/2d650d5e-e8e9-4825-9dd5-960f223b50a6" />
<img width="911" height="648" alt="Image" src="https://github.com/user-attachments/assets/6fac2075-830b-47da-a5e2-4194b1e1e47c" />

 Gambar tersebut menunjukkan tampilan **phpMyAdmin** yang sedang membuka tabel `obat` dari database bernama `apotek`. Dalam gambar ini, tampak bahwa tabel `obat` berisi delapan baris data yang mencatat berbagai informasi terkait obat-obatan. Setiap baris merepresentasikan satu data obat dengan empat kolom utama, yaitu `kode_obat`, `nama_obat`, `kategori_obat`, dan `kode_satuan`. Kolom `kode_obat` berisi kode unik untuk setiap obat seperti a001 atau b002, sedangkan `nama_obat` mencatat nama obat seperti “rhinos sr” atau “paracetamol”. Kolom `kategori_obat` menunjukkan jenis obat, misalnya “makanan” atau “obat bebas”, dan `kode_satuan` merepresentasikan kode satuan dari masing-masing obat.
Melalui tampilan ini, pengguna dapat mengedit, menyalin, atau menghapus setiap data menggunakan tombol yang tersedia pada sisi kiri setiap baris data. Data yang ditampilkan pada tabel ini berasal dari hasil query `SELECT * FROM obat`, yang berarti semua data dalam tabel `obat` ditampilkan secara lengkap. Tabel ini merupakan bagian penting dari aplikasi manajemen obat berbasis Java. Aplikasi tersebut berinteraksi langsung dengan database ini, sehingga semua aktivitas penambahan, pengeditan, dan penghapusan data yang dilakukan melalui aplikasi akan tercermin di dalam tabel ini. Dengan menggunakan phpMyAdmin, pengelolaan database menjadi lebih mudah tanpa perlu menulis perintah SQL secara manual.


# 🚀 Berikut beberapa penjelasan setiap Gambar dari Java Netbeans


<img width="388" height="480" alt="Image" src="https://github.com/user-attachments/assets/72432d00-362d-4a1d-b62d-80533c6c8d7e" />

Gambar tersebut menampilkan antarmuka dari sebuah aplikasi desktop berbasis Java yang berfungsi untuk mengelola data obat. Aplikasi ini dirancang dengan menggunakan komponen antarmuka grafis (GUI), Judul pada tampilan bertuliskan "OBAT", yang menunjukkan bahwa aplikasi ini digunakan untuk pencatatan atau manajemen data obat. Di sisi kiri atas, terdapat empat kolom input yang memungkinkan pengguna untuk mengisi data, yaitu `kode_obat`, `nama_obat`, `kategori_obat`, dan `kode_satuan`. Masing-masing kolom tersebut mewakili data penting dari suatu obat yang akan disimpan dalam sistem. Di bawah kolom input, terdapat empat tombol aksi yaitu "Tambah", "Edit", "Hapus", dan "Reset". Tombol "Tambah" digunakan untuk menyimpan data obat baru ke dalam sistem. Tombol "Edit" memungkinkan pengguna untuk mengubah data obat yang sudah ada, sedangkan tombol "Hapus" digunakan untuk menghapus data obat yang dipilih dari tabel. Tombol "Reset" digunakan untuk mengosongkan semua kolom input agar siap diisi ulang. Di bagian bawah tampilan terdapat sebuah tabel yang menampilkan daftar obat yang telah dimasukkan. Tabel ini menampilkan kolom `Kode Obat`, `Nama Obat`, `Kategori Obat`, dan `Kode Satuan` sebagai ringkasan data yang telah disimpan. Aplikasi ini sangat berguna untuk mendukung pengelolaan data obat secara digital dan terstruktur, serta bisa dihubungkan dengan database MySQL untuk penyimpanan data secara permanen.


<img width="488" height="577" alt="Image" src="https://github.com/user-attachments/assets/b8f207f9-a2ea-4812-b967-82b5316c474f" />


Dalam gambar ini, tombol "Edit" tampak aktif atau sedang ditekan, yang menunjukkan bahwa pengguna akan atau sedang melakukan proses pengeditan terhadap salah satu baris data obat yang telah ditampilkan pada tabel di bagian bawah. Tabel tersebut berfungsi untuk menampilkan seluruh data obat yang telah dimasukkan, dengan kolom-kolom berupa Kode Obat, Nama Obat, Kategori Obat, dan Kode Satuan. Saat proses edit berlangsung, pengguna dapat memilih baris data tertentu dari tabel, lalu mengubah isinya melalui input field di atas, dan menekan tombol "Edit" untuk memperbarui data tersebut dalam database. Aplikasi ini sangat berguna untuk memastikan bahwa data obat dapat selalu diperbarui dan dijaga keakuratannya, serta memberikan pengalaman pengguna yang praktis dalam pengelolaan data berbasis GUI.


<img width="288" height="380" alt="Image" src="https://github.com/user-attachments/assets/644eb5c4-a016-48d8-a4fe-bfa5ef81d752" />


Tabel yang ditampilkan berisi data lengkap dari beberapa obat yang sudah tersimpan di dalam sistem, dengan kolom seperti Kode Obat, Nama Obat, Kategori Obat, dan Kode Satuan. Untuk melakukan proses penghapusan, pengguna terlebih dahulu memilih salah satu baris data pada tabel, kemudian menekan tombol "Hapus" untuk menghapus data tersebut dari database. Setelah data dihapus, baris tersebut akan hilang dari tabel tampilan. Fungsi ini sangat penting untuk menjaga integritas dan akurasi data, serta mempermudah proses manajemen data obat apabila ada entri yang tidak lagi digunakan atau dimasukkan secara tidak sengaja. Aplikasi ini merupakan contoh aplikasi CRUD (Create, Read, Update, Delete) sederhana yang memanfaatkan Java sebagai bahasa pemrograman dan database MySQL untuk menyimpan data.


<img width="296" height="381" alt="Image" src="https://github.com/user-attachments/assets/0de55a3c-eb06-4640-81e5-c27989d64232" />


Di bagian bawah kolom input, terdapat empat tombol utama yaitu "Tambah", "Edit", "Hapus", dan "Reset". Pada kondisi ini, jika pengguna ingin membatalkan proses input atau membersihkan form, maka tombol "Reset" dapat ditekan. Fungsi dari tombol "Reset" adalah untuk mengosongkan semua isian pada kolom input agar pengguna dapat memulai entri data baru tanpa gangguan dari data sebelumnya. Tabel di bagian bawah masih menampilkan seluruh data obat yang telah tersimpan dalam sistem, berisi delapan baris data dengan kolom Kode Obat, Nama Obat, Kategori Obat, dan Kode Satuan. Fungsi reset sangat berguna dalam mencegah kesalahan input data dan memastikan bahwa pengguna dapat memulai proses entri baru dengan kondisi form yang bersih dan siap digunakan kembali.


<img width="294" height="382" alt="Image" src="https://github.com/user-attachments/assets/e4113d6a-622c-460e-b3b4-842507591057" />


Meskipun form input sudah kosong, tabel di bagian bawah masih menampilkan data obat secara lengkap, yang artinya fungsi reset hanya memengaruhi tampilan form input dan tidak menghapus data yang ada dalam database. Tabel tersebut masih menunjukkan data-data seperti kode obat a001 untuk “rhinos sr” hingga b004 untuk “multivitamin”, lengkap dengan kategori dan kode satuan masing-masing.




