# 🍜 Warmindo Online Ordering System

<p align="center">
  **Sistem Pemesanan Makanan dan Minuman Berbasis Web**
  <br />
  Aplikasi pemesanan Warmindo dengan halaman pelanggan dan dashboard admin untuk mengelola pesanan, stok, serta laporan transaksi.
</p>

---

## 📌 Tentang Proyek

**Warmindo Online Ordering System** merupakan aplikasi berbasis web yang dirancang untuk mempermudah proses pemesanan makanan dan minuman di Warmindo.

Aplikasi ini memiliki dua bagian utama, yaitu halaman pelanggan untuk melakukan pemesanan dan dashboard admin untuk memantau serta mengelola aktivitas operasional.

Seluruh fitur dikembangkan menggunakan HTML, CSS, JavaScript, dan Bootstrap. Penyimpanan data menggunakan **LocalStorage API**, sehingga aplikasi dapat berjalan tanpa backend atau database server.

## ✨ Fitur Utama

### 🛒 1. Halaman Pelanggan

Halaman pelanggan menyediakan antarmuka pemesanan yang memungkinkan pengguna memilih menu dan melakukan checkout secara langsung.

**Pemilihan Menu**
- Menampilkan daftar makanan dan minuman beserta harga.
- Menyediakan pilihan topping tambahan (opsional).
- Menyediakan pilihan suhu minuman (ICE / HOT).
- Mendukung kustomisasi setiap item pesanan.

**Manajemen Keranjang**
- Menambahkan dan menghapus item.
- Mengubah jumlah pesanan secara real-time.
- Menghitung total harga secara otomatis.
- Menyimpan data keranjang menggunakan LocalStorage.

**Informasi Pemesan**
- Input nama pemesan.
- Input nomor meja.
- Pilihan metode pembayaran Cash atau QRIS.

**Checkout**
- Memproses pesanan pelanggan.
- Menyimpan transaksi ke LocalStorage sebagai riwayat pesanan.
- Menghubungkan data pesanan dengan dashboard admin melalui penyimpanan browser.

### ⚙️ 2. Dashboard Admin

Dashboard admin digunakan untuk memantau pesanan dan mengelola kebutuhan operasional Warmindo.

**Laporan Pesanan Harian**
- Menampilkan daftar pesanan beserta detail transaksi.
- Menampilkan nama pemesan dan nomor meja.
- Menampilkan rincian harga dan metode pembayaran.
- Menampilkan waktu transaksi.
- Menandai pesanan yang telah selesai.
- Menghitung total pendapatan harian.
- Mengunduh laporan transaksi dalam format CSV.

**Manajemen Stok**
- Mengubah jumlah stok makanan secara langsung.
- Menyimpan perubahan stok secara otomatis.
- Menampilkan notifikasi ketika stok berhasil diperbarui.

**Kritik dan Saran**
- Menampilkan pesan yang dikirim pelanggan.
- Menyediakan informasi nama, email, isi pesan, dan waktu pengiriman.

**Rincian Pesanan**
- Menampilkan detail item dalam pop-up modal.
- Menghitung subtotal setiap menu.

**Reset Data Harian**
- Mengatur ulang data laporan secara otomatis setiap hari.

## 🖥️ Tampilan dan Halaman

| Halaman | File |
|---|---|
| Halaman pemesanan pelanggan | `pelanggan.html` |
| Dashboard admin | `admin.html` |

## 🛠️ Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| HTML5 | Struktur halaman web |
| CSS3 | Styling dan tata letak |
| Bootstrap 5.3.3 | Komponen dan responsive layout |
| JavaScript ES6 | Logika aplikasi dan interaksi |
| LocalStorage API | Penyimpanan data pada browser |
| Font Awesome | Ikon antarmuka |

## 🚀 Cara Menjalankan Proyek

1. Clone repository:

   ```bash
   git clone https://github.com/tanzz15/Warmindo-Manoban.git
   ```

2. Buka folder proyek.
3. Jalankan file `pelanggan.html` melalui browser untuk mengakses halaman pemesanan.
4. Buka file `admin.html` untuk mengakses dashboard admin.

Tidak diperlukan instalasi backend maupun database server.

## ⚠️ Catatan

Proyek ini menggunakan LocalStorage sebagai media penyimpanan data, bukan database terpusat. Data tersimpan pada browser yang digunakan sehingga aplikasi ini ditujukan sebagai proyek demonstrasi dan pembelajaran pengembangan aplikasi web, bukan sistem produksi multi-pengguna.

## 🎯 Tujuan Pengembangan

Proyek ini dibuat untuk menerapkan kemampuan pengembangan aplikasi web, khususnya dalam:
- Membangun antarmuka pengguna.
- Mengimplementasikan interaksi menggunakan JavaScript.
- Mengelola data menggunakan LocalStorage.
- Membuat sistem keranjang dan checkout.
- Mengembangkan dashboard admin dan laporan transaksi.

---

<p align="center">
  **Developed by [tanzz15](https://github.com/tanzz15)**
</p>
