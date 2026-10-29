# **WS04: Problem Identification & Scope**

**Mata Kuliah**: Konsep Sistem Informasi (KSI)  
**Kerangka Kerja**: Project-Based Learning (PBL) Level 1  
**Fase Learning Spine**: **Fase 2 — Frame (Problem Discovery & Scope)**  
**Minggu / Alokasi Waktu**: Minggu 2 / 14 Jam Belajar  
**Sub-CPMK / SFIA**: S-01.1 (Introduce \- Problem Framing) \| SFIA BUSA L1 (*Business Analysis*), IRMG L1  
**Penanggung Jawab Fase**: **Phase Lead 2 (Frame — Mahasiswa B)**  
**Keterkaitan Deliverable**: Sumber Utama Penyusunan **Deliverable D1 (Problem Brief \- TPL-01)**

---

## **1\. Identifikasi Tim & Objek Proyek**

| Elemen Informasi | Rincian Identitas Kelompok & Mitra |
| :---- | :---- |
| **Nama Kelompok / Kelas** | \[ Isi Nama Kelompok / Kelas \] |
| **Phase Lead 2 (Frame \- M2)** | \[ Nama Mahasiswa B — NIM \] |
| **Nama UMKM Mitra Lapangan** | \[ Nama Usaha Mikro Mitra \] |
| **Pemilik / Kontak Mitra** | \[ Nama Pemilik Usaha \] |

---

## **2\. Matriks Problem Framing & Analisis Akar Masalah (Root Cause Analysis)**

Gunakan temuan kuantitatif dari `WS03` untuk memisahkan antara **Gejala Permukaan (*Symptoms*)** dan **Akar Masalah Utama (*Root Cause*)** operasional bisnis mitra:

| No | Kategori Observasi | Gejala Permukaan (*Symptoms*) | Akar Masalah Operasional (*Root Cause*) | Bukti Kuantitatif (*Baseline Data*) |
| :---: | :---- | :---- | :---- | :---- |
| **1** | **Proses Transaksi Kasir** | Antrean mengular panjang saat jam sibuk. | Pencatatan pesanan dan penghitungan total harga masih manual di buku nota. | Rata-rata waktu transaksi \= **90 detik/orang**. |
| **2** | **Pengelolaan Stok Barang** | Sering kehabisan stok barang populer secara mendadak. | Pengurangan stok tidak dicatat saat transaksi (*As-Is*), rekap stok hanya bulanan. | Selisih stok rata-rata **12% per bulan**. |
| **3** | **Rekapitulasi Keuangan** | Pemilik usaha lelah merekap penjualan setiap malam. | Nota kertas harus dihitung ulang dengan kalkulator dan ditulis ke spreadsheet manual. | Durasi rekap harian \= **60–90 menit/malam**. |

---

## **3\. Perumusan Problem Statement Kontekstual**

Berdasarkan analisis di atas, rumuskan **Problem Statement** utama dalam 1–2 paragraf terstruktur.  
*Petunjuk*: Hindari mendefinisikan masalah sebagai *"Mitra belum memiliki aplikasi Python/komputer"*. Definisikan dari hambatan bisnis nyata mitra\!

> **Rumusan Problem Statement Kelompok**:  
> *"Pencatatan transaksi dan inventaris yang masih dilakukan secara manual menggunakan buku kertas nota di \[Nama UMKM Mitra\] (kondisi As-Is) menyebabkan bottleneck operasional berupa waktu transaksi kasir yang lambat (90 detik/pelanggan), keterlambatan pemesanan ulang stok akibat selisih stok 12% per bulan, serta waktu rekapitulasi harian pemilik usaha yang memakan waktu hingga 1,5 jam setiap malam. Kondisi ini menghambat efisiensi operasional dan potensi pertumbuhan omzet mitra."*

---

## **4\. Menetapkan Batasan Sistem (System Boundary / Scope Alignment)**

Untuk mencegah terjadinya pembengkakan fitur (*Scope Creep*) yang membahayakan penyelesaian proyek dalam 1 semester, tentukan secara tegas apa yang **Masuk Cakupan (*In-Scope*)** dan apa yang **Di Luar Cakupan (*Out-of-Scope*)**:

