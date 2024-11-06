![Mahkamah Agung](Logo/LogoDirektori.jpeg)

# Proyek Data Putusan Pengadilan Negeri Padang

Proyek ini mengumpulkan data putusan pengadilan negeri Padang yang diklasifikasikan berdasarkan jenis kasus narkotika dan psikotropika. Data ini mencakup putusan tahun 2022, 2023, dan 2024, dengan total 50 data, yang diambil secara manual dari direktori putusan Mahkamah Agung Republik Indonesia.

## Daftar Isi
- [Latar Belakang](#latar-belakang)
- [Fitur Proyek](#fitur-proyek)
- [Data Sumber](#data-sumber)
- [Struktur Direktori](#struktur-direktori)
- [Cara Pengumpulan Data](#cara-pengumpulan-data)
- [Cara Penggunaan](#cara-penggunaan)
- [Lisensi](#lisensi)

## Latar Belakang
Data putusan pengadilan sangat penting untuk analisis hukum, terutama dalam memahami pola dan klasifikasi kasus narkotika dan psikotropika. Proyek ini dirancang untuk mengumpulkan data terkait kasus tersebut dari situs Mahkamah Agung, sehingga dapat mendukung analisis hukum yang lebih terperinci.

## Fitur Proyek
- **Pengumpulan Data Manual**: Data putusan dari [direktori putusan Mahkamah Agung](https://putusan3.mahkamahagung.go.id/direktori.html) diunduh dan disusun secara manual.
- **Klasifikasi Kasus**: Fokus pada kasus narkotika dan psikotropika.
- **Periode Pengambilan Data**: Data mencakup putusan dari tahun 2022 hingga 2024, dengan total 50 putusan (20 dari 2022, 20 dari 2023, dan 10 dari 2024).
- **Penyimpanan Data**: Menyimpan data dalam bentuk PDF di direktori terstruktur dan file Excel untuk ringkasan.

## Data Sumber
Data diperoleh dari situs resmi Mahkamah Agung pada direktori berikut:  
[Direktori Putusan Pengadilan](https://putusan3.mahkamahagung.go.id/direktori.html)
Jumlah data berdasarkan tahun:
- **Tahun 2022**: 20 data putusan
- **Tahun 2023**: 20 data putusan
- **Tahun 2024**: 10 data putusan

## Struktur Direktori
Berikut struktur direktori untuk penyimpanan data hasil pengumpulan:

## Cara Pengumpulan Data
1. **Akses Situs Putusan**  
   Buka [Direktori Putusan Mahkamah Agung](https://putusan3.mahkamahagung.go.id/direktori.html).
2. **Filter dan Pilih Data**  
   Pilih direktori Pidana Khusus Pilih klasifikasi kasus narkotika dan psikotropika, Pilih Peradilan (PN Padang) serta tahun yang sesuai (2022, 2023, dan 2024).
3. **Unduh Data Putusan**  
   Unduh 20 data untuk tahun 2022, 20 data untuk tahun 2023, dan 10 data untuk tahun 2024, secara manual dalam format PDF.
4. **Buat Ringkasan Data**  
   Setelah pengunduhan selesai, masukkan ringkasan data ke dalam file `overview.xlsx` dengan struktur kolom:
   - **No.**
   - **No Putusan**
   - **Lembaga Peradilan**
   - **Barang Bukti**
   - **Amar Putusan**

## Cara Penggunaan
1. **Buka File PDF**  
   Data PDF putusan dapat diakses pada direktori `Narkotika.zip`.
2. **Lihat Ringkasan**  
   File `overview.xlsx` menyediakan ringkasan dari seluruh data yang diambil, memudahkan pencarian dan analisis ringkas.

## Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE). Anda bebas untuk menggunakan, menyalin, dan memodifikasi proyek ini sesuai kebutuhan Anda, selama tetap menyertakan lisensi yang sama.

---

**Catatan**: Harap mengikuti aturan dan etika penggunaan data, serta mematuhi regulasi dari Mahkamah Agung dalam penggunaan data putusan yang diperoleh dari situs resmi mereka.
