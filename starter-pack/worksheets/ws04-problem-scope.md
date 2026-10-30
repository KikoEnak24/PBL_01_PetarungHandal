**WS04: Problem Identification & Scope**

**Mata Kuliah**: Konsep Sistem Informasi (KSI)  
**Kerangka Kerja**: Project-Based Learning (PBL) Level 1  
**Fase Learning Spine**: **Fase 2 — Frame (Problem Discovery & Scope)**  
**Minggu / Alokasi Waktu**: Minggu 2 / 14 Jam Belajar  
**Sub-CPMK / SFIA**: S-01.1 (Introduce \- Problem Framing) \| SFIA BUSA L1 (*Business Analysis*), IRMG L1  
**Penanggung Jawab Fase**: **Phase Lead 2 (Frame — Mahasiswa B)**  
**Keterkaitan Deliverable**: Sumber Utama Penyusunan **Deliverable D1 (Problem Brief \- TPL-01)**

---

**1\. Identifikasi Tim & Objek Proyek**

| Elemen Informasi | Rincian Identitas Kelompok & Mitra |
| :---- | :---- |
| **Nama Kelompok / Kelas** | Petarung Handal / B |
| **Phase Lead 2 (Frame \- M2)** | Keyza Nada Afifa — 2638016081 |
| **Nama UMKM Mitra Lapangan** | Kafe Basabasi |
| **Pemilik / Kontak Mitra** | Jaka / Penanggung Jawab Kafe Basabasi cabang kragilan  |

---

**2\. Matriks Problem Framing & Analisis Akar Masalah (Root Cause Analysis)**

Gunakan temuan kuantitatif dari WS03 untuk memisahkan antara **Gejala Permukaan (*Symptoms*)** dan **Akar Masalah Utama (*Root Cause*)** operasional bisnis mitra:

| No | Kategori Observasi | Gejala Permukaan (*Symptoms*) | Akar Masalah Operasional (*Root Cause*) | Bukti Kuantitatif (*Baseline Data*) |
| :---- | :---- | :---- | :---- | :---- |
| **1** | **Identifikasi Pelanggan dan Pengantaran Pesanan**  | Pesanan sulit diantar ke pelanggan yang tepat, dan pelanggan sering ditanya ulang soal posisi duduknya.  | Pelanggan dan lokasi duduknya tidak dicatat, dan belum ada sistem nomor meja yang menghubungkan pesanan dengan pelanggan.  | 6 kali observasi dengan sudut pandang pengguna yang tidak berubah yaitu tidak ada pencatatan nama atau nomor meja pelanggan yang memesan.  |
| **2** | **sistem pemesanan digital (Barcode dimeja)** | Pesanan via barcode gagal masuk ke kasir.  | Aplikasi kasir tidak diaktifkan oleh kasir.  | 6 kali observasi dengan 3 kali tidak bisa di akses barcode nya. |
| **3** | **Akurasi Pesanan**  | Pesanan yang diterima tidak sesuai permintaan.  | Tidak ada konfirmasi ringkasan pesanan sebelum diteruskan ke dapur.  | 23 kali pesanan dengan 3 kali kesalahan pesanan. |

---

**3\. Perumusan Problem Statement Kontekstual**

**Rumusan Problem Statement Kelompok**:  
*“Absensi karyawan di Kafe Basabasi masih menggunakan foto selfie yang dikirim ke grup WhatsApp (kondisi As-Is). Cara ini sering sekali dicurangi, misalnya karyawan mengirim foto kemarin untuk absen hari ini. Akibatnya, penanggung jawab kafe tidak tahu siapa yang benar-benar hadir, shift jadi kekurangan orang, antrean pelanggan panjang, dan karyawan yang masuk kerjanya jadi lebih berat.”* 

---

**4\. Menetapkan Batasan Sistem (System Boundary / Scope Alignment)**

Untuk mencegah terjadinya pembengkakan fitur (*Scope Creep*) yang membahayakan penyelesaian proyek dalam 1 semester, tentukan secara tegas apa yang **Masuk Cakupan (*In-Scope*)** dan apa yang **Di Luar Cakupan (*Out-of-Scope*)**:

 ┌──────────────────────────────────────────────────────┐

 │                    SYSTEM BOUNDARY (BATASAN SISTEM)                             │

 │                                                                                                                                     │

 │   \[ IN-SCOPE: Fitur yang Akan Dibangun \]                                                │

 │   1\. Absensi karyawan dengan scan barcode saat masuk dan pulang sesuai shift.                          │

 │   2\. Pencatatan tanggal dan jam kehadiran secara otomatis.               │

 │   3\. Pencetakan rekap kehadiran harian dan bulanan untuk pemilik.          │

 │                                                                                                                                        │

 │  ───────────────────────────────────────────                            │

 │                                                                                                                                        │

 │   \[ OUT-OF-SCOPE: Di Luar Cakupan Proyek \]                                         │

 │   1\. Absensi pakai sidik jari atau pengenalan wajah.           │

 │   2\. Hitung gaji karyawan otomatis.                                │

 │   3\. Penerapan sistem di cabang kafe lainnya.                                      │

 │   ────────────────────────────────────────────────────── │

