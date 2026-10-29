Tags: #type/guidebook #domain/pbl #pbl/level-1 #audience/mentor
# Buku Petunjuk Mentor — Project-Based Learning (PjBL) Level 1
Version : v2.1 | Last Updated : 2026-10-01
Related Files:
- [PANDUAN_DOSEN.md](PANDUAN_DOSEN.md)
- [PANDUAN_MAHASISWA.md](PANDUAN_MAHASISWA.md)
- `learning_spine`
- [WORKSHEET_BOOK.md](WORKSHEET_BOOK.md)
- [TEMPLATE_PACK.md](TEMPLATE_PACK.md)
- [ASSESSMENT_RUBRICS.md](ASSESSMENT_RUBRICS.md)
- `individual_competency_passport`
- `course_pbl_level_1_moodle_blueprint`
- `silabus_dasar_pemrograman`
Shared References:
- `ai_policy`
- `assessment_framework`

**Digital Problem Framing Mini Project** | Program Studi Sistem Informasi | Semester 1 (Foundation Entry) | TA 2026/2027

> **Peran mentor**: **PBL Learning Facilitator** yang mendampingi mahasiswa sepanjang PBL Journey — dari Discover sampai Demo Day. Mentor bukan asisten khusus praktikum Dasar Pemrograman; pemrograman hanyalah salah satu area mentoring (terutama fase Design–Build–Test). Mentor memfasilitasi fase, coach proses belajar, menjaga evidence, dan menjadi **early warning system** bagi dosen. Mentor **tidak menetapkan nilai akhir**: skor mentor adalah input penilaian. Rasio: **1 mentor : 2 tim mahasiswa**.

---

## Apa yang Berubah di v2.0

Revisi ini menjawab 19 usulan pada `revision_note_2.md` — hasil pemeriksaan bahwa panduan mentor sebelumnya terlalu terorientasi pada praktikum Dasar Pemrograman dan mengukur keberhasilan dengan "progress", bukan "learning".

Perubahan paling mendasar: **guidebook tetap 16 pekan dan tetap 1:1 dengan aktivitas `| mentor` di Moodle**, tetapi kini setiap pekan dibungkus *layer fase PBL* — fase lebih dulu, baru aktivitas teknis. Teknis tidak dihapus, posisinya turun menjadi **Technical Mentoring Toolkit** (Bagian 4).

| # | Usulan di `revision_note_2.md` | Diterapkan di |
|---|---|---|
| 1 | Definisi mentor → *PBL Learning Facilitator* | Blok peran di atas & 1.1 |
| 2 | Urutan mengikuti PBL Journey, bukan urutan materi pemrograman | Bagian 2 & Bagian 3 |
| 3 | Porsi mentoring fase awal (observasi, wawancara, evidence) | 2.3, Bagian 3 · Pekan 1–4 |
| 4 | Tiga pertanyaan wajib setiap pekan | 2.2 & template di Bagian 3 |
| 5 | Problem Framing Coaching (Evidence → Insight → Problem) | 2.4 & Bagian 3 · Pekan 2–4 |
| 6 | Mentor–Course Integration Map | 1.4 |
| 7 | Technical mentoring dipertahankan, dipindah menjadi *toolkit* | Bagian 4 |
| 8 | Kesiapan & rehearsal GATE 1 (Problem/Design/Individual) | Bagian 3 · Pekan 8 & 5.3 |
| 9 | Testing berorientasi user, bukan sekadar "program tidak error" | Bagian 3 · Pekan 11–12 & 5.2 |
| 10 | Communicate: mentor sebagai *first audience* | Bagian 3 · Pekan 14–15 & 5.2 |
| 11 | Reflect dalam lima dimensi | Bagian 3 · Pekan 16 |
| 12 | Log mentor: Progress **+ Learning + Risk** | 6.1 |
| 13 | Diagram mentor dalam ekosistem PBL | 1.2 |
| 14 | Coaching Question Bank | Bagian 5 |
| 15 | Escalation Protocol | 6.2 |
| 16 | Mentor–Lecturer Weekly Sync (15–20 menit) | 6.3 |
| 17 | *Mentor Must Not* | 1.5 |
| 18 | *Question Before Answer* (Ask → Probe → Hint → Explain) | 1.6 & 5.4 |
| 19 | Mentor Preparation Checklist | 7.1 |

---

