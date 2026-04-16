# Analisis KPI Transaksi Nasabah Bank Jago Berbasis Data Warehouse

Project ini bertujuan untuk menganalisis Key Performance Indicator (KPI) transaksi nasabah Bank Jago dengan memanfaatkan data warehouse. Data dari sistem operasional (OLTP) diolah melalui proses ETL (Extract, Transform, Load) menggunakan Pentaho, kemudian dianalisis menggunakan Python (Google Colab) dan divisualisasikan melalui dashboard interaktif di Looker Studio. Hasil analisis digunakan untuk membantu pengambilan keputusan berbasis data.

---

## Objective

* Mengevaluasi tingkat keaktifan nasabah
* Mengukur kinerja finansial berdasarkan nilai transaksi
* Menilai rata-rata transaksi per nasabah
* Mengelompokkan nasabah berdasarkan pola transaksi
* Menganalisis kontribusi transaksi tiap segmen

---

## KPI yang Digunakan

* Total Nasabah Aktif
* Total Transaksi
* Total Nilai Transaksi
* Rata-rata Transaksi per Nasabah
* Segmentasi Nasabah
* Distribusi & Rata-rata Transaksi per Segment

---

## Arsitektur Project

1. **Data Source (OLTP)** → Data transaksi mentah
2. **ETL Process (Pentaho)** → Extract, Transform, Load
3. **Data Warehouse (MySQL)** → Star Schema
4. **Data Analysis (Google Colab)** → Data mining & clustering
5. **Visualization (Looker Studio)** → Dashboard KPI

---

## Struktur Folder

```
bank-jago-kpi-dwh/
│
├── data/                  # Dataset
├── etl_pentaho/           # File .ktr / .kjb
├── sql/                   # DDL & query SQL
├── notebook/              # Google Colab (.ipynb)
├── dashboard/             # Screenshot dashboard
├── docs/                  # Laporan (PDF)
└── README.md
```

---

## Tools & Technology

* Pentaho Data Integration (ETL)
* MySQL (Data Warehouse)
* Python (Google Colab)
* Looker Studio (Dashboard)
* GitHub (Version Control)

---

## Link Project

*  Dashboard Looker Studio: *(https://lookerstudio.google.com/reporting/09fa612c-7fd1-42aa-afa6-a9574bdb4320)*
*  Data / Resources: *(kaggle)*
*  Dokumen : *(https://drive.google.com/file/d/1sFt8fq3qadPguWwqnyf5T7qkWCF5W20y/view?usp=sharing)*

---

##  Hasil Analisis

* Tingkat keaktifan nasabah tergolong tinggi
* Volume dan nilai transaksi menunjukkan performa finansial yang baik
* Segmentasi nasabah berhasil mengidentifikasi pola perilaku transaksi
* Dashboard KPI membantu monitoring kinerja secara real-time

---

##  Catatan
* Project ini dibuat untuk tujuan pembelajaran dan analisis akademik
