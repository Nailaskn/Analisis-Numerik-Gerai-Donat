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
