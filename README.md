
# Pertemuan 10 - String dan Pengolahan Teks

**Nama:** Ahmad Nurikhsan  
**NIM:** 2225250042  
**Kelas:** 3E

## Tujuan

Mempelajari string Python serta menerapkan operasi indeks, slicing, method string, pembersihan teks, split, join, dan pencarian kata.

## Struktur Folder

- `latihan/01_dasar_string.py`
- `latihan/02_indeks_slicing.py`
- `latihan/03_method_string.py`
- `latihan/04_bersihkan_teks.py`
- `latihan/05_split_join.py`
- `latihan/06_pencarian_kata.py`
- `tugas/normalisasi_data_mahasiswa.py`

## Cara Menjalankan

Jalankan terminal pada folder utama proyek, kemudian gunakan:

```bash
python tugas/normalisasi_data_mahasiswa.py
```

## Algoritma

1. Menerima input nama mahasiswa dan kode kelas.
2. Menghapus spasi berlebih pada nama.
3. Mengubah nama menjadi title case.
4. Mengubah kode kelas menjadi huruf kapital dan memisahkan bagian kode dengan tanda hubung.
5. Menghitung jumlah kata pada nama.
6. Membuat inisial dari setiap kata nama.
7. Menampilkan hasil normalisasi.

## Test Case

| Input Nama | Input Kode | Hasil Nama | Hasil Kode | Inisial |
|---|---|---|---|---|
| aan hendrayana | pmat a 2026 | Aan Hendrayana | PMAT-A-2026 | AH |
| fATHIYYAH mUTHMAINNAH | kelas b | Fathiyyah Muthmainnah | KELAS-B | FM |
| BUDI | pmtk 01 | Budi | PMTK-01 | B |
| siti nur aisyah | kelas c | Siti Nur Aisyah | KELAS-C | SNA |

**Status pengujian:** Isi setelah menjalankan program dan mencocokkan hasil aktual dengan hasil yang diharapkan.

## Refleksi

Saya mempelajari cara menggunakan method string untuk membersihkan dan menyeragamkan data teks. Saya juga memahami penggunaan split() untuk memisahkan kata, join() untuk menggabungkan teks, serta fungsi untuk membuat proses pengolahan teks dapat digunakan kembali.

## Bantuan dan Referensi

- Modul Algoritma dan Pemrograman Pertemuan 10.
- Dokumentasi Python: https://docs.python.org/3/library/stdtypes.html#text-sequence-type-str

