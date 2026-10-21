# Functional Requirement

| ID | MODUL/FITUR | PERILAKU SISTEM |
| :--- | :--- | :--- |
| FR-01 | Autentikasi Login | Sistem harus dapat memvalidasi kredensial pengguna dan level hak akses (*Role* Admin & User/Staff) sebelum pengguna memasuki laman Dashboard. |
| FR-02 | Manajemen Pengguna | Admin dapat mengelola data pengguna (menambah, menghapus, atau mengubah data staff) yang memiliki hak akses pada sistem. |
| FR-03 | Manajemen Data Master | Pengelolaan data dasar yang diperlukan untuk operasional sistem, seperti data master aset, data supplier (vendor), dan data kategori aset. |
| FR-04 | Log Transaksi Pembelian (Purchase) Aset | Modul pencatatan transaksi mutasi aset masuk dari supplier atau vendor ke dalam sistem. |
| FR-05 | Log Pengembalian Barang / Aset (Return) | Modul pencatatan pengembalian aset yang sudah usang atau bermasalah kembali ke pihak supplier / vendor. |
| FR-06 | Pelaporan dan Visualisasi Data | Penyajian informasi statistik berbentuk diagram untuk mempermudah monitoring harian serta penyediaan fitur unduh laporan rekapitulasi inventaris. |

# Non-Functional Requirement

| ID | KATEGORI | PARAMETER KEBUTUHAN NON-FUNGSIONAL |
| :--- | :--- | :--- |
| NFR-01 | Usability (Kegunaan) | Sistem harus memiliki antarmuka yang mudah dipahami (*user-friendly*) serta dilengkapi notifikasi peringatan jika terdapat kolom input yang wajib diisi namun belum terisi. |
| NFR-02 | Reliability & Availability (Keandalan & Ketersediaan) | Sistem harus selalu tayang dan beroperasi stabil pada jaringan lokal, serta dilengkapi fitur *Offline-First* yang mampu menyimpan data secara lokal (*Local Persistent Data*). |
| NFR-03 | Maintainability (Kemudahan Pemeliharaan) | Sistem ditempatkan pada server lokal (*local server*) sehingga pembaruan fitur (*update*) atau perbaikan kendala teknis dapat segera diatasi dengan cepat. |
| NFR-04 | Scalability & Infrastructure (Skalabilitas & Infrastruktur) | Server wajib terhubung pada catu daya cadangan (*Uninterruptible Power Supply* / UPS) untuk meminimalisir gangguan listrik, serta menggunakan perangkat terpisah seperti NAS (*Network Attached Storage*) untuk *backup* basis data secara berkala. |
| NFR-05 | Security (Keamanan) | Server harus diletakkan pada jaringan VLAN (*Virtual Local Area Network*) yang terpisah dari komputer karyawan atau Wi-Fi umum, serta tetap menggunakan protokol SSL/HTTPS meskipun beroperasi di jaringan lokal. |
| NFR-06 | Compatibility (Kompatibilitas) | Sistem harus dapat diakses melalui berbagai macam *browser* web serta perangkat desktop maupun seluler yang terhubung pada jaringan lokal. |