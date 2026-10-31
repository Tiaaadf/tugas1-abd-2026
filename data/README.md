# Dokumentasi Dataset

## 1. Identitas Dataset

| Informasi | Keterangan |
|---|---|
| Nama dataset | VQFat Indonesian Corpus |
| Subset | cosmopedia_id |
| Nama file | cosmopedia_id.csv |
| Penulis | Vicky Fatrian |
| Platform | Hugging Face |
| Bahasa | Indonesia |
| Format | CSV |
| Versi dataset | 1.1 |
| Tanggal versi | 6 Maret 2026 |
| Lisensi | C-UDA (Computational Use of Data Agreement) |

## 2. Sumber Dataset

Dataset diperoleh dari Hugging Face:

https://huggingface.co/datasets/vickyfatrian/vqfat-indo-corpus

Subset yang digunakan adalah `cosmopedia_id`, yaitu korpus teks sintetis berbahasa Indonesia yang diadaptasi dari konsep Cosmopedia.

## 3. Informasi Dataset yang Digunakan

Berdasarkan pemeriksaan file lokal:

| Informasi | Hasil |
|---|---:|
| Nama file | cosmopedia_id.csv |
| Ukuran file | 554,81 MB |
| Jumlah baris | 120.068 |
| Jumlah kolom | 9 |
| Format | CSV |

Ukuran file di atas merupakan hasil pengukuran file yang digunakan dalam penelitian ini, bukan ukuran keseluruhan repositori dataset.

## 4. Struktur Data

Dataset terdiri dari sembilan kolom:

| Kolom | Keterangan |
|---|---|
| id | Identitas unik data |
| prompt | Teks instruksi atau konteks |
| text | Isi teks atau respons |
| token_length | Estimasi panjang teks berdasarkan token |
| audience | Target pembaca |
| format | Format atau jenis teks |
| seed_data | Informasi sumber atau data dasar |
| datasheet_global_id | Identitas global datasheet |
| created_at | Informasi waktu pembuatan data |

## 5. Unit Analisis

Unit analisis dalam tugas ini adalah satu entri teks pada dataset Cosmopedia Indonesia. Setiap baris merepresentasikan satu data yang memiliki informasi instruksi atau konteks, teks, serta metadata pendukung.

## 6. Lisensi dan Atribusi

Dataset menggunakan lisensi C-UDA (Computational Use of Data Agreement).

Penggunaan dataset harus mengikuti ketentuan lisensi dan atribusi yang tercantum pada halaman resmi Hugging Face.

Atribusi:
Vicky Fatrian. (2026). VQFat Indonesian Corpus: Combined Pre-training and Instruction QA Dataset for SLMs. Hugging Face.

## 7. Cara Memperoleh Dataset

Dataset dapat diperoleh melalui halaman Hugging Face berikut:

https://huggingface.co/datasets/vickyfatrian/vqfat-indo-corpus

Subset yang digunakan adalah `cosmopedia_id`.

File CSV disimpan pada direktori:

`data/raw/cosmopedia_id.csv`

Untuk reproduksi, unduh subset yang sama dari sumber resmi dan simpan dengan nama file tersebut.

## 8. Pengelolaan File

- Dataset mentah disimpan pada `data/raw/`.
- Dataset hasil pembersihan disimpan pada `data/processed/`.
- File dataset mentah dan hasil olahan berukuran besar tidak diunggah ke GitHub.
- Proses profiling, cleaning, dan EDA dilakukan melalui notebook pada direktori `notebooks/`.
