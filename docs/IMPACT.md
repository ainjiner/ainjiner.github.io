# Ainjiner — Impact Statement

> **Pernyataan dampak sosial yang ingin dicapai oleh proyek-proyek Ainjiner, beserta metrik keberhasilan yang terukur.**

---

## Visi Dampak

> *Setiap siswa Indonesia, di manapun mereka berada, memiliki akses ke panduan karier berbasis AI, ruang mengekspresikan diri yang aman, dan pendidikan yang mengajarkan mereka berpikir kritis — bukan bergantung pada mesin.*

---

## Konteks: Masalah yang Kami Tangani

### Masalah 1 — AI Dependency Crisis

Adopsi LLM yang masif (2023–2025) telah mengubah cara belajar siswa di seluruh dunia. Di Indonesia:

- **85%+** mahasiswa menggunakan ChatGPT atau tools serupa untuk mengerjakan tugas (survei informal berbagai universitas, 2024)
- Tren "copy-paste dari AI" menggantikan proses berpikir
- Tidak ada tools terbuka yang secara aktif menangkal ketergantungan ini
- Kurikulum sekolah belum beradaptasi dengan kecepatan adopsi AI

**Dampak jangka panjang:** Generasi yang pandai mendapatkan jawaban, tapi tidak pandai membentuk pertanyaan.

---

### Masalah 2 — Krisis Bimbingan Konseling

Data resmi Kemendikbud (2023):

| Indikator | Angka | Standar |
|-----------|-------|---------|
| Rasio Guru BK : Siswa | 1 : 500+ | 1 : 250 (UNESCO) |
| Sekolah dengan sistem BK digital | < 5% | — |
| Siswa SMA dengan tekanan psikologis signifikan | ~34% | — |
| Siswa yang pernah berkonsultasi ke Guru BK | ~18% | — |

**Kesimpulan:** 82% siswa yang membutuhkan bantuan tidak pernah mendapatkannya.

---

### Masalah 3 — Fragmentasi AI Development

Untuk developer Indonesia yang ingin membangun di atas LLM:

- Puluhan provider, format API berbeda-beda
- Tidak ada standar terbuka untuk tracking eksperimen LLM
- Biaya eksperimen tidak terprediksi
- Reproductibility riset berbasis LLM sangat rendah

---

## Target Dampak per Proyek

### 2USE — Impact Targets

| Metrik | 6 Bulan | 1 Tahun | 3 Tahun |
|--------|---------|---------|---------|
| Platform edtech yang mengadopsi | 1–2 | 5–10 | 30+ |
| Interaksi Socratic terfasilitasi | 10,000 | 100,000 | 5,000,000 |
| Paper penelitian terpublikasi | 0 | 1 | 3 |
| Dataset Socratic QA (open) | — | 5,000 pair | 50,000 pair |
| Kontributor aktif | 5 | 20 | 100 |

**Indikator keberhasilan kualitatif:**
- Siswa yang menggunakan 2USE menunjukkan peningkatan skor critical thinking (diukur dengan CCTDI atau Watson-Glaser)
- Feedback dari guru: "Siswa mulai bertanya lebih dalam, bukan sekadar mencari jawaban"

---

### We Will Shine — Impact Targets

| Metrik | 6 Bulan | 1 Tahun | 3 Tahun |
|--------|---------|---------|---------|
| Siswa aktif | 500 | 2,000 | 50,000 |
| Sekolah mitra | 3 | 15 | 100 |
| Sesi konseling AI terfasilitasi | 5,000 | 30,000 | 1,000,000 |
| Guru BK terlatih | 20 | 80 | 500 |
| Kabupaten/kota tercakup | 3 | 10 | 50 |
| Paper penelitian | 0 | 1 | 3 |

**Indikator keberhasilan kualitatif:**
- Siswa melaporkan peningkatan kejelasan arah karier (self-report survey)
- Guru BK: "Saya bisa membantu lebih banyak siswa karena data memberikan insight yang saya tidak bisa kumpulkan manual"
- Kepala sekolah: "Jumlah kasus siswa yang tidak tertangani menurun"

**Validated instruments yang akan digunakan:**
- GHQ-12 (General Health Questionnaire) — wellbeing umum
- SDS (Self-Directed Search) — eksplorasi karier
- CSEI (Career Self-Efficacy Inventory) adaptasi Indonesia

