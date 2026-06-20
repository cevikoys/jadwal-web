# Web Programming & PHP Fundamentals Labs

Selamat datang di repositori latihan pemrograman web! Repositori ini berisi kumpulan modul praktikum dasar untuk pengembangan web, mulai dari perancangan antarmuka statis dengan **HTML5 & CSS3** hingga pemrosesan sisi server (*server-side*) dinamis menggunakan **PHP**.

## Struktur dan Isi Repositori

Proyek-proyek di dalam repositori ini dikelompokkan berdasarkan fungsinya:

### 1. Antarmuka Statis & Desain (HTML & CSS)
* **Aplikasi Jadwal Akhir Pekan:**
    * `jadwal.html`: Halaman interaktif berbentuk tabel yang mendokumentasikan jadwal kegiatan akhir pekan (weekend) dilengkapi dengan elemen *checkbox* aksi.
    * `style.css`: Pengaturan tata letak tabel menggunakan CSS Flexbox, pewarnaan tema (`goldenrod` & `silver`), serta penataan responsif komponen tabel.

### 2. Pemrograman Sisi Server (PHP)
* **Dasar-Dasar PHP & Variabel:**
    * `mod1.php`: Latihan operasi aritmatika, deklarasi variabel, dan cetak string (menampilkan informasi mahasiswa).
    * `mod2.php`: Implementasi struktur data Array dan penggunaan fungsi `count()`.
    * `mod3_KonversiTipe.php`: Latihan konversi tipe data (*type casting*) ke tipe Double, Integer, dan String.
* **Manipulasi Waktu & Tanggal:**
    * `mod4_tanggal.php`: Menampilkan waktu standar langsung dari server lokal.
    * `Tugas1_tanggal.php`: Modifikasi dan kustomisasi berbagai variasi format tampilan fungsi `date()` di PHP.

### 3. Aplikasi Form Dinamis
* **`biodata/`**: Folder yang berisi halaman form input biodata (`Tugas2.php`) yang dilengkapi dengan fungsi sanitasi input aman (`htmlspecialchars`, `trim`) serta kustomisasi tampilan dengan `style2.css`.
* **`kalkulator/`**: Folder aplikasi web hitung luas persegi panjang (`kalkulator.php`) menggunakan metode POST untuk memproses data input pengguna.