**Tabel Penegasan Cakupan Proyek (*Scope Alignment Table*)**

| No | Modul / Fitur Sistem | Status Cakupan (*In-Scope / Out-of-Scope*) | Alasan Pertimbangan Kelayakan (O'Brien) |
| :---- | :---- | :---- | :---- |
| **1** | Scan Barcode Absen Masuk & Pulang  | **IN-SCOPE** | Kelayakan Operasional: Menjadi solusi utama karena karyawan tidak bisa lagi memakai foto lama untuk absen.   |
| **2** | Pencatatan Jam Kehadiran Otomatis  | **IN-SCOPE** | Kelayakan Teknis: Bisa dibuat dengan mengambil jam dan tanggal dari sistem secara langsung saat barcode di-scan.  |
| **3** | Rekap Kehadiran Harian & Bulanan  | **IN-SCOPE** | Kelayakan Ekonomi: Pemilik tidak perlu lagi mengecek foto satu per satu di grup WhatsApp, sehingga menghemat waktu.  |
| **4** | Absensi Sidik Jari / Pengenalan Wajah  | **OUT-OF-SCOPE** | Kelayakan Ekonomi: Perlu membeli alat tambahan, sedangkan proyek ini hanya berjalan 1 semester dengan anggaran terbatas.   |
| **5** | Multi-Branch / Banyak Cabang | **OUT-OF-SCOPE** | Kafe mitra punya banyak cabang, tetapi kerja sama proyek ini hanya dengan 1 cabang, jadi sistem hanya dibuat untuk cabang tersebut.   |

---

**5\. Target Metrik Keberhasilan Solusi (To-Be Targets)**

Tentukan target kuantitatif perbaikan yang ingin dicapai melalui solusi sistem informasi To-Be:

| Indikator Kinerja | Kondisi As-Is (Baseline) | Target To-Be (Expected) | Estimasi Persentase Peningkatan |
| :---- | :---- | :---- | :---- |
| **Rata-rata waktu transaksi per pelanggan** | 102 detik / 1 menit 42 detik | \< 50 detik / pelanggan | Peningkatan efisiensi 50.9% |
| **Durasi Rekapitulasi Harian** | 15 hingga 20 menit  | \< 10 menit / malam | Penghematan waktu 43% |
| **Frekuensi restok bahan baku** | setiap 2 hari sekali (tanggal genap) | Restock terjadwal dan tercatat, tanpa bahan habis mendadak  | tidak dihitung karena indikator jadwal bukan waktu. |

---

**6\. Refleksi & Lembar Pengesahan Phase Lead**

**A. Pertanyaan Refleksi Tim**

1. *Bagaimana tim memastikan bahwa batasan proyek yang ditetapkan realistis untuk diselesaikan dalam 16 minggu?*

   ***\[Keyza Nada Afifa\]** Dengan menyelesaikan tugas proyek di setiap minggu sesuai dengan tenggat waktu yang ditentukan.*

   ***\[Refina Ambar Melati\]** Selalu memprioritaskan tugas proyek di saat waktu luang atau tidak mementingkan nongkrong dan bermain yg melalaikan tugas proyek ini terabaikan* 

   ***\[Diza Gadiza El-Said\]** Dengan mengerjakan setiap tugas dan selalu memastikan setiap tugas terlaksana.*

   ***\[Nayla Ayudya Putri\]** mengerjakan sesuai dengan jadwal yang telah disepakati oleh tim*

   ***\[Raihan Khairul Putra Pratama\]** memastikan waktu yang digunakan untuk mengerjakan proyek cukup.*

2. *Apakah pemilik usaha mitra telah menyetujui batasan sistem yang diusulkan oleh kelompok?*

   ***\[Keyza Nada Afifa\]** Mitra menyetujui Batasan yang kami berikan kepada mereka, dan sedikit koreksi dengan ada yang ditambahkan dan dikurangkan.*

   ***\[Refina Ambar Melati\]** Ya mitra telah menyetujui gambaran dari rancangan  sistem yang sudah kami usulkan berdasarkan diskusi 2 arah antara kami dan mitra telah menghasilkan saran dan jalan keluar dari keluhan yang mitra alami pada usahanya.*

   ***\[Diza Gadiza El-Said\]** ya mitra setuju terhadap batasan sistem yang diusulkan.*

   ***\[Nayla Ayudya Putri\]** Mereka menerima setiap masukan dari kami dan sedikit mengoreksi jika ada yang tidak sesuai.*

   ***\[Raihan Khairul Putra Pratama\]** Mitra setujuu dengan masukan yang kami berikan.*

   

**B. Tanda Tangan Pengesahan Phase Lead 2**

Disusun oleh Phase Lead 2 (Frame):  Keyza Nada Afifa        

Tanggal Penyusunan: 16/10/2026

Tanda Tangan Phase Lead 2:  ![][image1]

Diverifikasi oleh Dosen Pengampu / Coach: **Imam Azhari, [S.Si](http://S.Si)., M.Cs.**

Tanggal: \[ Tanggal \] \| Status Checkpoint: \[ APPROVED / REVISION NEEDED \]

Catatan Dosen: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

[image1]: <data:image/png;base64,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>