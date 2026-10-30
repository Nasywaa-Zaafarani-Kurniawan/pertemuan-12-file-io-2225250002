# pertemuan-12-file-io-2225250002

## Tujuan
Membaca, memvalidasi, mengolah, dan menulis data file dengan Python.

## Format File Input
File data/nilai.txt menggunakan format:
NIM,nilai

Contoh:
A001,85
A002,78

## Cara Menjalankan
Jalankan file Python berikut dari root folder proyek:

python latihan/01_tulis_file.py
python latihan/02_baca_file.py
python latihan/03_append_file.py
python latihan/04_proses_baris.py
python latihan/05_file_not_found.py
python latihan/06_value_error.py
python tugas/rekap_nilai_file.py

## Error yang Ditangani
- FileNotFoundError
- ValueError

## Test Case
1. Data normal: record valid diproses.
2. File hilang: program menampilkan pesan error.
3. Nilai invalid: baris dilewati dan record lain diproses.
4. Baris kosong: baris dilewati.
5. Nilai 60: dihitung sebagai lulus.
