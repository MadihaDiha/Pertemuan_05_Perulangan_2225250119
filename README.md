# Pertemuan 05 Perulangan Python

## Identitas

- **Nama:** Madiha
- **NIM:** 2225250119
- **Kelas:** 3E

## Tujuan

Pada pertemuan ini, saya mempelajari penggunaan perulangan **`for`** dan **`while`** dalam Python untuk menyelesaikan berbagai masalah yang membutuhkan proses secara berulang atau iteratif.

## Struktur Folder

```text
Pertemuan_05_Perulangan_2225250119/
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
```

## Cara Menjalankan Program

Pastikan Python sudah terinstall pada komputer.

Contoh menjalankan program latihan:

```bash
python latihan/01_tabel_perkalian.py
```

atau:

```bash
python3 latihan/01_tabel_perkalian.py
```

Untuk menjalankan program kuis:

```bash
python kuis/kuis2_deret_aritmetika.py
```

## Materi yang Dipraktikkan

1. Perulangan `for`
2. Perulangan `while`
3. Fungsi `range()`
4. Validasi input
5. Seleksi `if` di dalam perulangan
6. Akumulasi dan pencacahan
7. Deret aritmetika

# Latihan

## 1. Tabel Perkalian

Program menerima sebuah bilangan bulat dan menampilkan hasil perkalian dari **1 sampai 10**.

### Test Case

| No. | Input | Keterangan |
|---|---:|---|
| 1 | 4 | Menampilkan tabel perkalian 4 dari 1 sampai 10 |
| 2 | -3 | Menampilkan tabel perkalian -3 dari 1 sampai 10 |

---

## 2. Jumlah Bilangan

Program menghitung jumlah bilangan dari **1 sampai n**.

### Test Case

| No. | Input `n` | Hasil |
|---|---:|---:|
| 1 | 1 | 1 |
| 2 | 5 | 15 |
| 3 | 10 | 55 |

---

## 3. Validasi Input

Program meminta pengguna memasukkan nilai ujian dari **0 sampai 100**. Jika nilai berada di luar rentang tersebut, program akan meminta pengguna memasukkan nilai kembali.

### Test Case

| No. | Input | Hasil |
|---|---:|---|
| 1 | 120 | Ditolak karena lebih dari 100 |
| 2 | -5 | Ditolak karena kurang dari 0 |
| 3 | 75 | Diterima karena berada pada rentang 0–100 |

**Kesimpulan pengujian:**  
Program berhasil menolak nilai `120` dan `-5`, kemudian menerima nilai `75` sebagai input yang valid.

---

## 4. Menghitung Bilangan Genap

Program menghitung banyaknya bilangan genap dari **1 sampai n**.

### Test Case

| No. | Input `n` | Banyak Bilangan Genap |
|---|---:|---:|
| 1 | 1 | 0 |
| 2 | 2 | 1 |
| 3 | 5 | 2 |
| 4 | 10 | 5 |

# Kuis 2 — Deret Aritmetika

Program menerima tiga input, yaitu:

- **Suku pertama (`a`)**
- **Beda (`d`)**
- **Banyak suku (`n`)**

Program menggunakan perulangan **`while`** untuk melakukan validasi nilai `n` dan menggunakan perulangan **`for`** untuk menghasilkan suku serta menghitung jumlah deret aritmetika.

## Test Case

| No. | `a` | `d` | `n` | Suku | Jumlah |
|---|---:|---:|---:|---|---:|
| 1 | 2 | 3 | 5 | 2, 5, 8, 11, 14 | 40 |
| 2 | 10 | -2 | 4 | 10, 8, 6, 4 | 28 |
| 3 | 1.5 | 0.5 | 3 | 1.5, 2.0, 2.5 | 6.0 |

# Hasil Pengujian

Berdasarkan pengujian yang telah dilakukan, seluruh program latihan dan kuis dapat dijalankan sesuai dengan tujuan yang telah ditentukan.

| No. | Program | Pengujian | Hasil yang Diharapkan | Status |
|---|---|---|---|---|
| 1 | Tabel Perkalian | `n = 4` | Menampilkan perkalian 4 dari 1–10 | Berhasil |
| 2 | Tabel Perkalian | `n = -3` | Menampilkan perkalian -3 dari 1–10 | Berhasil |
| 3 | Jumlah Bilangan | `n = 5` | Menghasilkan jumlah 15 | Berhasil |
| 4 | Jumlah Bilangan | `n = 10` | Menghasilkan jumlah 55 | Berhasil |
| 5 | Validasi Input | `120, -5, 75` | Menolak input tidak valid dan menerima 75 | Berhasil |
| 6 | Bilangan Genap | `n = 10` | Menghasilkan 5 bilangan genap | Berhasil |
| 7 | Deret Aritmetika | `a=2, d=3, n=5` | Suku = 2, 5, 8, 11, 14; jumlah = 40 | Berhasil |
| 8 | Deret Aritmetika | `a=10, d=-2, n=4` | Suku = 10, 8, 6, 4; jumlah = 28 | Berhasil |
| 9 | Deret Aritmetika | `a=1.5, d=0.5, n=3` | Suku = 1.5, 2.0, 2.5; jumlah = 6.0 | Berhasil |

# Refleksi

Pada pertemuan ini, saya mempelajari penggunaan perulangan **`for`** dan **`while`** dalam Python. Saya juga belajar menggunakan fungsi **`range()`**, melakukan validasi input, menggunakan seleksi **`if`** di dalam perulangan, serta menerapkan akumulasi untuk menghitung hasil secara berulang.

Dari latihan yang dilakukan, saya memahami bahwa perulangan dapat digunakan untuk membuat proses yang sama dilakukan secara otomatis tanpa harus menuliskan perintah yang sama berkali-kali.

Kesalahan yang perlu diperhatikan dalam penggunaan perulangan adalah batas pada **`range()`**, pembaruan variabel kontrol pada **`while`**, dan posisi variabel akumulator. Jika variabel kontrol pada perulangan `while` tidak diperbarui, program dapat mengalami **infinite loop** atau perulangan tanpa akhir.

Melalui latihan dan pengujian beberapa kasus, saya menjadi lebih memahami cara kerja perulangan serta bagaimana memastikan program menghasilkan output yang sesuai dengan input yang diberikan.
