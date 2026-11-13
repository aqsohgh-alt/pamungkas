PORTFOLIO AQSO

Cara menjalankan:
1. Extract file ZIP.
2. Buka folder portfolio_aqso di Visual Studio Code.
3. Klik file index.html.
4. Jalankan menggunakan extension Live Server.
5. Untuk membuka Sistem Data Sekolah, jalankan F5 dengan konfigurasi "Jalankan Portfolio dan Sistem Data Sekolah", lalu klik project tersebut.

File utama:
- index.html
- style.css
- script.js

Aplikasi kasir:
- Buka kasir\index.html atau klik project "Aplikasi Kasir" di bagian Portfolio.
- Fitur: transaksi, pilihan pembayaran, cetak struk, katalog produk, stok, dan riwayat penjualan.
- Data produk dan transaksi disimpan di penyimpanan browser perangkat yang digunakan.

Hosting GitHub Pages:
- Atur Pages agar mengambil branch dan folder yang berisi index.html utama.
- Pastikan folder kasir dan redesign beserta seluruh file di dalamnya ikut diunggah ke branch tersebut.
- Tautan project menggunakan path relatif, jadi tetap berfungsi pada URL GitHub Pages yang memakai nama repository.
- Jika hanya halaman utama yang muncul dan project mendapat 404, periksa kembali file kasir\index.html dan redesign\index.html di branch sumber Pages.
- Sistem Data Sekolah masih berjalan lokal dan belum tersedia sebagai demo online.

Catatan:
- Formulir kontak masih berupa demo dan belum mengirim pesan ke email/server.
- Sistem Data Sekolah berjalan sebagai server Laravel lokal dari folder C:\ujikom_laravel_alaqsojayajaya.
