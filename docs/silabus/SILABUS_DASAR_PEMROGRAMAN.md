# Silabus — Dasar Pemrograman

**Digital Problem Framing Mini Project** | Program Studi Sistem Informasi | Semester 1 | Tahun Akademik 2026/2027

Version : Rilis 1.0 | Last Updated : 2026-10-01
Status : Dokumen publik

Dokumen terkait:
- [Panduan Mahasiswa](../PANDUAN_MAHASISWA.md)
- [Panduan Dosen](../PANDUAN_DOSEN.md)
- [Panduan Mentor](../PANDUAN_MENTOR.md)
- [Worksheet Book](../WORKSHEET_BOOK.md)
- [Template Pack](../TEMPLATE_PACK.md)
- [Assessment Rubrics](../ASSESSMENT_RUBRICS.md)
- [Jadwal Semester](../JADWAL_SEMESTER.md)
- [Silabus Konsep Sistem Informasi](SILABUS_KONSEP_SI.md)
- [Silabus Komunikasi Profesional & Kerja Tim](SILABUS_KOMUNIKASI_PROFESIONAL.md)
- [Silabus Bahasa Inggris](SILABUS_BAHASA_INGGRIS.md)

---

## Cara Membaca Dokumen Ini

Proyek ini memakai beberapa kode agar semua dokumen saling terhubung. Kode berikut dipakai konsisten
di seluruh repository ini.

| Kode | Arti |
|---|---|
| `WS01`–`WS16` | Worksheet — lembar kerja yang diisi mahasiswa tiap pekan |
| `D1`–`D4` | Dokumen proyek utama — empat hasil yang harus diselesaikan tim |
| `E1`–`E7` | Lampiran pendukung `D4` (bukti eksekusi, log, deklarasi penggunaan AI, portofolio) |
| `TPL-01`–`TPL-11` | Instrumen penilaian — rubrik yang dipakai dosen |
| **CPL** | Capaian Pembelajaran Lulusan — kompetensi yang harus dimiliki alumni saat lulus |
| **CPMK** | Capaian Pembelajaran Mata Kuliah — kompetensi yang dituju satu mata kuliah |
| **Sub-CPMK** | Poin kemampuan kecil di dalam CPMK yang dinilai pada mata kuliah ini, contoh `S-03.5` |
| **Fase** | Tahapan proyek: Discover, Frame, Define, Design, Build, Test, Communicate, Reflect |
| **GATE 1 / GATE 2** | Titik persetujuan resmi pada Minggu 8 dan 13. Tim tidak boleh lanjut tanpa persetujuan ini |
| **SKS** | Satuan kredit semester. 1 SKS = 45 jam |

---

## 1) Identitas Mata Kuliah

| Komponen | Nilai |
|---|---|
| Nama Mata Kuliah | Dasar Pemrograman |
| SKS | 4 (180 jam per semester) |
| Semester | 1 |
| Kelompok Mata Kuliah | Fondasi Sistem & Kebutuhan |
| Posisi dalam PBL | Pemilik `D3` (Tested Solution Prototype) |
| Capaian Mata Kuliah | CPMK-03, dengan dukungan CPMK-07 |
| Sub-CPMK yang dimiliki | S-03.5 (tingkat perkenalan) |
| Rujukan Kurikulum 2020 | Dasar bahasa pemrograman dan dasar pengembangan perangkat lunak |

---

## 2) Deskripsi

Mata kuliah ini memperkenalkan konsep dasar pemrograman sebagai fondasi pengembangan solusi
komputasional. Mahasiswa mempelajari tipe data dasar, kontrol alur, fungsi, dan struktur solusi
sederhana.

Pembelajaran dilakukan melalui praktikum langsung, latihan menulis kode, dan proyek kecil yang
menyelesaikan masalah nyata milik unit usaha di sekitar kampus. Bahasa yang dipakai adalah Python.

Mata kuliah ini merupakan mata kuliah inti proyek PBL Level 1 dan menjadi pemilik `D3`, yaitu
prototipe program yang harus berjalan dan sudah diuji bersama pengguna.

