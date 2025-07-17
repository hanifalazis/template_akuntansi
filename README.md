# template akuntansi

# Template Akuntansi Otomatis dengan Google Sheets

Selamat datang di repositori Template Akuntansi Otomatis! Template ini adalah sistem akuntansi berbasis Google Sheets yang dirancang untuk membantu Usaha Kecil dan Menengah (UKM), freelancer, dan siapa pun yang ingin mengelola keuangan bisnis dengan lebih mudah dan efisien.

Dari pencatatan transaksi harian, template ini akan secara otomatis menghasilkan laporan keuangan penting seperti Laporan Laba Rugi dan Neraca.

## Fitur Utama

-   **Laporan Keuangan Otomatis:** Laporan Laba Rugi (LR) dan Neraca (NRC) ter-update secara real-time berdasarkan input jurnal Anda[cite: 33].
-   **Jurnal Terpusat:** Semua transaksi dari `J_PP` (Jurnal Umum), `J_Penjualan`, dan `ASET` digabungkan ke dalam satu master jurnal yang menjadi sumber data utama laporan[cite: 40].
-   **Manajemen Data Master:**
    -   **Chart of Accounts (COA):** Fleksibel untuk menambah, mengedit, atau menghapus daftar akun sesuai kebutuhan bisnis[cite: 37, 38].
    -   **Daftar Aset:** Modul untuk mencatat dan mengelola aset tetap perusahaan[cite: 40].
-   **Format Input Efisien:** Menggunakan format satu baris per transaksi (Debit & Kredit dalam satu baris) untuk menjaga performa spreadsheet tetap ringan dan cepat[cite: 44, 45, 46].
-   **Utilitas Laporan:** Fitur filter untuk menyembunyikan akun bernilai nol, sehingga laporan lebih ringkas dan fokus pada data yang relevan[cite: 51, 52].

## Cara Penggunaan

1.  **Dapatkan Salinan Template Anda**
    -   Buka link spreadsheet berikut: https://docs.google.com/spreadsheets/d/19gcBJWEpWHnxFLaINBM3fFnQVFF4HSfbXfmzvMIjUEw/edit?pli=1&gid=1726041086#gid=1726041086
    -   Klik menu **File > Make a copy (Buat Salinan)** untuk menyimpan template ke akun Google Drive Anda.

2.  **Siapkan Daftar Akun (COA)** [cite: 36]
    -   Buka sheet `COA`.
    -   Sesuaikan daftar akun yang ada. Anda bisa mengedit nama, menambah akun baru, atau menghapus akun yang tidak diperlukan[cite: 38].

3.  **Input Data Transaksi** [cite: 39]
    -   Aktivitas input data **hanya dilakukan** pada sheet `ASET`, `J_PP`, dan `J_Penjualan`[cite: 40].
    -   Pastikan Anda mengisi kolom Debit dan Kredit dalam satu baris yang sama untuk setiap transaksi[cite: 46].

4.  **Lihat Laporan (Read-Only)** [cite: 41]
    -   Sheet `LR` (Laba Rugi), `NRC` (Neraca), dan `Buku Besar` adalah laporan otomatis[cite: 42]. Jangan mengubah data apa pun di sheet ini[cite: 43].

5.  **Mengatasi Error `#REF!`** [cite: 47]
    -   **Penyebab:** Error ini biasanya terjadi karena Anda menambah akun baru di `COA` yang menyebabkan formula Array "tertimpa"[cite: 48].
    -   **Solusi:** Cukup **sisipkan baris baru (Insert Row)** tepat di sel yang menunjukkan error `#REF!` pada sheet Laporan untuk memberikan ruang bagi formula[cite: 49, 50].
