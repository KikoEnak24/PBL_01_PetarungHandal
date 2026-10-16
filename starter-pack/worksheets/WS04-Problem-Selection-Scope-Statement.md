### WS04 — Problem Selection & Scope Statement

**Worksheet Number**: WS04
**Title**: Pemilihan Masalah & Pernyataan Batasan (Evidence → Insight → Problem)
**Related Deliverable**: D1 (Problem Brief).

### Activity

1. Dari temuan observasi, tuliskan 3 calon masalah.
2. Nilai setiap calon: kepentingan bagi pemilik, keterukuran, dan kesesuaian dengan batasan teknis.
3. Pilih satu masalah utama + tulis insight mengapa masalah ini muncul.
4. Tulis pernyataan batasan: apa yang diselesaikan, apa yang TIDAK diselesaikan, dan alasannya.

### Identifikasi Tim & Objek Proyek

| Elemen Informasi | Rincian Identitas Kelompok & Mitra |
| Nama Kelompok / Kelas | Petarung Handal / B |
| Phase Lead 2 (Frame - M2) | Keyza Nada Afifa - 2638016081 |
| Nama UMKM Mitra Lapangan | Kafe Basabasi|
| Penanggung Jawab / Kontak Mitra | Mas Jaka |

### Matriks Problem Framing & Analisis Akar Masalah (Root Cause Analysis)

| Kategori Observasi | Gejala Permukaan (Symptoms) | Akar Masalah Operasional (Root Cause) | Bukti Kuantitatif (Baseline Data) |

1. | Proses Transaksi Kasir | Antrean mengular panjang saat jam sibuk. | Pencatatan pesanan dan penghitungan total harga masih manual di buku nota. | Rata-rata waktu transaksi = 90 detik/orang. |
2. | Pengelolaan Stok Barang | Sering kehabisan stok barang populer secara mendadak | Pengurangan stok tidak dicatat saat transaksi (As-Is), rekap stok hanya bulanan. | Selisih stok rata-rata 12% per bulan. |
3. | Rekapitulasi Keuangan | Pemilik usaha lelah merekap penjualan setiap malam. | Nota kertas harus dihitung ulang dengan kalkulator dan ditulis ke spreadsheet manual. | Durasi rekap harian = 60–90 menit/malam. |

### Perumusan Problem Statement Kontekstual

"Pencatatan transaksi dan inventaris yang masih dilakukan secara manual menggunakan buku kertas nota di [Nama UMKM Mitra] (kondisi As-Is) menyebabkan bottleneck operasional berupa waktu transaksi kasir yang lambat (90 detik/pelanggan), keterlambatan pemesanan ulang stok akibat selisih stok 12% per bulan, serta waktu rekapitulasi harian pemilik usaha yang memakan waktu hingga 1,5 jam setiap malam. Kondisi ini menghambat efisiensi operasional dan potensi pertumbuhan omzet mitra."

### Menetapkan Batasan Sistem (System Boundary / Scope Alignment)

No | Modul / Fitur Sistem | Status Cakupan (In-Scope / Out-of-Scope) | Alasan Pertimbangan Kelayakan (O'Brien)

1. Input Transaksi & Kalkulasi Total | IN-SCOPE | Kelayakan Operasional: Sangat dibutuhkan kasir untuk mempercepat transaksi.|
2. Update Stok Otomatis | IN-SCOPE | Kelayakan Teknis: Dapat diimplementasikan dengan | logika struktur data Python.|
3. Laporan Rekap Harian (Laba/Rugi) | IN-SCOPE | Kelayakan Ekonomi: Memberikan nilai Value of Information bagi pemilik usaha.|
4. Pembayaran Online / Payment Gateway | OUT-OF-SCOPE | Keterbatasan waktu 1 semester & kompleksitas API luar di PBL Level 1.|
5. Multi-Branch / Banyak Cabang | OUT-OF-SCOPE | Mitra saat ini hanya memiliki 1 lokasi usaha operasional.|

### Target Metrik Keberhasilan Solusi (To-Be Targets)

| Indikator Kinerja | Kondisi As-Is (Baseline) | Target To-Be (Expected) | Estimasi Persentase Peningkatan |

1. | Waktu Pelayanan Transaksi Kasir | 90 detik / pelanggan | < 30 detik / pelanggan | Peningkatan efisiensi 66.7% |
2. | Durasi Rekapitulasi Harian | 60–90 menit / malam | < 10 menit / malam | Penghematan waktu 83.3% |
3. | Akurasi Pencatatan Stok | Selisih 12% / bulan | Akurasi > 98% | Penurunan tingkat kesalahan selisih stok |

### Reflection
- Bagaimana tim memastikan bahwa batasan proyek yang ditetapkan realistis untuk diselesaikan dalam 16 minggu?
- Apakah pemilik usaha mitra telah menyetujui batasan sistem yang diusulkan oleh kelompok?

### Tanda Tangan Pengesahan Phase Lead 2

Disusun oleh Phase Lead 2 (Frame): [ Keyza Nada Afifa — 2638016081 ]
Tanggal Penyusunan: [ 16 Oktober 2026 ]

Tanda Tangan Phase Lead 2: ____________________

Diverifikasi oleh Dosen Pengampu / Coach:
Tanggal: [ Tanggal ] | Status Checkpoint: [ APPROVED / REVISION NEEDED ]

Catatan Dosen: __________________________________________________

### Checklist
- [ ] Tiga calon masalah dinilai dengan bukti
- [ ] Satu masalah terpilih dengan alasan & insight
- [ ] Batasan (scope) ditulis dan disepakati tim
- [ ] Masuk ke draf D1

---