---

### AI Lab — Impact Targets

| Metrik | 6 Bulan | 1 Tahun | 3 Tahun |
|--------|---------|---------|---------|
| GitHub stars | 200 | 500 | 2,000 |
| Active self-hosters | 50 | 200 | 2,000 |
| Provider didukung | 10 | 20 | 30+ |
| Papers yang menggunakan AI Lab | 0 | 2 | 15 |
| Komunitas aktif | 20 | 100 | 500 |

**Indikator keberhasilan kualitatif:**
- Peneliti berhasil mereproduksi eksperimen LLM menggunakan AI Lab
- Developer: "AI Lab adalah satu-satunya tool yang saya percaya untuk tracking LLM cost di production"

---

## Theory of Change

```
INPUT                → AKTIVITAS              → OUTPUT            → OUTCOME           → IMPACT
─────────────────────────────────────────────────────────────────────────────────────────────────
Dana & kontribusi    Develop 2USE             Siswa berinteraksi  Siswa lebih kritis  Generasi yang
OSS community    →   Deploy WS            →   dengan AI yg     →  dalam menggunakan → tidak bergantung
Research partners    Research & publish       mengajarkan          AI & teknologi      pada AI
                     Pilot sekolah            berpikir
                                                                  Siswa menemukan     Indonesia yang
                                             Guru BK punya        arah karier lebih  punya infrastruktur
                                             data untuk           jelas dengan        AI terbuka &
                                             intervensi dini      bantuan AI          berdaulat
```

---

## Komitmen Transparansi Dampak

Kami berkomitmen untuk mempublikasikan:

1. **Laporan dampak kuartalan** — progress terhadap target metrik
2. **Raw data (anonymized)** — dataset interaksi untuk peneliti
3. **Laporan keuangan** — via Open Collective setiap bulan
4. **Lessons learned** — termasuk kegagalan dan pivot yang kami lakukan
5. **Research output** — semua paper dalam open access

---

## Siapa yang Terdampak

### Penerima Manfaat Langsung

| Kelompok | Proyek | Cara Terdampak |
|----------|--------|----------------|
| Siswa SMA/SMK (15–18 tahun) | We Will Shine | Guidance karier, ruang ekspresi aman |
| Guru BK | We Will Shine | Tools dan data untuk kerja lebih efektif |
| Mahasiswa | 2USE | AI yang mengajarkan berpikir, bukan menggantikan |
| Developer Indonesia | AI Lab | Infrastruktur LLM terbuka dan dapat diaudit |
| Peneliti EdTech | Semua | Platform open-source untuk penelitian |

### Penerima Manfaat Tidak Langsung

| Kelompok | Cara Terdampak |
|----------|----------------|
| Orang tua siswa | Anak lebih siap menghadapi dunia kerja |
| Institusi pendidikan | Pengurangan beban konseling, data berbasis bukti |
| Industri teknologi Indonesia | Talenta yang lebih kritis dan terlatih |
| Ekosistem OSS Indonesia | Proyek referensi berkualitas tinggi |
| Komunitas global | Dataset & paper yang dapat digunakan ulang |

---

## Risiko & Mitigasi

| Risiko | Kemungkinan | Dampak | Mitigasi |
|--------|-------------|--------|----------|
| Tidak ada funding — proyek berhenti | Sedang | Tinggi | Jaga agar codebase tetap simple & maintainable oleh 1 orang |
| Privacy siswa terkompromi | Rendah | Sangat tinggi | Minimisasi data, enkripsi end-to-end, audit berkala |
| Resistansi dari guru/sekolah | Sedang | Sedang | Pendekatan bottom-up, libatkan guru sejak desain |
| Kualitas AI output buruk (hallucination) | Sedang | Tinggi | RAG dengan data tervalidasi, human-in-the-loop |
| Fork atau komersialisasi melanggar spirit OSS | Rendah | Rendah | MIT License mengizinkan ini; fokus pada reputasi komunitas |

---

*Impact statement ini direvisi setiap 6 bulan berdasarkan data aktual dari pilot dan penelitian.*

**Lihat juga:** [Roadmap](ROADMAP.md) | [Budget](BUDGET.md) | [Research Brief](../RESEARCH.md)
