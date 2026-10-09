# PjBL Level 1 -- Digital Problem Framing Mini Project

Buku petunjuk Project-Based Learning (PjBL) untuk mahasiswa Semester 1 Program Studi Sistem Informasi.

## Tentang Proyek

Proyek **Digital Problem Framing Mini Project** adalah kesempatan mahasiswa untuk:

1. Mengunjungi unit usaha nyata (kantin, warung, koperasi) di sekitar kampus
2. Memahami masalah yang mereka hadapi
3. Merancang solusi sederhana berbasis program
4. Membangun prototipe program konsol (CLI)
5. Mempresentasikan hasil ke pemilik usaha
6. Membangun portofolio digital pertama di LinkedIn

## File

| File | Deskripsi |
|---|---|
| [Panduan Mahasiswa](docs/PANDUAN_MAHASISWA.md) | Buku petunjuk utama untuk mahasiswa (revisi 3) |
| [Panduan Dosen](docs/PANDUAN_DOSEN.md) | Buku petunjuk operasional untuk dosen pengampu & reviewer gate |
| [Panduan Mentor](docs/PANDUAN_MENTOR.md) | Buku petunjuk mentor (v2.1): peran sebagai PBL Learning Facilitator, layer fase PBL pada 16 pekan, coaching problem framing, matriks eskalasi, dan preparation checklist |
| [Silabus — Konsep Sistem Informasi](docs/silabus/SILABUS_KONSEP_SI.md) | Silabus MK pemilik `D1` dan `D2` |
| [Silabus — Dasar Pemrograman](docs/silabus/SILABUS_DASAR_PEMROGRAMAN.md) | Silabus MK pemilik `D3` |
| [Silabus — Komunikasi Profesional & Kerja Tim](docs/silabus/SILABUS_KOMUNIKASI_PROFESIONAL.md) | Silabus MK pemilik bersama `D4` |
| [Silabus — Bahasa Inggris](docs/silabus/SILABUS_BAHASA_INGGRIS.md) | Silabus MK pendukung, pemilik bersama `D4` |
| [Worksheet Book](docs/WORKSHEET_BOOK.md) | Kumpulan worksheet WS01-WS16 |
| [Template Pack](docs/TEMPLATE_PACK.md) | Template deliverable TPL-01 s.d. TPL-11 (D1-D4 + supporting evidence) |
| [Assessment Rubrics](docs/ASSESSMENT_RUBRICS.md) | Rubrik penilaian lengkap (skema 50/30/20) |
| [Jadwal Semester](docs/JADWAL_SEMESTER.md) | Jadwal 16 minggu (8 fase, GATE 1, GATE 2, DEMO DAY) |

> Beberapa dokumen di `docs/` masih menyebut dokumen internal yang belum dipublikasikan di repository ini (contoh: `learning_spine`, `instructor_guide`, `project_guide_level_1`, dan dokumen shared). Nama dokumen tersebut ditulis dalam backtick sebagai referensi, bukan tautan. Hubungi koordinator bila diperlukan versi yang dapat dibagikan.

## Starter Pack

Clone starter pack untuk memulai proyek:

```bash
git clone [URL_REPO]
cd [nama-repo]
python src/main.py   # coba jalankan program awal
```

Lihat [starter-pack/README.md](starter-pack/README.md) untuk panduan lengkap.

## Struktur Repository

```
.
 README.md                     File ini
 LICENSE                       MIT License
 .gitignore
 docs/                         Dokumen proyek
      PANDUAN_MAHASISWA.md
      PANDUAN_DOSEN.md
      PANDUAN_MENTOR.md
      WORKSHEET_BOOK.md
      TEMPLATE_PACK.md
      ASSESSMENT_RUBRICS.md
      JADWAL_SEMESTER.md
      silabus/                  Silabus 4 mata kuliah
         SILABUS_KONSEP_SI.md
         SILABUS_DASAR_PEMROGRAMAN.md
         SILABUS_KOMUNIKASI_PROFESIONAL.md
         SILABUS_BAHASA_INGGRIS.md
 starter-pack/                 Template awal untuk mahasiswa
    README.md
    docs/                      D1-D4 + evidence/E1-E7
    src/
    worksheets/
    assets/
 images/                       Gambar pendukung
```

## Untuk Mitra Usaha

Seluruh isi repository ini ditulis agar dapat dibaca pihak luar. Mitra usaha dilibatkan pada tiga titik:

1. **Minggu 2** - tim mahasiswa melakukan observasi dan wawancara, dengan izin lebih dulu.
2. **Minggu 12** - pemilik usaha mencoba prototipe dan memberikan masukan.
3. **Minggu 16** - Demo Day, presentasi tim di depan mitra usaha.

Silabus di `docs/silabus/` menjelaskan apa yang diminta dari tiap mata kuliah, termasuk jam,
bobot penilaian, dan rubrik penilaian.


## Untuk Dosen

1. Baca [Panduan Dosen](docs/PANDUAN_DOSEN.md) - buku petunjuk operasional penuh: fasilitasi, gate, asesmen 50/30/20, dan passport kompetensi.
2. Baca juga [Panduan Mentor](docs/PANDUAN_MENTOR.md) bila Anda bertugas sebagai mentor. Di sanalah fasilitasi 8 fase, checklist mingguan, dan matriks eskalasi dijelaskan.
3. Clone repository ini.
4. Bagikan URL clone ke mahasiswa di Minggu 1.
5. Mahasiswa clone starter pack untuk memulai proyek.

## Untuk Mentor

1. Baca [Panduan Mentor](docs/PANDUAN_MENTOR.md) - peran mentor, fasilitasi 8 fase, 16 pekan, coaching, eskalasi, dan pelaporan.
2. Struktur 16 pekan mengikuti aktivitas Moodle yang sudah ada. Inti panduannya adalah **fase PBL** yang dilalui tim tiap pekan, bukan urutan materi pemrograman.
3. Pertanyaan awal yang dijawab mentor tiap pekan: *Where are we? - What should students have? - What is next?*
4. Skor mentor adalah **input bagi dosen**. Dosen yang menetapkan nilai akhir.

## Lisensi

MIT License - Lihat [LICENSE](LICENSE) untuk detail.

---

**Program Studi Sistem Informasi** | Tahun Akademik 2026/2027
