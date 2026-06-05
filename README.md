#Naming Conventinon
Herdan Wahyu Mairendra Pangestu
3325600064

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

Pembetulan Naming Convention sesuai PEP8
Baris,Elemen Asli,Elemen Perbaikan,Prinsip PEP 8 yang Dilanggar / Penjelasan
1,class dtBrg,class DataBarang,Nama kelas harus menggunakan format CapWords / PascalCase. Singkatan tidak baku (dtBrg) mempersulit pemahaman kode.
5,def _init_,def __init__,Magic method konstruktor bawaan Python wajib menggunakan double underscore (dunder) di awal dan akhir nama.
"5, 34","n, hrg, d, tP","nama, harga, barang, tipe_pelanggan",Nama argumen dan variabel lokal harus deskriptif dan dilarang menggunakan satu/dua huruf singkatan yang tidak bermakna jelas.
"13, 14","self.NM, self.HRG","self.nama, self.harga",Atribut atau variabel instance wajib ditulis menggunakan huruf kecil penuh (snake_case). Format kapital (ALL_CAPS) hanya digunakan untuk konstanta global.
17,def hitung Disc,def hitung_diskon,Nama fungsi/method tidak boleh mengandung spasi (memicu SyntaxError) dan harus ditulis dengan format snake_case.
25,self. HRG,self.harga,Penulisan pemanggilan atribut objek tidak boleh dipisahkan oleh spasi ekstra setelah tanda titik.
34,def CETAK,def cetak_rincian,Nama fungsi reguler harus menggunakan huruf kecil semua dengan pemisah kata berupa underscore (snake_case).
"41, 42","ds, ttl","diskon, total",Variabel penampung nilai lokal harus berupa kata lengkap yang representatif untuk meningkatkan nilai clean code.
50,x = dtBrg(...),laptop = DataBarang(...),Variabel penampung instansiasi objek harus mencerminkan entitas objek yang dibuat.
''',,,