```
 ┌───────────────────────────────────────────┐
 │                    SYSTEM BOUNDARY (BATASAN SISTEM)                    │
 │                                                                        │
 │   [ IN-SCOPE: Fitur yang Akan Dibangun ]                               │
 │   1. Pencatatan transaksi kasir berbasis konsol (CLI).                 │
 │   2. Pengurangan stok otomatis setiap transaksi berhasil.              │
 │   3. Pencetakan ringkasan rekapitulasi harian untuk pemilik.           │
 │                                                                        │
 │─────────────────────────────────────────── │
 │                                                                        │
 │   [ OUT-OF-SCOPE: Di Luar Cakupan Proyek ]                             │
 │   1. Integrasi gateway pembayaran e-wallet / QRIS otomatis.            │
 │   2. Fitur penggajian karyawan / manajemen HRD.                        │
 │   3. Pemesanan stok otomatis ke supplier luar.                         │   └────────────────────────────────────────────┘
```

### **Tabel Penegasan Cakupan Proyek (*Scope Alignment Table*)**

| No | Modul / Fitur Sistem | Status Cakupan (*In-Scope / Out-of-Scope*) | Alasan Pertimbangan Kelayakan (O'Brien) |
| :---: | :---- | :---: | :---- |
| **1** | Input Transaksi & Kalkulasi Total | **IN-SCOPE** | Kelayakan Operasional: Sangat dibutuhkan kasir untuk mempercepat transaksi. |
| **2** | Update Stok Otomatis | **IN-SCOPE** | Kelayakan Teknis: Dapat diimplementasikan dengan logika struktur data Python. |
| **3** | Laporan Rekap Harian (Laba/Rugi) | **IN-SCOPE** | Kelayakan Ekonomi: Memberikan nilai *Value of Information* bagi pemilik usaha. |
| **4** | Pembayaran Online / Payment Gateway | **OUT-OF-SCOPE** | Keterbatasan waktu 1 semester & kompleksitas API luar di PBL Level 1\. |
| **5** | Multi-Branch / Banyak Cabang | **OUT-OF-SCOPE** | Mitra saat ini hanya memiliki 1 lokasi usaha operasional. |

---

## **5\. Target Metrik Keberhasilan Solusi (To-Be Targets)**

Tentukan target kuantitatif perbaikan yang ingin dicapai melalui solusi sistem informasi To-Be:

| Indikator Kinerja | Kondisi As-Is (Baseline) | Target To-Be (Expected) | Estimasi Persentase Peningkatan |
| :---- | :---: | :---: | :---: |
| **Waktu Pelayanan Transaksi Kasir** | 90 detik / pelanggan | **\< 30 detik / pelanggan** | Peningkatan efisiensi **66.7%** |
| **Durasi Rekapitulasi Harian** | 60–90 menit / malam | **\< 10 menit / malam** | Penghematan waktu **83.3%** |
| **Akurasi Pencatatan Stok** | Selisih 12% / bulan | **Akurasi \> 98%** | Penurunan tingkat kesalahan selisih stok |

---

## **6\. Refleksi & Lembar Pengesahan Phase Lead**

### **A. Pertanyaan Refleksi Tim**

1. *Bagaimana tim memastikan bahwa batasan proyek yang ditetapkan realistis untuk diselesaikan dalam 16 minggu?*  
   * **Jawab**: \[ Jelaskan analisis kelayakan teknis dan kemampuan tim \]  
2. *Apakah pemilik usaha mitra telah menyetujui batasan sistem yang diusulkan oleh kelompok?*  
   * **Jawab**: \[ Jelaskan hasil konfirmasi awal ke mitra \]

### **B. Tanda Tangan Pengesahan Phase Lead 2**

```
Disusun oleh Phase Lead 2 (Frame): [ Nama Mahasiswa B — NIM ]
Tanggal Penyusunan: [ Tanggal ]

Tanda Tangan Phase Lead 2: ____________________

Diverifikasi oleh Dosen Pengampu / Coach:
Tanggal: [ Tanggal ] | Status Checkpoint: [ APPROVED / REVISION NEEDED ]
Catatan Dosen: __________________________________________________
```

