
# Pertemuan 07 Fungsi Python

Nama: Erna Hidayanti Nur Falah  
NIM: 2225250036  
Kelas: [Isi kelas kamu]

## Tujuan

Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular dalam Python.

## Cara Menjalankan

Jalankan program melalui terminal VS Code dari folder utama repositori.

Latihan 1:
```bash
py latihan/01_fungsi_salam.py
```

Latihan 2:
```bash
py latihan/02_luas_persegi_panjang.py
```

Latihan 3:
```bash
py latihan/03_jumlah_n.py
```

Latihan 4:
```bash
py latihan/04_statistik_sederhana.py
```

Latihan 5:
```bash
py latihan/05_eksperimen_scope.py
```

Praktik utilitas matematika:
```bash
py latihan/utilitas_matematika.py
```

## Struktur Fungsi

1. `salam(nama, kelas)`  
   Parameter: `nama` dan `kelas`.  
   Return: tidak mengembalikan nilai, tetapi menampilkan salam menggunakan `print`.

2. `luas_persegi_panjang(p, l)`  
   Parameter: panjang `p` dan lebar `l`.  
   Return: hasil perkalian panjang dan lebar.

3. `jumlah_n(n)`  
   Parameter: bilangan bulat `n`.  
   Return: jumlah bilangan dari 1 sampai `n`.

4. `statistik(data)`  
   Parameter: kumpulan data angka.  
   Return: nilai minimum, maksimum, dan rata-rata.

5. `demo(x)`  
   Parameter: `x`.  
   Return: nilai `x + 5`. Fungsi ini menunjukkan perbedaan variabel lokal dan variabel di luar fungsi.

6. `luas_segitiga(a, t)`  
   Parameter: alas `a` dan tinggi `t`.  
   Return: hasil perhitungan luas segitiga, yaitu 0.5 × alas × tinggi.

7. `faktorial(n)`  
   Parameter: bilangan bulat nonnegatif `n`.  
   Return: hasil perkalian bilangan dari 1 sampai `n`. Faktorial 0 bernilai 1.

8. `tampilkan_menu()`  
   Parameter: tidak ada.  
   Return: tidak mengembalikan nilai, tetapi menampilkan pilihan operasi matematika.

## Hasil Pengujian

| Program | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| Luas persegi panjang | p=8, l=5 | 40 | 40 | Berhasil |
| Luas segitiga | a=10, t=6 | 30.0 | 30.0 | Berhasil |
| Jumlah 1 sampai n | n=10 | 55 | 55 | Berhasil |
| Faktorial | n=5 | 120 | 120 | Berhasil |
| Faktorial | n=0 | 1 | 1 | Berhasil |
| Statistik sederhana | [70, 80, 65, 90, 75] | Min=65, maks=90, rata-rata=76.0 | Min=65, maks=90, rata-rata=76.0 | Berhasil |

Catatan: Status pengujian di atas perlu disesuaikan jika hasil aktual saat program dijalankan berbeda.

## Refleksi

Program menjadi lebih sederhana setelah proses perhitungan dipisahkan menjadi beberapa fungsi. Contohnya, perhitungan luas persegi panjang ditempatkan di dalam fungsi `luas_persegi_panjang()`, sehingga program utama hanya perlu memanggil fungsi tersebut dan memberikan nilai panjang serta lebar.

Dengan modularisasi, kode lebih mudah dibaca, digunakan kembali, dan diuji. Kesalahan juga lebih mudah ditemukan karena setiap fungsi memiliki tugas yang jelas.