---

## 3) Capaian Pembelajaran

### 3.1 Dalam Bahasa Sederhana

Pada akhir mata kuliah ini, mahasiswa mampu:

1. **Menulis program sederhana dengan benar.** Memilih tipe data yang tepat dan memastikan alur
   program berjalan sesuai kebutuhan.
2. **Mengubah desain menjadi kode.** Membaca rancangan input–proses–output lalu menerjemahkannya
   menjadi program yang bisa dijalankan.
3. **Menguji dan memperbaiki.** Menyusun kasus uji, menemukan kesalahan, dan memperbaiki program.
4. **Menjelaskan kodenya sendiri.** Menjelaskan program baris demi baris, termasuk bagian yang
   dibantu AI. Kemampuan menjelaskan ini wajib dibuktikan pada GATE 2.

### 3.2 Capaian Pembelajaran Lulusan (CPL)

| CPL | Rumusan |
|---|---|
| CPL-03 | Merancang arsitektur solusi SI yang mengintegrasikan proses, data, aplikasi, dan infrastruktur |

### 3.3 Capaian Pembelajaran Mata Kuliah (CPMK) dan Sub-CPMK

| CPMK | Sub-CPMK | Tingkat | Rumusan Sub-CPMK |
|---|---|---|---|
| CPMK-03 — Merancang arsitektur solusi SI yang mengintegrasikan proses, data, aplikasi, dan infrastruktur | S-03.5 | Perkenalan | Menerapkan konstruksi pemrograman dasar (tipe data, kontrol alur, fungsi) untuk mewujudkan solusi komputasional sederhana |

### 3.4 Peta Capaian

```
CPL-03 ──→ CPMK-03 ──→ S-03.5 — Pemrograman dasar
```

---

## 4) Bahan Kajian

| No | Bahan Kajian | Sub-CPMK |
|---|---|---|
| 1 | Melihat masalah dari sisi komputasi | S-03.5 |
| 2 | Tipe data dasar: bilangan bulat, desimal, teks, benar-salah | S-03.5 |
| 3 | Kontrol alur: percabangan dan perulangan | S-03.5 |
| 4 | Fungsi dan modularisasi | S-03.5 |
| 5 | Transformasi data sederhana | S-03.5 |
| 6 | Struktur solusi sederhana: input, proses, output | S-03.5 |
| 7 | Pencarian kesalahan dan pengujian dasar | S-03.5 |

---

## 5) Mata Kuliah Pendukung

Empat mata kuliah berjalan sebagai satu proyek. Setiap mata kuliah memiliki peran yang berbeda,
namun semuanya menghasilkan bagian dari dokumen yang sama.

| Mata Kuliah | Peran dalam Proyek |
|---|---|
| Konsep Sistem Informasi | Melihat masalah dan memetakan komponen sistem — pemilik `D1` dan `D2` |
| Dasar Pemrograman | Membangun solusi komputasional sederhana — pemilik `D3` |
| Komunikasi Profesional & Kerja Tim | Cara kerja tim dan penyampaian hasil — pemilik bersama `D4` |
| Bahasa Inggris | Penulisan profesional dan presentasi — pemilik bersama `D4` |

---

## 6) Strategi Pembelajaran

| Komponen | Penjelasan |
|---|---|
| Metode | Studio pemrograman, berpasangan, praktikum |
| Penggunaan AI | Dipakai untuk meminta petunjuk sintaks dan untuk membandingkan beberapa alternatif solusi |
| Aktivitas berbasis masalah | Mewujudkan solusi komputasional sederhana sebagai `D3` |
| Pengawasan penggunaan AI | Menjelaskan kode sendiri secara lisan pada GATE 2 wajib; mahasiswa harus dapat menjelaskan setiap baris kode miliknya |

### Aturan Penggunaan AI

Aturan berikut berlaku di semua mata kuliah dalam proyek ini.

