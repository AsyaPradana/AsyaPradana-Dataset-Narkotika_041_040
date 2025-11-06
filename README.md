# 🏛️ Dataset Narkotika – Putusan Pengadilan Indonesia

Repositori ini berisi kumpulan **50 dokumen putusan pengadilan** terkait **kasus tindak pidana narkotika**, yang dikumpulkan dari berbagai sumber terbuka seperti **Direktori Putusan Mahkamah Agung Republik Indonesia**.

Dataset ini disusun untuk kepentingan **penelitian Temu Kembali Informasi (Information Retrieval)** pada dokumen hukum, khususnya dalam konteks pencarian teks hukum berbasis machine learning, NLP, dan analisis semantik.

---

## 📂 Struktur Direktori

Dataset-Narkotika_041_040/
│

├── 📁 Dataset
│ └── Narkotika.zip ← Berisi 50 dokumen putusan (*.pdf)
│

├── 📁 Overview
│ └── Overview.xlsx ← Summary dari 50 dokumen putusan
│
└── 📄 README.md ← Dokumentasi proyek



---

## 📘 Deskripsi Dataset

- **Jumlah dokumen:** 50 file putusan pengadilan
- **Format dokumen:** Portable Document Format (*.pdf)
- **Bahasa:** Bahasa Indonesia
- **Jenis perkara:** Tindak pidana narkotika
- **Sumber utama:** [Direktori Putusan Mahkamah Agung RI](https://putusan3.mahkamahagung.go.id/)
- **Tahun putusan:** Beragam antara 2023–2025

---

## 📊 File Overview.xlsx

File ini berisi metadata dari setiap putusan dalam bentuk tabel.  
Berikut adalah kolom yang terdapat pada file `Overview.xlsx`:

|        Kolom          |              Deskripsi               |
|-----------------------|--------------------------------------|
| No                    | Nomor urut dokumen                   |
| Nomor Putusan         | Nomor resmi putusan dari pengadilan  |
| Lembaga Pengadilan    | Nama pengadilan yang memutus perkara |
| Amar Putusan          | Ringkasan hukuman yang dijatuhkan    |

---

## 🧠 Tujuan Penggunaan

Dataset ini disiapkan untuk:
- Penelitian **Temu Kembali Informasi (Information Retrieval)** pada teks hukum  
- Eksperimen **Text Mining**, **Natural Language Processing (NLP)**, dan **Text Classification**  
- Analisis pola bahasa hukum dan sentimen pada putusan pengadilan  
- Pengembangan **search engine hukum berbasis semantik**

---

## 🧰 Cara Menggunakan

1. Unduh berkas `Narkotika.zip` dari folder `Dataset`
2. Ekstrak berkas ZIP ke direktori lokal Anda
3. Gunakan skrip NLP, text mining, atau IR untuk melakukan analisis teks terhadap dokumen `.pdf`
4. Gunakan metadata dari `Overview.xlsx` untuk memetakan hasil analisis ke atribut hukum (no putusan lembaga, dll)

---

## ⚖️ Lisensi

Dataset ini bersifat **non-komersial** dan hanya digunakan untuk tujuan **pendidikan, penelitian, dan pengembangan ilmu pengetahuan**.  
Sumber data tetap menjadi hak dari **Mahkamah Agung Republik Indonesia**.

---

## 👥 Kontributor

- **Asya Cahya Pradana** – NIM: 202210370311041  
- **Ahmad Rifsa Danovan** – NIM: 202210370311040  

Fakultas **Teknik**

Program Studi **Informatika**  
**Universitas Muhammadiyah Malang**
2025

---




