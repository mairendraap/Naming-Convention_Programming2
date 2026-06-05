# Naming Conventinon
Herdan Wahyu Mairendra Pangestu
3325600064

## Latihan 1
Instalasi Autoformatter Flake8 dan Black Formatter
<img width="1920" height="1080" alt="Screenshot (421)" src="https://github.com/user-attachments/assets/a1f73ad2-325a-453e-a511-c9b008a0e0eb" />
<img width="828" height="154" alt="Screenshot 2026-06-05 193147" src="https://github.com/user-attachments/assets/5b4371e4-3cc3-4419-9afa-eef321d1b008" />
<img width="1920" height="1080" alt="Screenshot (420)" src="https://github.com/user-attachments/assets/17a80c46-f466-4b84-8ee1-c97b7b0f18ee" />
<img width="1586" height="265" alt="Screenshot 2026-06-05 193753" src="https://github.com/user-attachments/assets/4374569e-cbb1-4398-bbde-f035eaf7151a" />
<img width="1586" height="348" alt="Screenshot 2026-06-05 194444" src="https://github.com/user-attachments/assets/58254489-ea80-4a95-8018-ce813f9d13ed" />
<img width="1920" height="1080" alt="Screenshot (423)" src="https://github.com/user-attachments/assets/677dfb4a-019f-4761-81d0-19ab7f24728d" />
<img width="1596" height="333" alt="Screenshot 2026-06-05 194735" src="https://github.com/user-attachments/assets/9a47efb7-0421-48cc-a9ad-772f74a06f1c" />
<img width="1580" height="314" alt="Screenshot 2026-06-05 194746" src="https://github.com/user-attachments/assets/8278bd54-f95a-4520-a617-c8a9cfd47d06" />

Menggunakan Flake8 instalasi via terminal menggunakan pip dan venv agar environtmentnya sama
- FLake8 terdapat error (saya juga kurang paham kenapa karena jarang pakai autoformatter)
- Black Formatter berhasil format 1 file

## Latihan 2
| Baris | Kode Asli (Salah) | Kode Perbaikan (Benar) | Prinsip PEP 8 yang Dilanggar & Penjelasan |
| :---: | :--- | :--- | :--- |
| 1 | `class dtBrg:` | `class DataBarang:` | Nama *class* wajib menggunakan format **PascalCase**. Singkatan tidak baku mengurangi keterbacaan. |
| 5 | `def _init_(...):` | `def __init__(...):` | *Magic method* (konstruktor) wajib menggunakan *double underscore* (dunder) di awal dan akhir nama. |
| 5, 34 | `n`, `hrg`, `d`, `tP` | `nama`, `harga`, `barang`, `tipe_pelanggan` | Nama variabel/argumen dilarang berupa singkatan 1-2 huruf yang tidak memiliki makna jelas. |
| 13, 14 | `self.NM`, `self.HRG` | `self.nama`, `self.harga` | Atribut *instance* wajib menggunakan huruf kecil penuh (**snake_case**). Kapital penuh hanya untuk konstanta. |
| 17 | `def hitung Disc(...):` | `def hitung_diskon(...):` | Nama fungsi/method tidak boleh mengandung spasi (SyntaxError) dan wajib menggunakan format **snake_case**. |
| 25, 28 | `self. HRG` | `self.harga` | Tidak boleh ada spasi ekstra setelah tanda titik saat memanggil atribut dari suatu objek. |
| 34 | `def CETAK(...):` | `def cetak_rincian(...):` | Nama fungsi reguler tidak boleh menggunakan huruf kapital penuh (*ALL CAPS*), melainkan **snake_case**. |
| 41, 42 | `ds`, `ttl` | `diskon`, `total` | Variabel lokal harus berupa kata utuh agar deskriptif (*clean code*). |
| 50 | `x = dtBrg(...)` | `laptop = DataBarang(...)` | Nama instansiasi objek sebaiknya mencerminkan entitas objek yang dibuat. |
