# Analisis-Numerik-Gerai-Donat

## Deskripsi

Proyek ini merupakan tugas Analisis Numerik yang bertujuan untuk menganalisis hubungan antara jumlah penjualan dengan revenue pada lima gerai donat serta menentukan Break Even Point (BEP) masing-masing gerai.

## Tujuan

1. Membuat plot hubungan jumlah penjualan dengan revenue pada lima gerai.
2. Menerapkan regresi untuk mengetahui bentuk tren revenue berdasarkan volume penjualan.
3. Menentukan jumlah penjualan yang menghasilkan Break Even Point (BEP) menggunakan metode numerik.

## Dataset

Dataset yang digunakan adalah data penjualan harian lima gerai donat, yaitu Gerai A, Gerai B, Gerai C, Gerai D, dan Gerai E.

Variabel yang digunakan meliputi:
- Tanggal
- Gerai
- Harga Jual
- Jumlah Terjual
- Pendapatan Kotor
- Biaya Variabel
- Fixed Cost Harian
- Balance

## Metode

Analisis dilakukan melalui beberapa tahap:
1. Eksplorasi dan pengecekan dataset.
2. Visualisasi jumlah penjualan terhadap revenue.
3. Regresi linear untuk memodelkan revenue.
4. Pembentukan fungsi revenue dan total cost.
5. Penentuan BEP sebagai akar dari fungsi revenue dikurangi total cost.
6. Pencarian akar menggunakan metode Bisection.

## Hasil

Hasil analisis menunjukkan hubungan linear antara jumlah penjualan dan revenue pada kelima gerai. BEP yang diperoleh setelah pembulatan ke atas adalah:

| Gerai | BEP |
|---|---:|
| Gerai A | 103 unit |
| Gerai B | 191 unit |
| Gerai C | 282 unit |
| Gerai D | 209 unit |
| Gerai E | 92 unit |

## File

`Analisis_Numerik_Donat_Naila.ipynb` berisi seluruh proses analisis, kode Python, visualisasi, hasil perhitungan, dan interpretasi.


# Perhitungan Volume Lambung Kapal

## Deskripsi

Proyek ini merupakan tugas Analisis Numerik yang bertujuan untuk menghitung volume dua lambung kapal berdasarkan data pengukuran pada grid menggunakan metode integrasi numerik Simpson 1/3.

## Tujuan

1. Menentukan titik pengukuran dan jarak antar titik berdasarkan grid pada gambar kapal.
2. Menghitung luas penampang lambung pada setiap titik pengukuran.
3. Menerapkan metode Simpson 1/3 untuk menghitung volume masing-masing lambung.
4. Menentukan volume total kedua lambung kapal.

## Data

Data yang digunakan diperoleh dari gambar tampak atas dan tampak bawah kapal. Bagian reserve buoyancy tidak digunakan dalam perhitungan, sehingga diperoleh 16 interval dengan 17 titik pengukuran.

Data yang digunakan meliputi:
- Grid 2 sampai grid 18
- Jumlah interval = 16
- Jarak antar titik = 10 cm
- Tinggi penampang = 10 cm
- Lebar lambung pada setiap titik pengukuran

## Metode

Perhitungan dilakukan melalui beberapa tahap:
1. Menentukan grid yang digunakan dengan mengabaikan bagian reserve buoyancy.
2. Menentukan jarak antar titik pengukuran.
3. Mengukur lebar masing-masing lambung pada setiap titik.
4. Menghitung luas penampang menggunakan rumus:
   
   A_i = w_i × h

5. Menggunakan metode Simpson 1/3 untuk menghitung volume masing-masing lambung.
6. Menjumlahkan volume kedua lambung untuk mendapatkan volume total.

Metode Simpson 1/3 digunakan karena jumlah interval yang digunakan adalah 16, sehingga memenuhi syarat jumlah interval genap.

## Hasil

Hasil perhitungan menggunakan metode Simpson 1/3 diperoleh:

| Bagian | Volume |
|---|---:|
| Lambung 1 | 31,61 liter |
| Lambung 2 | 31,32 liter |
| Total | 62,93 liter |

Volume total kedua lambung kapal yang diperoleh adalah sekitar **62,93 liter**.

Hasil tersebut merupakan pendekatan numerik karena data lebar lambung diperoleh melalui pengukuran pada gambar grid.

## File

`ANALISIS_NUMERIK_KAPAL.ipynb` berisi seluruh proses perhitungan, kode Python, data pengukuran, penerapan metode Simpson 1/3, hasil perhitungan, dan interpretasi.
