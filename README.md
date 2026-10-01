Pertemuan 05 Perulangan Python

Nama: Madiha
NIM: 2225250119
Kelas: 3E

Tujuan

Menggunakan perulangan "for" dan "while" untuk menyelesaikan masalah iteratif.

Struktur Folder

pertemuan-05-perulangan-NIM/
│
├── README.md
├── .gitignore
│
├── latihan/
│   ├── 01_tabel_perkalian.py
│   ├── 02_jumlah_bilangan.py
│   ├── 03_validasi_input.py
│   └── 04_hitung_genap.py
│
└── kuis/
    └── kuis2_deret_aritmetika.py

Cara Menjalankan

Pastikan Python sudah terinstall.

Contoh menjalankan program:

python latihan/01_tabel_perkalian.py

atau:

python3 latihan/01_tabel_perkalian.py

Untuk menjalankan kuis:

python kuis/kuis2_deret_aritmetika.py

Materi yang Dipraktikkan

1. Perulangan "for"
2. Perulangan "while"
3. "range()"
4. Validasi input
5. Seleksi "if" di dalam perulangan
6. Akumulasi dan pencacahan
7. Deret aritmetika

Latihan

1. Tabel Perkalian

Program menerima sebuah bilangan bulat dan menampilkan perkalian dari "1" sampai "10".

Test case:

- "n = 4"
- "n = -3"

2. Jumlah Bilangan

Program menghitung jumlah bilangan dari "1" sampai "n".

Test case:

- "n = 1" → "1"
- "n = 5" → "15"
- "n = 10" → "55"

3. Validasi Input

Program meminta nilai ujian dari "0" sampai "100". Jika nilai tidak berada dalam rentang tersebut, program meminta input kembali.

Test case:

120
-5
75

Program menolak "120" dan "-5", kemudian menerima "75".

4. Menghitung Bilangan Genap

Program menghitung banyak bilangan genap dari "1" sampai "n".

Test case:

n| Hasil
1| 0
2| 1
5| 2
10| 5

Kuis 2 — Deret Aritmetika

Program menerima:

- Suku pertama "a"
- Beda "d"
- Banyak suku "n"

Program menggunakan "while" untuk validasi "n" dan "for" untuk menghasilkan suku serta menghitung jumlah deret.

Test Case

a| d| n| Suku| Jumlah
2| 3| 5| 2, 5, 8, 11, 14| 40
10| -2| 4| 10, 8, 6, 4| 28
1.5| 0.5| 3| 1.5, 2.0, 2.5| 6.0

Refleksi

Pada pertemuan ini saya mempelajari penggunaan perulangan "for" dan "while" dalam Python. Saya juga belajar menggunakan "range()", validasi input, seleksi "if" di dalam perulangan, serta akumulasi untuk menghitung hasil secara berulang.

Kesalahan yang perlu diperhatikan dalam perulangan adalah batas "range", pembaruan variabel pada "while", dan posisi variabel akumulator. Jika variabel kontrol pada "while" tidak diperbarui, program dapat mengalami infinite loop.

Hasil Pengujian

Semua program dijalankan menggunakan beberapa test case untuk memastikan perulangan berhenti pada kondisi yang benar dan menghasilkan output sesuai dengan yang diharapkan.
