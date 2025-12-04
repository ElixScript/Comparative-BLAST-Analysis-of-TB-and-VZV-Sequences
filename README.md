# Comparative-BLAST-Analysis-of-TB-and-VZV-Sequences

Repository ini berisi implementasi analisis bioinformatika menggunakan **NCBI BLAST** untuk mengidentifikasi dua sekuens biologis:

1. gen **rpoB** dari *Mycobacterium tuberculosis*, dan
2. protein **Thymidine Kinase (TK)** dari *Varicella Zoster Virus (VZV)*.

---

## 🔬 **Deskripsi Singkat**

**Comparative BLAST Sequence Analysis**

---

## 🧬 **Tujuan Proyek**

* Melakukan pencarian kemiripan sekuens menggunakan **Blast.qblast()**
* Mengidentifikasi organisme berdasarkan database NCBI (nt & nr)
* Membandingkan nilai **E-value**, **Bit score**, dan **Identity**
* Memverifikasi validitas biologis dari dua sekuens berbeda

---

## 🛠️ **Teknologi yang Digunakan**

* **Python**
* **Biopython (Bio.Blast, Bio.SeqIO)**
* **Google Colab**
* **NCBI BLAST (QBLAST API)**

---

## 📊 **Isi Notebook**

Notebook utama (`notebook.ipynb`) mencakup:

* Pembacaan file FASTA
* Pengiriman query ke NCBI BLAST
* Penyimpanan hasil sebagai XML
* Parsing struktur hasil BLAST
* Ringkasan 5 hit teratas (ID, Deskripsi, Panjang, E-value, Identity, Bit Score)
* Analisis biologis untuk kedua sekuens

---

## 📑 **Presentasi**

Hasil analisis dan visualisasi terdapat dalam file:

**`Final Project BioInformatika.pdf`**
Berisi:

* Penjelasan data
* Tabel output BLAST
* Analisis Sequence 1 (rpoB – Tuberkulosis)
* Analisis Sequence 2 (TK – Varicella Zoster Virus)
* Kesimpulan komputasional dan biologis

---

## 👥 **Kontributor**

Kelompok 2 – Bioinformatika

* Athaya Naura Khalilah
* Bagus Cipta Pratama
* Kosmas Rio Legowo
* Muhammad Akmal Fauzan
* Muhammad Hanif Zuhair

Jika ingin README versi yang lebih panjang, lebih akademik, atau ditambah visual diagram workflow BLAST, tinggal bilang!
