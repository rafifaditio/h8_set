# **LIVECODE 2**

---

_Graded Challenge ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada Sql dan Pandas._

---

## Dataset Description

Pada graded challenge ini, data diakses dari BigQuery dengan ketentuan:

- **Project_id**: `hacktiv8-ftds-challenge`
- **Dataset**   : `livecode_02`
- **Tabel**     : `taxi_fare`

---
---

## Assignment Problems

Kamu adalah seorang Data Analyst yang sedang melakukan analisa data perjalanan dari penyedia jasa transportasi di kotamu. Pada tahapan ini analisa yang dilakukan masih bersifat preliminary, sebagai landasan untuk analisa utama.

**Analisa yang kamu lakukan kali ini terbagi menjadi 2 section; SQL dan Pandas.** Pada SQL akan dilakukan overview EDA analysis, sementara pada section Pandas akan dilakukan persiapan data untuk analisa lebih lanjut. Penjabaran dari apa yang akan kamu lakukan tertera di masing-masing section berikut:

### Problem 1 - SQL

Jawab masing-masing pertanyaan ini dengan 1 query:

1. Apa saja nama perusahaan yang terdapat dalam data?
2. Berapa nilai minimum dan maksimum dari waktu pengambilan data?
3. Bandingkan jumlah banyaknya perjalanan antara seluruh perusahaan di setiap tahun yang ada?
4. Perusahaan mana yang memiliki tarif perjalanan per km termurah? (Narasikan asumsi dan pertimbangan langkahmu dalam menjawab pertanyaan ini, narasikan insightnya)

### Problem 2 - Pandas

Pengambilan data dari SQL untuk diolah di pandas **wajib** menggunakan query di bawah ini:

<div align="center">

`SELECT * FROM hacktiv8-ftds-challenge.livecode_02.taxi_fare`

</div>

1. buat kolom baru, menunjukkan representasi keterangan waktu dengan ketentuan berikut:

<div align="center">

|Keterangan Waktu|Jam|	
|--|--|
|Pagi|04:00 - 09:59|
|Siang|10:00 - 15:59|
|Sore|16:00 - 18:59|
|Malam|19:00 - 23:59|
|Dini Hari|00:00 - 03:59|

</div>

2. Berapa total jarak perjalanan yang dicapai perusahaan Federway Int. pada tahun 2022? (Gunakan pandas query untuk menjawab soal no. 2)

>**Hints:**

>- Dalam mengerjakan soal Pandas poin 1, Untuk melakukan ekstraksi waktu (jam) dapat memanfaatkan `pd.Series.dt.hour`, pastikan kolom yang akan di-ekstrak sudah memiliki format *datetime*.
>- Setelah melakukan ekstraksi waktu (jam), lakukan looping dan kondisional untuk setiap entry data sesuai ketentuan kondisi keterangan waktu diatas.
>- Simpan looping dan kondisional ke dalam list dan convert menjadi kolom baru.

---
## Assignment Submission

- Simpan assignment pada sesi ini dengan nama `h8dsft_P0LC2_<nama-student>.ipynb`, misal `h8dsft_P0LC2_raka_ardhi.ipynb`.
- Push Assigment yang telah kalian buat ke repository Github Classroom masing-masing student.
---
## Assignment Objectives

*Live Code 2* ini dibuat guna mengevaluasi SQL dan Pandas sebagai berikut:

- Mampu melakukan analisa data di SQL.
- Mampu melakukan pengambilan data dari SQL.
- Mampu melakukan pengolahan data di pandas.
- Mampu menerapkan looping, conditional, serta query agggregation menggunakan pandas.

---

## Assignment Rubrics

<img src="--"></img>

---

```
Total Points : --
```