## Daftar Isi
1. [Peran Mentor dalam Ekosistem PBL](#bagian-1-peran-mentor-dalam-ekosistem-pbl)
2. [PBL Journey & Posisi Mentor](#bagian-2-pbl-journey--posisi-mentor)
3. [Aktivitas Mentor per Pekan (16)](#bagian-3-aktivitas-mentor-per-pekan-16)
4. [Technical Mentoring Toolkit](#bagian-4-technical-mentoring-toolkit)
5. [Coaching Question Bank](#bagian-5-coaching-question-bank)
6. [Pelaporan, Eskalasi & Koordinasi](#bagian-6-pelaporan-eskalasi--koordinasi)
7. [Persiapan Mingguan & Penutupan](#bagian-7-persiapan-mingguan--penutupan)

---

# Bagian 1: Peran Mentor dalam Ekosistem PBL

## 1.1 Siapa Mentor dalam PBL

Mentor adalah **PBL Learning Facilitator**: fasilitator yang mendampingi mahasiswa memahami dan menjalankan setiap fase proyek, sekaligus membantu dosen memastikan proses pembelajaran berjalan sebagaimana dirancang.

Tiga kata kunci yang membedakan mentor dari teaching assistant:

| Kata kunci | Artinya | Bukan berarti |
|---|---|---|
| **Facilitator** | Memandu percakapan, forum, dan alur kerja yang menghubungkan ide-ide mahasiswa | Memberi kuliah atau materi pengganti |
| **Coach** | Mempercepat kemandirian mahasiswa melalui pertanyaan yang tepat | Mengerjakan atau memperbaiki hasil kerja mahasiswa |
| **Journey guardian** | Menjaga agar tim berada di fase yang benar dan siap berpindah fase | Menentukan nilai atau menggantikan dosen dalam menilai |

Dasar Pemrograman tetap menjadi salah satu area mentoring — terutama pada fase Design, Build, dan Test — tetapi tidak lagi menjadi definisi keseluruhan peran.

## 1.2 Mentor dalam Ekosistem PBL

```
   KOORDINATOR  ──jadwal, mitra, konsistensi lintas MK, arsip nilai──┐
        │                                                        │
        ▼                                                        ▼
     DOSEN  ◄─────── weekly sync (15–20 menit) ───────►  MENTOR
  owner of teaching                                          facilitator
  & assessment                                                & coach
        │                                                        │
        │  Environment: Moodle (Grader), GitHub, dan repo starter │
        ▼                                                        ▼
    MAHASISWA ◄── tim 3–4 orang, rotating phase lead ──►  MENTOR
    owner of learning
    & project
        │
        ▼
  MITRA / REAL-WORLD PARTNER
  pemilik usaha, luar kampus
```

Prinsip pembagian peran:

| Peran | Tanggung jawab utama | Batasnya |
|---|---|---|
| **Koordinator** | Orkestrasi semester: jadwal, gate, mitra, konsistensi lintas MK, arsip nilai | Tidak memberi kuliah atau penilaian |
| **Dosen** | Pemilik pengajaran & penilaian: scaffolding, asesmen Sub-CPMK, sign-off GATE 1/2 | Tidak boleh mendelegasikan penilaian akhir |
| **Mentor** | Fasilitator & coach: proses, evidence, kesiapan fase, deteksi dini risiko | Tidak menetapkan nilai akhir, tidak mengerjakan tugas mahasiswa |
| **Mahasiswa** | Pemilik belajar & proyek: problem framing, solusi, keputusan, refleksi | Bertanggung jawab atas mutu karyanya sendiri |
| **Mitra** | Sumber masalah & pengguna nyata: validasi prototipe, penilaian di Demo Day | Bukan penerima outsourcing sistem |

## 1.3 Tanggung Jawab Mentor

| Area | Tanggungan jawab |
|---|---|
| Orientasi fase | Memastikan tiap tim tahu fase PBL yang sedang dilalui dan bukti yang harus sudah ada (lihat 2.2) |
| Onboarding alat | Pekan 1: akses e-learning, repo GitHub, clone starter pack, menjalankan Python pertama |
| Fasilitasi & coaching | Mendampingi tiap tim, terutama pada fase awal (observasi, wawancara, evidence) dan fase Test |
| Cek pekerjaan | Periksa artefak dan kode, beri umpan balik spesifik yang mengaitkan ke rubrik/Sub-CPMK |
| Kesiapan gate | Membantu mahasiswa siap GATE 1 & GATE 2; menyelenggarakan rehearsal bila diminta dosen |
| Deteksi dini | Mencatat **kesenjangan belajar** dan **risiko** lebih awal — bukan menunggu minggu gate |
| Input penilaian | Menilai aktivitas `\| mentor` dengan rubrik resmi dosen; menyerahkan skor + catatan bukti ke dosen terkait |
| Penjaga integritas | Mendeteksi output AI mentah, free-rider, dan verification note yang janggal; melapor ke dosen |
| Pelaporan | Mengisi log Progress + Learning + Risk (6.1) dan menyampaikan pada weekly sync (6.3) |

## 1.4 Integrasi dengan Empat Mata Kuliah

| Mata Kuliah | Kontribusi ke proyek | Dukungan mentor | Fase terkait |
|---|---|---|---|
| **Konsep Sistem Informasi** | Understand — problem & context framing | Membantu membedakan fakta dari asumsi, evidence dari opini, problem dari symptom | Discover–Frame |
| **Dasar Pemrograman** | Build — technical support, logika, coding | Technical Mentoring Toolkit (Bagian 4), walkthrough, debugging | Design–Build–Test |
| **Komunikasi Profesional & Kerja Tim** | Collaborate — team process, komunikasi, konflik | Fasilitasi rapat & forum, coaching komunikasi, mediasi ringan | Sepanjang journey |
| **Bahasa Inggris** | Communicate — dokumentasi, presentasi, terminologi | Cek keterbacaan dokumen & pitch deck, latihan tanya jawab | Communicate–Reflect |

> Mentor **tidak menggantikan dosen** — tugas mentor adalah membantu mahasiswa mengintegrasikan kontribusi keempat mata kuliah dalam satu proyek.

## 1.5 Mentor Must Not

- Mengerjakan proyek untuk mahasiswa.
- Menulis kode untuk mahasiswa.
- Memilihkan objek studi atau masalah.
- Menentukan solusi yang harus dipakai mahasiswa.
- Memberikan jawaban langsung setiap kali mahasiswa bertanya (lihat 1.6).
- Menggantikan dosen dalam mengajar.
- Menetapkan nilai akhir.
- Mengambil alih konflik tim tanpa eskalasi.
- Menggunakan AI untuk menghasilkan pekerjaan mahasiswa.
- Mempermalukan atau menghina mahasiswa di depan publik.

Prinsip: **Guide, don't solve.**

## 1.6 Cara Membimbing: Ask → Probe → Hint → Explain

Urutan yang dipakai mentor sebelum memberi bantuan apa pun:

1. **Ask** — *"Menurut kalian, apa yang terjadi?"*
2. **Probe** — *"Dari mana kalian tahu begitu? Apa buktinya?"*
3. **Hint** — *"Coba perhatikan jenis datanya."*
4. **Explain** — baru dijelaskan, dan hanya sepanjang yang memang dibutuhkan.

Satu pertanyaan menghasilkan satu petunjuk — bukan satu solusi. Arahkan umpan balik ke **aspek rubrik** (tipe data, kontrol alur, fungsi, kualitas kode, pengujian, penjelasan walkthrough) atau **Sub-CPMK**, bukan ke opini rasa.

---

# Bagian 2: PBL Journey & Posisi Mentor

## 2.1 Delapan Fase, Pekanan, dan Checkpoint

```
DISCOVER → FRAME → DEFINE → DESIGN → [GATE 1] → BUILD → TEST → [GATE 2] → COMMUNICATE → REFLECT → [DEMO DAY]
```

| Fase | Pekan | Inti fase | Bukti yang harus sudah ada | Checkpoint |
|---|---|---|---|---|
| **Discover** | 1 | Arah, tim, alat | WS01 (norma + rotasi phase lead), WS02 (need-to-know) | — |
| **Frame** | 2 | Melihat & bertanya di lapangan | WS03 (observasi + rencana wawancara), WS04 (masalah + scope) | — |
| **Define** | 3–4 | Kebutuhan awal yang bisa diuji | WS05 (user story + acceptance criteria), WS06 (metrik + komponen) | — |
| **Design** | 5–7 | Solusi dalam bentuk yang bisa dibangun | WS07, WS08, WS07-final | — |
| **GATE 1** | 8 | Sign-off D1 + D2 | D1, D2 final + oral defense per individu | **GATE 1** |
| **Build** | 9–12 | Prototipe yang berjalan | WS09, CKPT-DP, WS10, WS11 | — |
| **Test** | 11–12 | Bukti bahwa solusi bekerja | WS12 (validasi pengguna) | — |
| **GATE 2** | 13 | Verifikasi D3 | D3 final + code walkthrough per individu + draf D4 | **GATE 2** |
| **Communicate** | 14–15 | Menyampaikan ke audiens | WS14, Final-DP, DemoPrep-DP | — |
| **Reflect** | 13–16 | Makna dari seluruh proses | WS15, WS16, D4 + evidence + passport | **DEMO DAY (P16)** |

Referensi lengkap: `learning_spine.md` dan `jadwal_semester_pbl_level_1.md`.

## 2.2 Tiga Pertanyaan Wajib Setiap Pekan

Sebelum masuk sesi mentoring, mentor menjawab tiga pertanyaan ini — untuk tim yang dibimbing maupun untuk diri sendiri:

| Pertanyaan | Isi yang harus dijawab |
|---|---|
| **Where are we?** | Fase PBL apa yang sedang dilalui tim sekarang? |
| **What should students have?** | Evidence / learning outcome apa yang seharusnya sudah ada di akhir pekan ini? |
| **What is next?** | Apa langkah berikutnya, dan apa yang akan dicari berikutnya? |

Tiga pertanyaan ini dipakai sebagai alat diagnosis. Jika **What should students have?** tidak terpenuhi pada akhir pekan, yang dicatat bukan "tidak selesai" melainkan **hambatan + kesenjangan belajar** (lihat 6.1).

Contoh diagnosis:

| Gejala tim | Temuan learning | Apa yang dicatat |
|---|---|---|
| Datang ke Pekan 1 tanpa WS02 | Belum paham cara memetakan apa yang perlu diketahui | Kesenjangan: need-to-know; intervensi: coaching di sync berikutnya |
| Datang ke Pekan 10 tanpa WS09 | Tidak terbiasa memecah pekerjaan menjadi fitur terukur | Kesenjangan: dekomposisi; intervensi: memecah tugas menjadi langkah kecil |
| Uji coba selalu "berhasil" tapi tidak ada kasus gagal | Belum memahami pengujian sebagai proses mencari kesalahan | Kesenjangan: mindset pengujian; coaching: kasus batas |

## 2.3 Fase Awal: Observe → Ask → Record → Interpret → Frame

Mahasiswa semester 1 membutuhkan scaffolding terbesar justru **sebelum** menyentuh kode: cara melihat masalah, bukan diberi masalah. Lima langkah yang difasilitasi mentor pada Pekan 1–4:

| Langkah | Yang dilakukan mahasiswa | Peran mentor |
|---|---|---|
| **Observe** | Mengamati proses kerja nyata tanpa langsung menawarkan solusi | Memastikan lembar observasi terisi; menuntun tim menuliskan apa yang terlihat, bukan apa yang diasumsikan |
| **Ask** | Menyusun ≤10 pertanyaan singkat dan meminta izin sebelum wawancara | Melatih probing: pertanyaan terbuka → pertanyaan pemantik masalah |
| **Record** | Mencatat evidence termasuk angka sederhana | Memeriksa sumber data; menandai data yang belum terverifikasi |
| **Interpret** | Menemukan insight dari evidence | Menguji asumsi: mana fakta, mana opinion? |
| **Frame** | Memilih satu masalah dan menuliskan scope / non-scope | Bertanya, bukan memilihkan |

> Ekspektasi yang harus ditegaskan: **hasil Discover–Frame tidak selalu tentang solusi yang tepat, tetapi tentang kejelasan cara melihat masalah.** Tim yang belum berhasil merumuskan masalah,
> tetapi belajarnya evident, tetap layak dilanjutkan dengan dukungan.

## 2.4 Problem Framing Coaching: Evidence → Insight → Problem

Pertanyaan mentor untuk membimbing mahasiswa bergerak dari bukti ke masalah:

- Apa yang benar-benar kalian lihat di lapangan?
- Apa yang kalian dengar langsung dari user, bukan dari dugaan?
- Mana yang fakta, mana yang asumsi?
- Apa evidence yang mendukung klaim kalian?
- Apakah ini problem atau symptom? Kalau symptom, apa penyebabnya?
- Siapa yang mengalami masalah ini, seberapa sering?
- Mengapa masalah ini penting bagi mereka?
- Apa yang masih belum kalian ketahui?

Batas peran mentor: mentor membantu **kualitas pertanyaan dan kejelasan evidence**, bukan menentukan mana masalah yang benar. Penentuan masalah tetap milik tim; validasi akademiknya milik dosen Konsep Sistem Informasi.

---

# Bagian 3: Aktivitas Mentor per Pekan (16)

Struktur 16 pekan dipertahankan agar **tetap 1:1 dengan aktivitas `| mentor` di Moodle Course PBL Level 1** (kode aktivitas & rubrik tidak berubah). Yang berubah adalah cara membacanya: **fase lebih dulu, lalu aktivitas teknis sebagai lapisan pendukung.**

Peta aktivitas mentor (16 pekan): **Pekan 1–4 = support** (WS01–WS06 + draf D1/D2), **Pekan 5–16 = 13 kegiatan yang dinilai** dengan rubrik resmi.

| Pekan | Artefak | Rubrik |
|---|---|---|
| 1 | `WS01`, `WS02` | Support mentor — S-14.1, S-01.1 (dosen MK pemilik) |
| 2 | `WS03`, `WS04`, `D1` draf | Support mentor — S-04.1, S-01.1 (dosen Konsep SI) |
| 3 | `WS05`, `D1`/`D2` draf | Support mentor — S-01.1, S-02.1 (dosen Konsep SI) |
| 4 | `WS06`, `D1`/`D2` draf | Support mentor — S-02.1 (dosen Konsep SI) |
| 5 | `WS07-DP` | Rubrik Desain Solusi Sederhana (S-03.1) |
| 6 | `WPseud` | Rubrik Desain Solusi Sederhana (S-03.1) |
| 7 | `WS07-final` | Rubrik Desain Solusi Sederhana (S-03.1) |
| 8 | `Gate1-DP` | Rubrik Oral/Code Defense — GATE 1 (S-03.1, S-03.5) |
| 9 | `WS09` | Rubrik Rencana Pengembangan Prototipe (S-03.5) |
| 10 | `CKPT-DP` | Rubrik Praktikum Pemrograman Dasar (S-03.5) |
| 11 | `WS10` | Rubrik Code Walkthrough & Pengujian (S-03.1) |
| 11 | `WS11` | Rubrik Praktikum Pemrograman Dasar (S-03.5) |
| 12 | `WS12` | Rubrik Code Walkthrough & Pengujian (S-03.1) |
| 13 | `Gate2-DP` | Rubrik D3 — Tested Solution Prototype (S-03.5) |
| 14 | `Final-DP` | Rubrik D3 — Tested Solution Prototype (S-03.5) |
| 15 | `DemoPrep-DP` | Rubrik Demo Day / Presentasi / Oral Defense (S-03.5) |
| 16 | `Postmortem-DP` | Rubrik Learning Journal / Refleksi Akhir (S-03.5) |

Aktivitas yang **bukan** dinilai mentor tetapi tetap perlu dipantau: `WS07`, `WS08`, `WS14`–`WS16` (Komunikasi Profesional), forum mingguan, serta review `Check-13` (Konsep SI). Untuk aktivitas ini mentor bersifat **support/coaching**, bukan grader.

> **Catatan kode artefak.** Artefak yang diakui di dokumentasi rilis ini hanya `WS01`–`WS16` (worksheet), `D1`–`D4` (core artifact), `E1`–`E7` (evidence/lampiran D4), dan `TPL-01`–`TPL-11` (instrumen). Latihan teknis pada Pekan 1–4 (input–proses–output, konversi tipe data, percabangan, perulangan) **bukan artefak terpisah** dan tidak berkode — hasilnya masuk ke `src/main.py` dan menjadi bahan awal `D3`.

---

## Pekan 1 — Discover: Menetapkan Arah, Tim, dan Alat Kerja

- **Where are we?** Fase Discover, pekan 1. Tim belum punya arah masalah dan belum punya alat kerja.
- **What should students have?** WS02 (≥6 pertanyaan need-to-know beserta sumber), WS01 (tim 3–4 orang, objek studi dari daftar aman, jadwal rotating phase lead, ≥5 norma), forum perkenalan, repo tim ter-clone dengan commit pertama, latihan teknis pertama (input–proses–output) berhasil dijalankan.
- **What is next?** Menyusun rencana pengetahuan yang akan dicari di lapangan pada Pekan 2.

**Aktivitas mentor**: support pada `WS01` & `WS02` — bukan grading. Latihan teknis pertama adalah lapisan pendukung tanpa kode artefak; inti pekan adalah Discover.

**SOP — A. Akses E-Learning**
1. Pastikan mahasiswa login Moodle dan masuk course **PBL Level 1**.
2. Unduh **PANDUAN_MAHASISWA** & **starter pack** dari resource course.
3. Cek akses forum umum + tempat submisi tugas latihan teknis.

**SOP — B. GitHub**
4. Buat akun GitHub (username profesional, mis. `nama_nim`) atau klaim undangan repositori tim.
5. Instal Git; set identitas: `git config --global user.name "Nama"` · `git config --global user.email "email@kampus"`.
6. `git clone <url>` repositori starter (per tim); periksa struktur folder (lihat 4.3).
7. Dorong **commit pertama** tim: modifikasi kecil → add → commit → push.
8. Validasi: repo tim tampil di GitHub dan berisi `src/main.py` yang sudah ter-push.

**SOP — C. Python & Latihan Pertama**
9. Instal Python 3.10+ (centang *Add to PATH*); verifikasi `python --version`.
10. `python src/main.py` → harus muncul menu aplikasi CSV sederhana.
11. Buat program latihan teknis pertama (sapa → baca → tampilkan ulang nama; beri komentar bagian *input / proses / output*) di `src/main.py`.
12. Jalankan, ambil **screenshot**, unggah ke Moodle.

**Checklist mentor** (per mahasiswa): login e-learning ✓ · clone repo ✓ · commit pertama ter-push ✓ · `python src/main.py` jalan ✓ · latihan teknis terunggah ✓ · `WS01` & `WS02` lengkap ✓.

- **Coaching**: *"Bagian mana yang disebut input, proses, output?"* · *"Apa isi `data_penjualan.csv` setelah program dijalankan?"* · *"Soal need-to-know kalian, dari mana sumbernya?"*
- **Eskalasi**: kendala instalasi/PATH/akun → catat di log mentor (6.1) & laporkan ke dosen sebelum pekan berikutnya.

## Pekan 2 — Frame: Melihat dan Bertanya di Lapangan

- **Where are we?** Fase Frame (Observe → Ask → Record → Interpret → Frame). Tim turun ke lapangan untuk pertama kali.
- **What should students have?** WS03 (≤10 pertanyaan + lembar observasi), WS04 (3 calon masalah → 1 masalah utama + insight + scope/non-scope), forum simulasi wawancara etis, latihan teknis tipe data & konversi terunggah.
- **What is next?** Mengubah insight menjadi kebutuhan awal yang bisa diuji (Pekan 3).

**Aktivitas mentor**: support pada `WS03` & `WS04` (dosen Konsep SI). Latihan teknis diintegrasikan tanpa kode artefak.

- **Sebelum**: pastikan setiap tim sudah meminta izin kepada pemilik usaha; bekali lembar observasi & daftar pertanyaan.
- **Selama**: dampingi penyusunan pertanyaan — hindari pertanyaan yang mengarahkan jawaban (*leading*) atau menjanjikan solusi. Tekankan *type mismatch* pada latihan konversi; minta mahasiswa menjelaskan output sebelum mengeksekusi.
- **Setelah**: periksa evidence sudah tercatat lengkap (termasuk angka sederhana); beri umpan balik singkat pada WS03/WS04 dan hasil latihan teknis + screenshot.
- **Coaching**: *"Mana yang kalian lihat sendiri, mana yang kalian dengar?"* · *"Mana fakta, mana asumsi?"* · *"Apakah ini masalah inti, atau gejalanya?"* · *"input() selalu mengembalikan string — apa akibatnya kalau tidak di-casting?"*
- **Batas**: mentor **tidak memilihkan** masalah tim. Bila objek studi terasa tidak aman atau tidak etis, eskalasi ke dosen (6.2).
- **Eskalasi**: pemilik usaha keberatan / menolak → hentikan aktivitas, laporkan ke dosen sebelum pekan berikutnya.

## Pekan 3 — Define: Kebutuhan Awal & Kriteria Penerimaan

- **Where are we?** Fase Define, pekan 3. Tim menerjemahkan masalah menjadi kebutuhan yang bisa diuji.
- **What should students have?** WS05 (user story + acceptance criteria), forum rapat status, latihan teknis percabangan.
- **What is next?** Success metrics dan peta komponen SI (Pekan 4).

**Aktivitas mentor**: support pada `WS05` (dosen Konsep SI); latihan teknis dipandu lewat sesi coaching.

- **Sebelum**: siapkan 2–3 soal keputusan sederhana yang nyambung dengan masalah tim (mis. validasi stok, cek harga).
- **Selama**: minta mahasiswa menulis *flowchart mini* dulu sebelum kode; tekankan indentasi & kondisi majemuk (`and`/`or`). Tanyakan: *"Dari acceptance criterion kalian, input apa yang harus mengaktifkannya?"*
- **Setelah**: nilai logika percabangan (bukan sekadar jalan); uji dengan input di luar contoh (edge case).
- **Coaching**: *"Siapa user utama masalah ini?"* · *"Apa yang sebenarnya mereka butuhkan, bukan yang kalian ingin buat?"* · *"Kalau harga 0, masuk cabang mana? Kenapa?"* · *"Apakah acceptance criterion ini bisa diuji, atau hanya terlihat?"*
- **Eskalasi**: kebutuhan yang keluar dari batasan teknis proyek → catat, laporkan di sync (6.3) untuk ditangani dosen saat validasi.

## Pekan 4 — Define: Metrik Keberhasilan & Peta Komponen

- **Where are we?** Fase Define, pekan 4. Tim mengukur "berhasil" dan memetakan komponen sistem.
- **What should students have?** WS06 (success metric + peta komponen SI), forum refleksi kolaborasi, latihan teknis perulangan.
- **What is next?** Desain solusi (Pekan 5).

**Aktivitas mentor**: support pada `WS06` (dosen Konsep SI); latihan teknis dipandu lewat sesi coaching.

- **Sebelum**: siapkan contoh perulangan menu utama (pola `while True` + menu) yang dipakai starter pack.
- **Selama**: tekankan perbedaan FOR (jumlah iterasi jelas) vs WHILE (berhenti berdasarkan kondisi); awas **infinite loop** (selalu sediakan cara keluar/`break`).
- **Setelah**: cek apakah program bisa mengulang menu & keluar dengan benar; **tandai mahasiswa yang belum paham kondisi berhenti** untuk prioritas bimbingan Pekan 5.
- **Coaching**: *"Sukses itu angka apa, bagi siapa?"* · *"Metrik ini diukur kapan, dan dari data mana?"* · *"Komponen mana yang paling berisiko jadi masalah?"*
- **Eskalasi**: metrik yang tidak bisa diukur dengan data yang akan dikumpulkan tim → laporkan ke dosen.

## Pekan 5 — Design: Alur Solusi dari D1/D2 ke Bentuk yang Bisa Dibangun

- **Where are we?** Fase Design. Tim mengubah kebutuhan menjadi alur yang bisa dibangun — ini membentuk proses berpikir desain, bukan menulis kode.
- **What should students have?** WS07 (IPO + flowchart + pseudocode, versi awal), forum persiapan protokol kritik, WS07-DP.
- **What is next?** Kritik sejawat (Pekan 6) untuk menguji desain.

**Aktivitas mentor**: `WS07-DP` — Rubrik Desain Solusi Sederhana (S-03.1).

- **Sebelum**: ingatkan membawa *outline* D1 (masalah + pemilik usaha) dan flowchart WS07.
- **Selama**: tuntun pemecahan alur menjadi **fungsi-fungsi kecil** (satu fungsi satu tanggung jawab, meniru pola `tampilkan_menu()`, `baca_data()`, `simpan_data()` pada starter). Cek konsistensi pseudocode ↔ flowchart.
- **Setelah**: nilai struktur dekomposisi & kejelasan pseudocode; verifikasi mahasiswa bisa **menjelaskan** ulang alurnya (bekal GATE 1). Mulai **Daftar Konsolidasi** (log mentor): nama mahasiswa yang lemah menjelaskan → prioritas bimbingan.
- **Coaching**: *"Requirement mana yang melahirkan fitur ini?"* · *"Kalau input ini masuk, apa yang harus terjadi sebelum keluar?"* · *"Fungsi ini satu tanggung jawab, atau masih terlalu umum?"*
- **Eskalasi**: desain yang tidak mungkin dibangun dengan batasan teknis → eskalasi ke dosen sebelum defend GATE 1.

## Pekan 6 — Design: Sesi Kritik Sejawat I

- **Where are we?** Fase Design, pekan 6. Tim menguji desain dengan mata orang lain.
- **What should students have?** WPseud (revisi pseudocode berdasarkan kritik), forum refleksi kritik.
- **What is next?** Finalisasi desain & penutupan kritik I (Pekan 7).

**Aktivitas mentor**: `WPseud` — Rubrik Desain Solusi Sederhana (S-03.1).

- **Sebelum**: siapkan daftar masukan umum kelas (fungsi terlalu besar, nama fungsi tidak deskriptif, asumsi tanpa bukti).
- **Selama**: dampingi revisi per tim; pastikan umpan balik Pekan 5 benar-benar dimasukkan, bukan sekadar menyalin ulang.
- **Setelah**: bandingkan versi 1 vs revisi; **nilai proses revisi, bukan hasil semata**; catat tim yang revisinya kosmetik.
- **Coaching**: *"Siapa yang memberi kritik, dan bagian mana yang paling sulit dipahami?"* · *"Apa yang kalian tidak setuju dengan kritik itu, dan kenapa?"*
- **Eskalasi**: tim yang menolak kritik secara terus-menerus → catat; bila berlanjut, eskalasi ke dosen saat sync.

## Pekan 7 — Design: Finalisasi Desain & Kritik I (Penutupan)

- **Where are we?** Fase Design, pekan 7 — pekan terakhir sebelum GATE 1.
- **What should students have?** WS08 (kritik antartim & revisi desain), WS07-final (desain final lengkap & konsisten dengan D2).
- **What is next?** GATE 1 (Pekan 8): sign-off D1 & D2, oral defense per individu.

**Aktivitas mentor**: `WS07-final` — Rubrik Desain Solusi Sederhana (S-03.1).

- **Sebelum**: cross-check dengan dosen Konsep Sistem Informasi mengenai keselarasan D2 (komponen SI) → poin yang sama di WS07-final.
- **Selama**: lakukan *desk check* — jalankan mental pseudocode dengan satu skenario; cari celah logika.
- **Setelah**: nilai desain final; tandai **siap GATE 1** vs **remedial**; kirim rekap ke dosen sebelum Pekan 8.
- **Coaching (rehearsal GATE 1)**: mulai dengan pertanyaan: *"Jelaskan masalah ini ke teman yang belum pernah dengar — pakai kalimatmu sendiri."*
- **Eskalasi**: desain belum konsisten dengan D2 atau metric → eskalasi ke dosen **sebelum** GATE 1, jangan menunggu hari-H.

## Pekan 8 — GATE 1: Sign-Off D1 & D2 + Oral Defense

- **Where are we?** GATE 1. Tim harus bisa menjelaskan masalah, desain, dan kontribusinya sendiri.
- **What should students have?** D1 Problem Brief final (TPL-01), D2 System & Solution Design final (TPL-02), `Gate1-DP` (oral defense per individu), forum observasi presentasi GATE 1.
- **What is next?** Perencanaan dan pengkodean prototipe (Pekan 9).

**Aktivitas mentor**: `Gate1-DP` — Rubrik Oral/Code Defense — GATE 1 (S-03.1, S-03.5).

Kesiapan GATE 1 di tiga blok — mentor memastikan mahasiswa siap menjawab:

| Blok | Pertanyaan yang harus bisa dijawab |
|---|---|
| **Problem** | Apa masalahnya? · Apa evidence-nya? · Siapa user-nya? · Kenapa ini penting? |
| **Design** | Apa requirement-nya? · Mengapa solusi ini dipilih? · Bagaimana solusi menjawab requirement? |
| **Individual** | Apa kontribusi saya? · Apa yang saya pahami? · Apa yang belum saya pahami? |

- **Sebelum**: *(rehearsal)* Bila diminta dosen, sediakan sesi rehearsal GATE 1 — simulasi pertanyaan dosen tanpa nilai. Koordinasikan jadwal dengan forum Observasi Presentasi GATE 1 (Komunikasi Profesional) agar tidak bentrok.
- **Selama**: tiap mahasiswa menjelaskan flowchart & pseudocode (percabangan, perulangan, keputusan stok) + verifikasi manual. Mentor **mengamati, menandai bukti penjelasan**, dan mencatat siapa yang tidak mampu menjelaskan (gagal checkpoint individu → remedial).
- **Setelah**: serahkan lembar observasi ke dosen. **Jangan beri nilai akhir** — beri rekomendasi.
- **Coaching**: *"Mana yang paling sulit kalian jelaskan?"* · *"Kalau user bertanya 'kenapa bukan cara lain?', apa jawabannya?"*
- **Eskalasi**: mahasiswa tidak mampu menjelaskan → langsung laporkan ke dosen; jangan menunggu gate berikutnya.

## Pekan 9 — Build: Rencana Build yang Terukur

- **Where are we?** Fase Build, pekan 9. Desain harus diterjemahkan menjadi pekerjaan nyata.
- **What should students have?** WS09 (3–5 fitur, PIC tiap fitur, cara uji, target selesai), forum check-in dinamika tim.
- **What is next?** Pengkodean & uji fitur 1–2 (Pekan 10).

**Aktivitas mentor**: `WS09` — Rubrik Rencana Pengembangan Prototipe (S-03.5).

- **Sebelum**: siapkan template pemecahan D3 → fitur + pemilik + cara uji + target.
- **Selama**: pastikan tiap fitur punya **PIC** dan cara uji sederhana; tekankan bahwa sprint log (WS11) akan jadi bukti kontribusi individu (anti-free-rider).
- **Setelah**: nilai kelayakan rencana (fitur terukur, tidak muluk). Catat pembagian beban antar anggota → awasi di Pekan 10–11.
- **Coaching**: *"Fitur mana yang harus selesai pertama, dan kenapa?"* · *"Bagaimana kalian tahu fitur ini selesai?"* · *"Kalau ada anggota yang belum bisa menjelaskan bagiannya, apa langkah yang akan kalian ambil?"*
- **Eskalasi**: rencana tidak terukur atau beban menumpuk pada 1–2 anggota → laporkan di sync; bila berulang → eskalasi ke koordinator (6.2).

## Pekan 10 — Build: Fitur 1–2 Selesai & Teruji

- **Where are we?** Fase Build, pekan 10 — kode pertama yang berjalan.
- **What should students have?** CKPT-DP (fitur 1–2 + log uji: kasus, input, output diharapkan, output aktual, status, perbaikan), walkthrough singkat per tim.
- **What is next?** Walkthrough menyeluruh & critique II (Pekan 11).

**Aktivitas mentor**: `CKPT-DP` — Rubrik Praktikum Pemrograman Dasar (S-03.5).

- **Sebelum**: cek log uji awal sudah ada (kasus, input, output diharapkan, output aktual, status).
- **Selama**: walkthrough singkat per tim — jalankan kode, tanya per wilayah logika. Verifikasi tiap anggota memahami bagian kode yang diklaimnya.
- **Setelah**: nilai fitur + kualitas log uji. Anggota yang tidak bisa menjelaskan bagiannya sendiri → catat untuk intervensi.
- **Coaching**: *"Apakah kode ini benar-benar merealisasikan desain WS07?"* · *"Kasus uji apa yang bisa membuat program ini salah?"* · *"Menurut kalian, bagian paling rawan di kode ini di mana?"*
- **Eskalasi**: gejala free-rider mulai terlihat → catat di log dengan bukti (sprint log, walkthrough); eskalasi bila berulang.

## Pekan 11 — Build/Test: Walkthrough, Sprint Log & Critique II

- **Where are we?** Fase Build/Test, pekan 11 — verifikasi bahwa yang dibangun memang milik tim.
- **What should students have?** WS10 (catatan walkthrough & pengujian berkelanjutan), WS11 (sprint log update ≥1×/minggu: fitur, PIC, status, hambatan, solusi), forum bantuan debugging.
- **What is next?** Validasi pengguna nyata (Pekan 12).

**Aktivitas mentor**: `WS10` — Rubrik Code Walkthrough & Pengujian (S-03.1) · `WS11` — Rubrik Praktikum Pemrograman Dasar (S-03.5).

- **Selama**: walkthrough seluruh fitur — mahasiswa menjelaskan alur, variabel, keputusan, termasuk **bagian yang dibantu AI + verifikasi manual** (patuhi `ai_policy`). Bantu memperbaiki bug yang ketemu; hasil final disiapkan untuk GATE 2 (Pekan 13).
- **WS11**: pastikan sprint log diperbarui minimal mingguan; ini bahan verifikasi kontribusi individu di D4.
- **Forum**: mentor memantau Forum Bantuan Debugging — bantu tim lain saling membalas dengan saran yang spesifik.
- **Setelah**: skor WS10 + WS11; skor sprint log menjadi bahan verifikasi kontribusi individu di D4.
- **Coaching**: *"Bagaimana kalian membuktikan solusi ini bekerja?"* · *"Dari kode ini, bagian mana yang paling sulit, dan mengapa?"* · *"Bagian mana yang dibantu AI, dan bagaimana cara memverifikasinya?"*
- **Eskalasi**: indikasi kode dikerjakan AI penuh → mintakan penjelasan lisan; bila tidak bisa menjelaskan, laporkan ke dosen.

## Pekan 12 — Test: Validasi Pengguna & Uji Penerimaan

- **Where are we?** Fase Test. Sekarang ukurannya bukan "program tidak error", melainkan **apakah user bisa memakainya dan mendapatkan manfaat**.
- **What should students have?** WS12 (skenario validasi 3–5 langkah + catatan masukan pengguna + rencana perbaikan), forum refleksi implementasi, draf awal D4.

**Aktivitas mentor**: `WS12` — Rubrik Code Walkthrough & Pengujian (S-03.1).

Rantai yang harus dijaga mentor agar testing benar-benar berorientasi user:

```
Acceptance Criteria → Test Case → Expected Result → Actual Result → User Feedback → Improvement
```

| Pertanyaan mentor | Fokus |
|---|---|
| Apakah requirement terpenuhi? | Kesesuaian dengan kriteria penerimaan WS05 |
| Apakah user dapat menggunakannya? | Kemudahan pakai yang nyata, bukan sekadar dokumentasi |
| Apa yang terjadi ketika user mencoba? | Perilaku tak terduga, kebingungan, salah input |
| Apa yang harus diperbaiki? | Perbaikan yang berprioritas, tercatat di decision log (E4) |

- **Sebelum**: siapkan panduan sesi (skenario 3–5 langkah) & log catatan observasi pemilik usaha.
- **Selama**: dampingi tim memandu pemilik mencoba prototipe — **minta bertindak sebagai pengguna, jangan menyoroti bug**; catat masukan terhadap kriteria penerimaan WS05.
- **Setelah**: pastikan masukan terdokumentasi di Decision Log (E4) & rencana perbaikan tertera. Nil kualitas pelaksanaan validasi + dokumentasinya.
- **Coaching**: *"Apa yang paling membingungkan dari sudut pandang pengguna?"* · *"Kalau user tidak membaca README-nya, program ini masih bisa dipakai?"* · *"Masukan mana yang akan ditolak, dan mana yang masuk scope?"*
- **Eskalasi**: pengguna tidak dapat diakses, atau validasi diminimalkan → laporkan ke dosen; jangan mengganti dengan uji antar mahasiswa tanpa catatan alasan.

## Pekan 13 — GATE 2: Verifikasi D3, Evidence & Draf D4

- **Where are we?** GATE 2. Tim harus dapat membuktikan kecakapan teknisnya dan menunjukkan produk yang sudah diuji.
- **What should students have?** `Gate2-DP` (D3 final + code walkthrough per individu), WS15 (decision log, AI disclosure, refleksi individu — review GATE 2), draf evidence E1–E7, review `Check-13` (Konsep SI) berjalan berdampingan.
- **What is next?** Penyusunan executive summary & persiapan demo (Pekan 14).

**Aktivitas mentor**: `Gate2-DP` — Rubrik D3 — Tested Solution Prototype (S-03.5).

- **Sebelum**: bantu dosen menyusun jadwal walkthrough per individu; siapkan lembar verifikasi (kode, log uji, dokumentasi, kesesuaian dengan D2).
- **Selama**: tiap mahasiswa menjelaskan tipe data, kontrol alur, fungsi/modularisasi, dan tes yang dijalankan. **Verifikasi tiap klaim evidence terhadap artefak yang benar-benar ada.** Catat bukti kemampuan menjelaskan per individu.
- **Setelah**: **TIDAK LULUS jika dokumentasi tidak valid atau mahasiswa gagal menjelaskan kode** — sampaikan rekomendasi lulus/perbaikan ke dosen. Kesamaan GATE 1: mentor tidak menetapkan nilai akhir.
- **Sinkron**: koordinasikan dengan reviewer `KP-GATE2` & `Check-13` (Konsep SI) agar pemeriksaan berdampingan.
- **Coaching**: *"Jelaskan kode ini baris demi baris — termasuk yang dibantu AI."* · *"Kalau saya mengubah urutan input, apa yang terjadi?"*
- **Eskalasi**: ketidaksesuaian D3 ↔ D2 yang tidak bisa dijelaskan → eskalasi ke dosen **sebelum** gate ditutup.

## Pekan 14 — Communicate: Executive Summary & Persiapan Demo

- **Where are we?** Fase Communicate. Tim harus mengubah hasil teknis menjadi cerita yang dipahami orang luar.
- **What should students have?** WS14 (draf executive summary + naskah demo), forum rancangan pesan untuk audiens non-teknis, Final-DP (finalisasi D3 & penyiapan demo).
- **What is next?** Rehearsal & finalisasi pitch (Pekan 15).

**Aktivitas mentor**: `Final-DP` — Rubrik D3 — Tested Solution Prototype (S-03.5).

> **Mentor adalah audiens pertama sebelum audiens kedua.** Dengarkan penjelasan mereka **sampai selesai tanpa menyela**, baru ajukan pertanyaan. Kesan pertama audiens tidak teknis sering menentukan apakah pesan masuk atau tidak.

Enam pertanyaan mentor saat menjadi audiens pertama:

1. Apa masalah yang kalian selesaikan?
2. Apa buktinya?
3. Mengapa solusi ini dipilih?
4. Apa dampaknya?
5. Apa keterbatasannya?
6. Apa yang kalian pelajari?

- **Selama**: pandu perapian akhir — dokumentasi `README`, komentar kode, pembersihan kode mati, uji lintas platform sederhana. Siapkan skenario demo fitur; koordinasikan dengan tim Bahasa Inggris (pitch deck).
- **Setelah**: nilai kualitas final — kebersihan kode, dokumentasi, reproduktibilitas (`python src/main.py` dari repo bersih). Beri catatan untuk skenario demo.
- **Coaching**: *"Kalau saya pemilik usaha, bagian mana yang harus saya dengar lebih dulu?"* · *"Bisakah orang luar memahami proyek kalian?"*
- **Eskalasi**: dokumentasi teknis tidak valid saat finalisasi → laporkan ke dosen; jangan menggagalkan di hari-H.

## Pekan 15 — Communicate: Rehearsal & Finalisasi Pitch

- **Where are we?** Fase Communicate, pekan 15 — latihan terakhir sebelum tampil.
- **What should students have?** DemoPrep-DP (skenario demo D3 + sesi tanya jawab latihan), seluruh anggota bisa mendemokan fitur.
- **What is next?** DEMO DAY (Pekan 16).

**Aktivitas mentor**: `DemoPrep-DP` — Rubrik Demo Day / Presentasi / Oral Defense (S-03.5).

- **Selama**: uji tiap skenario (langkah, input, output diharapkan). Adakan **tanya jawab teknis latihan** dengan pertanyaan menyerupai pertanyaan mitra usaha; pastikan **semua anggota** bisa mendemokan & menjelaskan fitur (bukan hanya sang pembuat kode).
- **Setelah**: nilai kelengkapan skenario & kesiapan seluruh anggota; laporkan anggota yang belum siap → dampingi rehearsal ulang sebelum Demo Day.
- **Coaching**: *"Pertanyaan paling sulit apa yang bisa muncul dari mitra?"* · *"Kalau demo gagal di tengah, apa rencana cadangan kalian?"*
- **Eskalasi**: anggota yang sama belum siap setelah dua kali latihan → eskalasi ke dosen untuk keputusan soal pembagian peran presentasi.

## Pekan 16 — Reflect + DEMO DAY: Refleksi Akhir & Penutupan

- **Where are we?** Reflect + DEMO DAY — menguji makna dari seluruh proses, bukan hanya produk.
- **What should students have?** Postmortem-DP, WS16 (refleksi akhir & postmortem tim), D4 final + evidence E1–E7 + Individual Competency Passport (E7), presentasi di depan audiens publik.
- **What is next?** Penutupan: serahkan Daftar Konsolidasi ke dosen; passport menjadi rekam jejak kompetensi untuk semester berikutnya.

**Aktivitas mentor**: `Postmortem-DP` — Rubrik Learning Journal / Refleksi Akhir (S-03.5).

Refleksi dipandu dalam lima dimensi — **bukan hanya kemampuan teknis**:

| Dimensi | Pertanyaan pemandu |
|---|---|
| **Problem** | Apa yang ternyata salah dari pemahaman awal kalian tentang masalah ini? |
| **Project** | Apa yang berhasil dan apa yang tidak? |
| **Team** | Bagaimana cara kerja tim kalian — termasuk saat konflik? |
| **Solution** | Apa yang akan kalian ubah kalau mengulang proyek? |
| **Individual** | Apa yang benar-benar kalian pelajari — kompetensi mana yang paling berkembang, dan apa buktinya? |

- **Selama**: pimpin diskusi reflektif; arahkan tiap anggota menjawab lima dimensi di atas (bukan sekadar daftar kejadian yang tidak terukur).
- **Setelah**: nilai kualitas refleksi (bukan panjang teks, tapi kedalaman & kejujuran). Selesaikan **Daftar Konsolidasi mentor**: rekap temuan, skor sementara, dan catatan perkembangan → serahkan final ke dosen sebagai input nilai & verifikasi passport (E7).
- **Penutup**: ucapkan apresiasi untuk tiap tim; berikan **1 kalimat apresiasi** untuk tiap mahasiswa (hal terbaik minggu ini).
- **Eskalasi**: klaim kompetensi pada passport yang tidak didukung bukti → laporkan ke dosen; passport diverifikasi dosen, bukan mentor.

---

# Bagian 4: Technical Mentoring Toolkit

Konten teknis di bawah ini **tidak dihapus** — hanya dipindahkan posisinya. Technical mentoring adalah **lapisan pendukung**, bukan definisi peran mentor. Dipakai terutama pada fase Design, Build, dan Test.

## 4.1 Daftar Alat (disiapkan sebelum semester)

| Alat | Kebutuhan | Catatan |
|---|---|---|
| Python | 3.10+ | Centang **Add to PATH** saat instalasi |
| Git | Terbaru | `git config --global user.name` & `user.email` |
| GitHub | Akun mahasiswa/org | Repositori kerja per tim |
| Editor | VS Code (opsional) | Pasang ekstensi Python |
| E-learning (Moodle) | Course PBL Level 1 | Peran **Grader** pada aktivitas `\| mentor` |
| Starter pack | `starter-pack/` (release) | Disediakan di e-learning/GitHub |

## 4.2 Alur Git Dasar (diajarkan Pekan 1, dipakai terus)

```bash
git clone <url-repo-tim>
git add <file>
git commit -m "feat: menambah fitur input"
git push origin main
```

Pesan commit: `feat:` (fitur baru) · `fix:` (perbaikan) · `docs:` (dokumentasi).

## 4.3 Struktur Repo (wajib dilestarikan)

```
repo-tim/
├── docs/
│   ├── D1-problem-brief.md
│   ├── D2-solution-design.md
│   ├── D3-prototipe.md
│   ├── D4-portfolio.md
│   ├── screenshots/        # bukti eksekusi
│   └── evidence/           # E1-E7 (lampiran D4)
├── src/
│   ├── main.py
│   ├── README.md
│   └── test_log.md
├── worksheets/             # WS01-WS16
└── assets/
```

## 4.4 Troubleshooting Cepat

| Gejala | Kemungkinan | Tindakan mentor |
|---|---|---|
| `python` tidak dikenali | Python tidak di PATH | Perbaiki PATH / reinstall centang *Add to PATH* |
| `git: command not found` | Git belum terinstal | Instal Git; saat instal pilih *Git from the command line* |
| Push ditolak (auth) | Token/credential salah | Pandu buat **Personal Access Token** (fine-grained, scope repo) |
| `TypeError: can't concatenate str` | `input()` belum di-*cast* | Arahkan cek tipe `type(x)`; jangan tulis perbaikannya |
| Program hang / loop tak berhenti | Infinite loop | Minta tunjukkan kondisi keluar / `break` |
| Struktur repo berantakan | File tak ditaruh folder | Arahkan ikuti struktur 4.3; gunakan `.gitignore` |
| Moodle submisi tidak muncul | File salah nama/besar | Cek ekstensi `.py` (bukan `.txt`), ukuran < batas, tombol *Submit* diklik |
| Konten unggahan ditolak | Berkas melebihi batas Moodle | Pecah lampiran; unggah lewat repo bila perlu |

---

# Bagian 5: Coaching Question Bank

## 5.1 Cara Memakai

Bank ini adalah **cadangan** untuk sesi tanpa konteks teknis murni. Mentor memilih 1–3 pertanyaan yang paling relevan dengan kondisi tim — bukan membacakan seluruh daftar. Prinsipnya tetap: **satu pertanyaan = satu petunjuk.**

## 5.2 Pertanyaan Kunci per Fase

| Fase | Pertanyaan inti |
|---|---|
| **Discover** | Apa yang kalian lihat? Siapa yang mengalami? Dari mana kalian tahu? |
| **Frame** | Apa evidence-nya? Apakah ini problem atau symptom? Mana fakta, mana asumsi? |
| **Define** | Siapa user utama? Apa yang sebenarnya mereka butuhkan? Bagaimana kita tahu kebutuhan itu terpenuhi? |
| **Design** | Requirement mana yang melahirkan fitur ini? Apakah desain ini bisa dibangun dengan sumber daya kalian? |
| **Build** | Apakah kode ini benar-benar merealisasikan desain? Siapa yang bisa menjelaskan bagian ini? |
| **Test** | Bagaimana kalian membuktikan solusi bekerja? Apa yang terjadi ketika user benar-benar mencoba? |
| **Communicate** | Bisakah orang luar memahami proyek kalian tanpa penjelasan teknis tambahan? |
| **Reflect** | Apa yang akan kalian lakukan berbeda jika mengulang proyek ini? Kompetensi mana yang paling berkembang? |

## 5.3 Pertanyaan Gate 1 & Gate 2

**GATE 1 (rehearsal, tanpa nilai):**

- Problem: apa masalahnya, apa buktinya, siapa user-nya?
- Design: apa requirement-nya, mengapa solusi ini dipilih, bagaimana solusi menjawab requirement?
- Individual: apa kontribusi saya, apa yang saya pahami, apa yang belum saya pahami?

**GATE 2 (walkthrough):**

- Jelaskan kode ini bagian demi bagian — termasuk yang dibantu AI.
- Tunjukkan tes yang kalian jalankan dan hasil aktualnya.
- Kalau ada yang gagal, apa yang sudah diperbaiki dan bagaimana kalian memvalidasinya?
- Bagaimana kode ini akan bereaksi jika inputnya di luar contoh?

## 5.4 Pola Percakapan: Ask → Probe → Hint → Explain

| Langkah | Contoh kalimat mentor |
|---|---|
| **Ask** | "Menurut kalian input-nya apa?" |
| **Probe** | "Prosesnya apa? Sudah kalian tulis pseudocode-nya?" |
| **Hint** | "Bagian mana yang belum kalian pahami?" |
| **Explain** | Baru jelaskan — sepanjang yang dibutuhkan, lalu kembali ke pertanyaan |

Yang **tidak** dilakukan: langsung memberikan kode atau jawaban benar pada pertanyaan pertama.

---

# Bagian 6: Pelaporan, Eskalasi & Koordinasi

## 6.1 Log Mentor: Progress + Learning + Risk

Dalam PBL, "tugas selesai" tidak selalu berarti "learning terjadi". Karena itu mentor mencatat tiga hal setiap pekan, bukan hanya satu:

| Tanggal | Tim | Fase | **Progress** — apa yang berjalan | **Learning** — apa yang bisa dikerjakan mahasiswa sekarang yang belum bisa minggu lalu | **Risk** — apa yang perlu diwaspai sebelum gate | Tindakan lanjutan | Eskalasi ke |
|---|---|---|---|---|---|---|
| | | | | | | | |

> Kolom **Learning** adalah pembeda utama: satu tim bisa punya progress 100% tetapi learning-nya stagnan. Dua kasus yang wajib dicatat sebagai kesenjangan belajar: (1) program jalan tetapi mahasiswa tidak bisa menjelaskan; (2) desain selesai tetapi evidence lapangan tipis.

## 6.2 Matriks Eskalasi

Mentor perlu tahu batas: apa yang boleh diselesaikan sendiri, dan apa yang harus naik ke atas.

| Situasi | Tindakan mentor | Eskalasi ke |
|---|---|---|
| Masalah teknis dasar (instalasi, PATH, Git, error umum) | Selesaikan sendiri atau via panduan 4.4 | — |
| Klarifikasi istilah, alur kerja, deadline | Jawab langsung | — |
| Coaching & umpan balik rutin | Selesaikan sendiri | — |
| Masalah **konsep akademik** (mis. keraguanan terhadap rumusan masalah) | Catat, beri pertanyaan pemandu | **Dosen** (MK terkait) |
| Hal terkait **penilaian** (interpretasi rubrik, pengecualian) | Jangan putuskan sendiri | **Dosen** |
| Perbedaan pendapat tentang **kualitas akademik** | Catat kedua argumen | **Dosen** |
| Kebutuhan **remedial** mahasiswa | Susun rencana bimbingan singkat | **Dosen** |
| Konflik serius / free-rider berulang | Catat bukti, jangan mediasi sendiri | **Koordinator** |
| Risiko proyek besar (objek studi aman, klien hilang) | Hentikan aktivitas sementara | **Koordinator** |
| Keterlambatan sistemik (semua tim) | Laporkan segera | **Koordinator** |
| Masalah antar-mata kuliah (mis. keterlambatan D4) | Catat kebutuhan kedua MK | **Koordinator** |

Aturan waktu: hal yang **menghambat gate** dilaporkan segera (maksimal 1×24 jam); sisanya dibahas pada weekly sync (6.3).

## 6.3 Mentor–Lecturer Weekly Sync

Tidak perlu rapat panjang. **15–20 menit per minggu** dengan dosen, sebelum pekan berjalan.

Agenda tetap:

1. What is happening? — apa yang sudah terjadi di tiap tim.
2. Which teams are at risk? — tim yang perlu perhatian khusus.
3. What learning gaps are appearing? — kesenjangan yang berulang, bukan kasus tunggal.
4. What intervention is needed? — bentuk intervensi yang diusulkan.
5. What should mentors focus on next week? — fokus mentoring minggu depan.

Output: daftar tim berisiko + fokus mentor minggu depan. Dengan agenda ini, mentor menjadi **early warning system** bagi dosen — masalah terdeteksi di minggu 5, bukan di minggu 8 saat GATE 1 sudah dekat.

## 6.4 Alur Penilaian

1. Nilai tiap aktivitas `| mentor` menggunakan **rubrik resmi dosen** (lihat peta di Bagian 3).
2. Simpan bukti: screenshot eksekusi, tangkapan walkthrough, catatan verifikasi manual.
3. Isi **Daftar Konsolidasi** (per tim: aktivitas, skor sementara, bukti, catatan).
4. Serahkan ke dosen yang relevan per checkpoint (P7, P8, P13, P16) — **dosen yang menetapkan nilai akhir**.

## 6.5 Integritas & Kebijakan AI

- Terapkan `ai_policy`: kode/artefak dibantu AI wajib ada **verification note**. Tindak lanjut dugaan *output AI mentah*: minta mahasiswa menjelaskan baris/konsep secara lisan.
- **Free-rider**: gunakan sprint log (WS11) + walkthrough (CKPT/WS10/GATE) sebagai bukti kontribusi; laporkan ke dosen bila anggota tim tidak berkontribusi.
- **Rekaman lapangan**: data yang dikumpulkan harus etis — tanpa data pribadi sensitif tanpa izin (lihat WS03 & `ai_policy`).
- Laporkan semua dugaan pelanggaran ke dosen; **jangan menghakimi mahasiswa di depan umum**.

---

# Bagian 7: Persiapan Mingguan & Penutupan

## 7.1 Mentor Preparation Checklist

Sebelum setiap pekan, mentor memeriksa sembilan hal ini:

- [ ] **Fase PBL** apa yang sedang berjalan pekan ini?
- [ ] **Learning outcome** fase apa yang harus tercapai di akhir pekan?
- [ ] **Evidence** apa yang diharapkan sudah ada?
- [ ] **Aktivitas dosen** apa yang akan berjalan pekan ini?
- [ ] **Aktivitas mahasiswa** apa yang harus saya dampingi?
- [ ] **Apa yang harus saya bantu?** (lihat 1.6 — coaching, bukan mengerjakan)
- [ ] **Risiko** apa yang harus saya amati?
- [ ] **Apa yang harus saya laporkan**? (6.1, 6.2, 6.3)
- [ ] **Apakah ada tim yang perlu saya awasi lebih ketat?** (dari laporan sync sebelumnya)

Checklist ini mengubah mentor dari **reactive helper** menjadi **prepared learning facilitator**.

## 7.2 Penutupan Semester

- Tutup dengan **passport** — Individual Competency Passport (E7) adalah rekam jejak kompetensi mahasiswa; mentor menyiapkan bukti pendukung, dosen yang memverifikasi.
- Serahkan **Daftar Konsolidasi** lengkap ke dosen koordinator.
- Isi bagian **Temuan lapangan** di bawah ini — ini yang menjadi bahan revisi panduan ini di semester berikutnya.

### Temuan Lapangan (untuk revisi berikutnya)

> Catat hal-hal berikut selama semester: apa yang tidak tercakup panduan ini, aktivitas yang membingungkan, scaffolding yang kurang, alat yang dibutuhkan, dan permintaan mahasiswa yang belum terjawab.

1. .
2. .
3. .

---

## Riwayat Revisi

| Versi | Tanggal | Fokus |
|---|---|---|
| v1.0 | 2026-09-20 | Draft awal: 16 pekan, aktivitas `\| mentor`, rubrik, troubleshooting |
| v2.0 | 2026-09-30 | Revisi sesuai `revision_note_2.md`: definisi PBL Learning Facilitator, layer fase PBL pada 16 pekan, Problem Framing Coaching, ecosystem & integration map, *Mentor Must Not*, Coaching Question Bank, log Progress+Learning+Risk, eskalasi, weekly sync 15–20 menit, preparation checklist |
| v2.1 | 2026-10-01 | Konsistensi kode artefak: hapus `Lat-M1`–`Lat-M4` (kode modul). Pekan 1–4 kini memakai `WS01`–`WS06` + draf `D1`/`D2`; latihan teknis tanpa kode artefak. Peta aktivitas 16 pekan: 4 support + 13 dinilai |

---

*Buku petunjuk ini adalah acuan kerja mentor PjBL Level 1. Struktur 16 pekan sengaja dipertahankan agar selaras dengan aktivitas `| mentor` di Moodle Course PBL Level 1. Temuan lapangan dan wacana perbaikan disampaikan ke dosen koordinator; bila perlu dirubah, gunakan nomor revisi & tanggal.*
