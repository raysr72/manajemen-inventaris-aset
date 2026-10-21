# Business Requirement Document (BRD)

## Sistem Manajemen Inventaris Aset

---

## Business Background
Sistem Manajemen Inventaris Aset dirancang dan dikembangkan untuk mengoptimalkan proses pengelolaan aset secara digital. Sistem ini bertujuan untuk meningkatkan akurasi proses pencatatan data barang serta transaksi masuk dan keluar, meminimalkan risiko kesalahan manual (human error), serta menyajikan laporan rekapitulasi yang valid dan real-time bagi kebutuhan operasional perusahaan.

## Problem Statement

- **Ketergantungan pada Pencatatan Manual:** Dokumentasi data aset inventaris (baik barang masuk maupun keluar) masih dilakukan secara manual dengan pencatatan menggunakan Microsoft Excel atau lembar kerja terpisah.
- **Inefisiensi Waktu & Risiko Human Error:** Proses dokumentasi memakan waktu lama, rentan terhadap kesalahan pencatatan, serta sering terjadi duplikasi data.
- **Hambatan Rekapitulasi:** Kesulitan dalam melakukan perhitungan rekap bulanan yang akurat sehingga mengurangi efisiensi kerja di tiap bagian perusahaan.

## Project Objectives
- Mengembangkan sistem manajemen inventaris berbasis web yang dapat mengoptimalkan pengelolaan aset secara real-time, akurat, dan efisien.
- Mengurangi risiko kesalahan manual (human error) dan mencegah duplikasi data pencatatan inventaris.
- Mempercepat proses pelaporan serta mendukung pengambilan keputusan strategis manajemen perusahaan melalui penyajian statistik dan data yang valid.

## Project Scope

### In-Scope
- **Manajemen Data Pengguna:** Kontrol hak akses multi-level berbasis akun (Admin/Supervisor dan User/Staff).
- **Manajemen Data Master & Aset:** Pengelolaan data kategori, data aset, dan data vendor/supplier.
- **Log Transaksi:** Pencatatan alur aset masuk (Purchase) dan pengembalian barang (Return).
- **Pelaporan & Rekapitulasi:** Penyajian statistik visualisasi, fitur pencatatan, serta pengunduhan laporan data inventaris perusahaan secara terpusat.

### Out-of-Scope
- Integrasi perangkat keras pemindai barcode/RFID industri tingkat lanjut secara mandiri di luar fitur input web standar.
- Modul akuntansi keuangan eksternal (General Ledger perusahaan pihak ketiga).

## Business Process Flow

- **Proses Saat Ini (As-Is):** Pengelolaan data aset masuk, aset keluar, dan rekapitulasi stok masih dilakukan secara manual menggunakan formulir kertas atau lembar kerja terpisah (Microsoft Excel), sehingga rentan terhadap kesalahan manusia dan keterlambatan pelaporan.
- **Proses Usulan (To-Be):** Seluruh proses pencatatan, mulai dari manajemen data master, transaksi pembelian (purchase), pengelolaan retur, hingga pengunduhan laporan operasional dilakukan secara terpusat dan terotomatisasi melalui aplikasi berbasis web yang dapat diakses secara fleksibel.