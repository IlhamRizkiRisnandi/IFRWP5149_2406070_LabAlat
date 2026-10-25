Mahasiswa dan dosen sama-sama merupakan Civitas Akademika yang dapat melihat kalender akademik. Dosen menginput nilai mata kuliah yang diampunya setelah masa perkuliahan berakhir. Mahasiswa melihat Kartu Hasil Studi (KHS) untuk semester yang nilainya sudah dipublikasikan. Admin Akademik mengelola data mahasiswa: menambah data mahasiswa baru, mengubah data mahasiswa, dan menghapus data mahasiswa. Dua use case utama, Input Nilai Mata Kuliah dan Lihat KHS, ditunjukkan realisasinya oleh collaboration yang bersesuaian.



|  Aktor  |  Kedudukan  |Tujuan terhadap sistem |
|---------|----------------------|--------------------------------------------------------------------------------|
| Civitas |  Akademika Umum (general) | Peran umum bagi pengguna akademik kampus. Mewariskan fungsinya kepada Mahasiswa dan Dosen untuk melihat kalender akademik. |
|Mahasiswa|   Khusus dari Civitas Akademika | Melihat kalender akademik (diwarisi dari Civitas Akademika) dan melihat KHS (Kartu Hasil Studi).         |
|  Dosen  |   Khusus dari Civitas Akademika | Melihat kalender akademik (diwarisi dari Civitas Akademika) dan menginput nilai mata kuliah.           |
|  Admin  |AkademikUtama Berdiri Sendiri | Mengelola data mahasiswa (termasuk tambah, ubah, dan hapus).                    |


## katalog use case

| ID | Nama use case | Peran dalam model | Sumber kebutuhan |
| :--- | :--- | :--- | :--- |
| SIA-UC01 | Lihat Kalender Akademik | Fungsi aktor umum Civitas Akademika | SIA-R07 |
| SIA-UC02 | Input Nilai Mata Kuliah | Fungsi khusus Dosen; direalisasikan oleh collaboration SIA-CO01 | SIA-R08, SIA-R12 |
| SIA-UC03 | Lihat KHS | Fungsi khusus Mahasiswa; direalisasikan oleh collaboration SIA-CO02 | SIA-R09, SIA-R12 |
| SIA-UC04 | Kelola Data Mahasiswa | Use case UMUM bagi SIA-UC05, SIA-UC06, SIA-UC07; fungsi Admin Akademik | SIA-R10, SIA-R11 |
| SIA-UC05 | Tambah Data Mahasiswa | Use case KHUSUS dari SIA-UC04 | SIA-R11 |
| SIA-UC06 | Ubah Data Mahasiswa | Use case KHUSUS dari SIA-UC04 | SIA-R11 |
| SIA-UC07 | Hapus Data Mahasiswa | Use case KHUSUS dari SIA-UC04 | SIA-R11 |