1. Setiap dokumen wajib mencantumkan **deklarasi penggunaan AI**.
2. Wajib ada **catatan verifikasi**: apa yang diperiksa manual dan bagaimana caranya.
3. Dilarang menyerahkan hasil AI mentah tanpa analisis dan modifikasi kritis.
4. Penilaian melihat cara berpikir, bukan hanya kualitas dokumen akhir.
5. Pertemuan awal, sesi kritik antar-tim, dan refleksi tidak boleh dilakukan oleh AI.

Ringkasan aturan ini juga tersedia di [Panduan Mahasiswa](../PANDUAN_MAHASISWA.md#62-ai-policy-ringkas).

---

## 7) Jadwal Perencanaan Pembelajaran (16 Minggu)

Proyek berjalan dalam delapan fase. **GATE 1** (Minggu 8) dan **GATE 2** (Minggu 13) adalah momen
persetujuan, bukan fase tersendiri. Tahap Build dan Test berjalan beriringan pada Minggu 11–12.

Rincian jam untuk keempat mata kuliah ada di [Jadwal Semester](../JADWAL_SEMESTER.md).

| Minggu | Fase | Topik dan Aktivitas | Jam | Hasil Proyek |
|---|---|---|---|---|
| 1 | Discover | Pengenalan komputasi; melihat masalah dari sisi komputasi; norma tim | 5 | — |
| 2 | Frame | Tipe data dasar; variasi input dan output | 5 | — |
| 3–4 | Define | Kontrol alur: percabangan dan perulangan; pengenalan struktur solusi | 9 | — |
| 5–7 | Design | Desain input–proses–output, diagram alur, pseudocode; persiapan `D3`; fungsi dan modularisasi | 48 | Desain `D3` |
| 8 | GATE 1 | Review desain `D3`; pertanyaan jawab dan penjelasan kode per individu | 16 | — |
| 9–12 | Build dan Test | Penulisan kode `D3`; pengujian sederhana; perbaikan; penjelasan kode | 63 | `D3` |
| 13 | GATE 2 | Review `D3` final; penjelasan kode per individu | 16 | `D3` final |
| 14–15 | Communicate | Finalisasi `D3`; latihan presentasi | 18 | — |
| 16 | Reflect dan Demo Day | Refleksi teknis; Demo Day (wajib hadir) | 0 | Demo Day |
| **Total** | | | **180** | |

Seluruh 180 jam mata kuliah ini dikhususkan untuk Sub-CPMK S-03.5 dan tersebar dari Minggu 1 sampai 16.

Latihan teknis pada Minggu 1–4 (input–proses–output, konversi tipe data, percabangan, perulangan)
merupakan lapisan pendukung, bukan dokumen yang dinilai. Hasilnya masuk ke berkas program tim dan
menjadi bahan awal `D3`.

---

## 8) Penilaian

Seluruh penilaian dalam proyek ini mengikuti tiga bagian dengan proporsi tetap:

- **50%** dokumen hasil tim
- **30%** penilaian individu di depan dosen (pertanyaan jawab dan penjelasan kode)
- **20%** refleksi dan proses kerja individu

Proporsi tersebut diterapkan pada porsi proyek dalam nilai mata kuliah ini.

### 8.1 Komponen Penilaian

| Kategori | Komponen | Bobot | Instrumen | Catatan |
|---|---|---|---|---|
| Proyek — dokumen tim (50%) | `D3` Tested Solution Prototype | 20% | Rubrik dokumen `D3` | Dinilai sebagai hasil tim |
| Proyek — individu (30%) | Pertanyaan jawab GATE 1 dan penjelasan kode GATE 2 | 12% | Rubrik pertanyaan jawab dan penjelasan kode | Wajib per individu |
| Proyek — individu (20%) | Jurnal belajar, bukti kontribusi dan keputusan | 8% | Rubrik refleksi dan paspor kompetensi | Wajib per individu |
| Di luar proyek | Praktikum, tugas, dan komponen lain | 60% | Diisi dosen pengampu | Di luar proporsi proyek |
| **Total** | | **100%** | | |

### 8.2 Distribusi ke Proyek

| Komponen | Bobot terhadap nilai mata kuliah |
|---|---|
| `D3` + penjelasan kode + GATE 2 | 40% |

### 8.3 Rincian Rubrik

#### S-03.5 — Pemrograman Dasar

| Aspek | Bobot | Unggul (85–100) | Memadai (70–84) | Berkembang (55–69) | Belum (<55) |
|---|---|---|---|---|---|
| Penguasaan tipe data dan kontrol alur | 25% | Tepat memilih dan menerapkan tipe data; kontrol alur benar | Sebagian besar tepat, kesalahan minor | Beberapa kesalahan pemilihan tipe atau kontrol | Tidak memahami tipe data dan kontrol alur |
| Penggunaan fungsi dan modularisasi | 20% | Fungsi terdefinisi baik, modular, dapat dipakai ulang | Fungsi ada, sebagian kurang modular | Fungsi ada tetapi tidak terstruktur | Tidak ada penggunaan fungsi |
| Kualitas kode dan dokumentasi | 20% | Kode bersih, terdokumentasi, mudah dibaca | Kode cukup terstruktur, dokumentasi sebagian | Kode berantakan, dokumentasi minim | Tidak terdokumentasi |
| Pengujian dan pencarian kesalahan | 15% | Pengujian dilakukan sistematis, kesalahan diperbaiki | Pengujian ada, sebagian kesalahan diperbaiki | Pengujian informal | Tidak ada pengujian |
| Penjelasan kode | 20% | Menjelaskan seluruh kode dengan benar dan mandiri | Menjelaskan kode inti | Penjelasan sebagian, atau terbantu AI tanpa dipahami | Tidak mampu menjelaskan |

Bukti: `WS07`, `WS09`–`WS13`, `D3`, penjelasan kode pada GATE 2. Penilai: dosen Dasar Pemrograman
dan peninjau gate. Rincian lengkap di [Assessment Rubrics](../ASSESSMENT_RUBRICS.md).

### 8.4 Perhitungan Skor

Skor akhir Sub-CPMK dihitung dari kombinasi berbobot setiap bukti:

| Sub-CPMK | Sumber Bukti (bobot) |
|---|---|
| S-03.5 | `WS07`, `WS09`–`WS13` (25%) · desain `D2` dan `D3` (35%) · penjelasan kode dan GATE 2 (40%) |

### 8.5 Skala Pencapaian

| Skala | Rentang | Arti |
|---|---|---|
| Unggul | 85–100 | Kemahiran penuh |
| Memadai | 70–84 | Kemahiran memadai |
| Berkembang | 55–69 | Perlu penguatan |
| Belum | <55 | Belum tercapai, ada remedial |

---

## 9) Dokumen Rujukan

| Dokumen | Isi |
|---|---|
| [Panduan Mahasiswa](../PANDUAN_MAHASISWA.md) | Buku petunjuk utama mahasiswa |
| [Panduan Dosen](../PANDUAN_DOSEN.md) | Buku petunjuk operasional dosen dan peninjau gate |
| [Panduan Mentor](../PANDUAN_MENTOR.md) | Buku petunjuk mentor |
| [Worksheet Book](../WORKSHEET_BOOK.md) | `WS01`–`WS16` |
| [Template Pack](../TEMPLATE_PACK.md) | Template dokumen `D1`–`D4` dan lampiran `E1`–`E7` |
| [Assessment Rubrics](../ASSESSMENT_RUBRICS.md) | Rubrik penilaian lengkap |
| [Jadwal Semester](../JADWAL_SEMESTER.md) | Jadwal 16 minggu lengkap lintas mata kuliah |
| [Starter Pack](../../starter-pack/README.md) | Berkas awal untuk mahasiswa |

---

*Rilis 1.0 — dokumen publik. Dokumen ini siap dibaca pihak luar, termasuk mitra usaha yang menjadi
mitra proyek. Rujukan kurikulum internal tidak disertakan; bila diperlukan, hubungi koordinator
program studi.*
