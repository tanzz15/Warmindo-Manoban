## 🍜 Warmindo Online Ordering System

Project ini merupakan sistem pemesanan makanan Warmindo berbasis web yang terdiri dari halaman user (pemesan) dan dashboard admin.
Seluruh fitur berjalan menggunakan HTML, CSS, JavaScript, Bootstrap, dan seluruh data disimpan menggunakan LocalStorage tanpa backend.

Project ini terdiri dari dua bagian utama:
1. pelanggan.html → Halaman pemesanan (user)
2. admin.html → Dashboard Admin untuk monitoring dan manajemen

## 1. Halaman User – Pemesanan
   Halaman ini digunakan pelanggan untuk memesan makanan dan minuman secara langsung. Fitur Utama:
   
✔ Pemilihan Menu
1. Daftar makanan dan minuman tampil lengkap dengan harga.
2. Tersedia opsi topping (optional).
3. Tersedia pilihan suhu minuman (ICE / HOT).
4. Customization tersimpan per item.

✔ Manajemen Keranjang
1. Menambah / menghapus item.
2. Edit jumlah item secara real-time.
3. Total harga otomatis terhitung.
4. Penyimpanan data keranjang via LocalStorage.

✔ Form Pemesanxdr
1. Input nama pemesan
2. Nomor meja
3. Metode pembayaran (Cash / Qris)

✔ Checkout
1. Pesanan yang selesai checkout akan tersimpan ke LocalStorage sebagai riwayatPesanan.
2. Data dikirim ke halaman admin untuk monitoring.

## 2. Dashboard Admin
   Halaman admin untuk melihat pesanan, mengatur stok, membaca kritik & saran, serta mengelola laporan keuangan. Fitur Utama:
   
✔ Laporan Pesanan Harian
1. Menampilkan seluruh pesanan lengkap dengan detail:
   Nama pemesan
   Nomor meja
   Total harga
   Metode pembayaran
   Waktu transaksi
2. Tombol "Tandai Selesai" untuk menandai pesanan yang sudah selesai.
3. Penghitungan total pendapatan harian.
4. Tombol Download CSV untuk mengunduh laporan.

✔ Manajemen Stok
1. Admin dapat mengubah stok makanan secara langsung.
2. Perubahan otomatis tersimpan ke LocalStorage.
3. Notifikasi toast muncul saat stok berhasil diubah.

✔ Kritik & Saran
1. Menampilkan pesan yang dikirim oleh pelanggan.
2. Terdapat data: nama, email, isi pesan, waktu.

✔ Modal Rincian Pesanan
1. Menampilkan detail item pesanan dalam pop-up modal.
2. Menghitung subtotal tiap menu.

✔ Reset Harian
1. Data laporan akan otomatis ter-reset setiap hari.

## Teknologi yang Digunakan
1. HTML5
2. CSS & Bootstrap 5.3.3
3. JavaScript ES6
4. LocalStorage API
5. Font Awesome (ikon)
