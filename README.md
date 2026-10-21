# Manajemen Inventaris Aset

Sistem informasi pengelolaan aset perusahaan berbasis web yang dirancang untuk mengotomatisasi pencatatan mutasi barang, meminimalkan kesalahan input, mempercepat penyusunan laporan, serta memastikan akurasi antara data digital dan kondisi fisik aset di gudang.

## Disclaimer Privasi

*Catatan:* Repositori ini menampilkan dokumentasi perancangan sistem dan analisis bisnis. Seluruh *source code*, konfigurasi server, serta kunci API tidak disematkan untuk mematuhi kebijakan privasi, hak kekayaan intelektual, serta perjanjian kerahasiaan dengan pihak mitra terkait.

## Latar Belakang & Analisis Masalah

- Profil Studi Kasus: **UD. Jawa Press** (berlokasi di Krembung, Sidoarjo) merupakan perusahaan manufaktur produksi massal bahan cetak kertas (seperti majalah dan kalender tahunan) yang mengandalkan ketepatan sirkulasi inventaris aset alat produksi dan penunjangnya.

- Pain Points:
1. **Proses Manual & Lambat:** Dokumentasi dan Pelaporan inventaris aset masih memakan waktu lama serta rentan terhadap kesalahan manusia (*human error*) maupun duplikasi data.

2. **Ketergantungan Lembar Kerja Terpisah:** Pemrosesan dan pencatatan riwayat inventaris barang masuk maupun keluar masih mengandalkan file Microsoft Excel terpisah, sehingga menyulitkan sinkronisasi antarbagian.

3. **Hambatan Rekapitulasi:** Kesulitan dalam melakukan audit dan rekapitulasi laporan bulanan secara valid dan *real-time*, yang berimbas pada penurunan efisiensi operasional gudang.

## Panduan

Dokumen ini disusun secara sistematis untuk menunjukkan alur kerja dan analisis bisnis menjadi spesifikasi teknis serta perancangan sistem. Dokumen ini dapat ditelusuri melalui urutan alur berikut :

1. Business Requirements Document (BRD): Meninjau batasan ruang lingkup proyek, objektif bisnis, dan alur kerja operasional pengelolaan inventaris. [BRD](BRD.md)
2. Functional Requirement Document (FRD): Menilai daftar kebutuhan fungsional (FR) dan parameter non-fungsional (NFR) untuk spesifikasi teknis perangkat lunak. [FRD](FRD.md)
3. Pemodelan Sistem (System Modeling): Mempelajari perancangan alur proses (*Flowchart*), batasan sistem (*Diagram Konteks*), dekomposisi aliran data (*DFD Level 1*), hingga struktur basis data relasional (*ERD*). [System Modeling](system-modeling.md)

## Fitur Utama

- **Manajemen Aset:** Fitur tambah, ubah, dan hapus data aset secara terpusat untuk mengatasi hambatan pencatatan manual dan duplikasi data.
- **Mutasi Aset Masuk:** Modul pencatatan pembelian (*purchase*) atau penerimaan stok aset baru guna memastikan akurasi data awal di gudang.
- **Mutasi Aset Retur:** Modul pencatatan pengembalian (*return*) atau pergerakan aset lama guna menjaga siklus audit yang jelas.
- **Laporan Log Aset:** Fitur ekspor data log pergerakan inventaris ke format PDF dan Excel untuk mempercepat proses rekapitulasi bulanan manajemen.
- **Manajemen Pengguna (RBAC):** Pembagian hak akses yang terstruktur antara Admin dan Petugas Gudang demi keamanan dan akuntabilitas data.