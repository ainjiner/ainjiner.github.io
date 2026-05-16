# Ainjiner — Research Brief

> **Dokumen ini ditujukan untuk peneliti, akademisi, dosen, dan lembaga riset yang ingin berkolaborasi atau menggunakan proyek Ainjiner sebagai objek atau infrastruktur penelitian.**

---

## Daftar Isi

- [Ringkasan Eksekutif](#ringkasan-eksekutif)
- [Latar Belakang & Konteks](#latar-belakang--konteks)
- [Peluang Penelitian per Proyek](#peluang-penelitian-per-proyek)
- [Metodologi yang Bisa Digunakan](#metodologi-yang-bisa-digunakan)
- [Dataset & Infrastruktur Tersedia](#dataset--infrastruktur-tersedia)
- [Kolaborasi yang Kami Tawarkan](#kolaborasi-yang-kami-tawarkan)
- [Referensi & Literatur Terkait](#referensi--literatur-terkait)
- [Kontak](#kontak)

---

## Ringkasan Eksekutif

Ainjiner mengembangkan tiga proyek open-source di persimpangan **kecerdasan buatan, pendidikan, dan infrastruktur teknologi terbuka**:

| Proyek | Domain Riset Utama |
|--------|--------------------|
| **2USE** | AI Ethics, Pedagogical Computing, HCI, Critical Thinking |
| **We Will Shine** | Educational Psychology, Mental Health Tech, HCI, Social Computing |
| **AI Lab** | MLOps, LLM Observability, Reproducible AI Research |

Semua proyek bersifat **open-source (MIT)**, dapat diaudit, dimodifikasi, dan digunakan sebagai platform penelitian tanpa biaya lisensi.

---

## Latar Belakang & Konteks

### Masalah yang Kami Identifikasi

**1. Ketergantungan kognitif terhadap AI**

Adopsi LLM yang masif (ChatGPT, Gemini, dll.) menimbulkan kekhawatiran serius di kalangan pendidik: siswa semakin sering meminta jawaban langsung tanpa proses berpikir. Tidak ada studi longitudinal di Indonesia tentang dampak ini, dan tidak ada middleware open-source yang secara aktif menangkal fenomena ini.

**2. Krisis bimbingan konseling di sekolah Indonesia**

Rasio Guru BK (Bimbingan Konseling) di Indonesia adalah **1:500 siswa**, jauh di bawah standar UNESCO (1:250). Mayoritas sekolah tidak memiliki sistem digital untuk mendokumentasikan kondisi wellbeing siswa. Data dari Kemendikbud (2023) menunjukkan 34% siswa SMA mengalami tekanan psikologis signifikan tanpa akses layanan konseling.

**3. Fragmentasi ekosistem LLM**

Developer yang menggunakan LLM menghadapi fragmentasi: puluhan provider, format API berbeda, tidak ada standar observability. Ini menghambat reproducibility dalam penelitian berbasis LLM.

---

## Peluang Penelitian per Proyek

### 2USE — Socratic AI Middleware

#### Apa itu 2USE?
Sebuah middleware yang diposisikan antara user dan LLM. Alih-alih meneruskan query langsung, 2USE menganalisis pertanyaan dan merespons dengan pertanyaan klarifikasi berbasis metode Sokrates sebelum (atau sebagai pengganti) jawaban langsung.

#### Pertanyaan Penelitian Terbuka

1. **Efektivitas Pedagogis:** Apakah interaksi dengan 2USE meningkatkan kemampuan pemecahan masalah siswa dibandingkan LLM konvensional? (Quasi-experimental study)
2. **UX & Acceptance:** Bagaimana siswa dan guru menerima AI yang "menolak menjawab"? Apa faktor frustrasi vs. apresiasi? (Mixed-methods HCI)
3. **Desain Pertanyaan Sokrates:** Algoritma apa yang paling efektif untuk generate Socratic questions dari query awal? (NLP / Prompt Engineering research)
4. **AI Alignment:** Apakah 2USE bisa digunakan sebagai mekanisme "safety layer" untuk mengurangi hallucination dengan memaksa user memperjelas konteks? (AI Safety)
5. **Longitudinal Learning:** Apakah penggunaan 2USE secara konsisten selama 1 semester mempengaruhi kebiasaan berpikir kritis siswa? (Educational Psychology)

#### Metodologi yang Disarankan
- RCT (Randomized Controlled Trial) atau quasi-experimental di setting sekolah
- Think-aloud protocol untuk UX study
- Pre-post test critical thinking (Watson-Glaser, CCTDI)
- Log analysis dari middleware interactions

---

### We Will Shine — AI Career Guidance & Student Wellbeing

#### Apa itu We Will Shine?
Platform berbasis web (SvelteKit) yang menyediakan:
- AI mentor untuk eksplorasi minat dan karier siswa
- Jurnal digital anonim untuk ekspresi diri
- Dashboard untuk Guru BK dengan aggregated wellbeing insights

#### Pertanyaan Penelitian Terbuka

1. **Efektivitas AI Guidance:** Seberapa akurat rekomendasi karier AI vs. Guru BK manusia dalam konteks siswa Indonesia? (Comparative study)
2. **Mental Health Disclosure:** Apakah siswa lebih terbuka mengungkapkan distress kepada AI dibanding manusia? (Social desirability bias study)
3. **Equity & Access:** Apakah platform ini efektif untuk siswa di daerah terpencil dengan koneksi internet terbatas? (Digital divide research)
4. **Guru BK Adoption:** Apa barrier utama Guru BK dalam mengadopsi dashboard digital? (Technology Acceptance Model / TAM)
5. **Cultural Fit:** Apakah framing karier ala barat relevan untuk siswa Indonesia, atau perlu adaptasi kontekstual? (CulturalAI / localization research)
6. **Privacy & Trust:** Bagaimana siswa memersepsikan privasi data wellbeing mereka di platform digital sekolah? (Privacy Paradox in EdTech)

#### Metodologi yang Disarankan
- Survey longitudinal (baseline, 3 bulan, 6 bulan)
- Semi-structured interviews dengan siswa dan Guru BK
- A/B testing versi fitur
- Analysis sentimen dari entri jurnal (dengan consent)
- Validated scales: GHQ-12, SDQ, PHQ-9 adaptasi Indonesia

---

### AI Lab — Open LLM Engineering Platform

#### Apa itu AI Lab?
Platform self-hosted untuk manajemen provider LLM, tracking eksperimen, analisis biaya, dan sinkronisasi konfigurasi. Mendukung 10+ provider (OpenAI, Anthropic, Google Gemini, Groq, dll.).

#### Pertanyaan Penelitian Terbuka

1. **LLM Cost Efficiency:** Bagaimana perbandingan cost-per-token antar provider untuk task NLP spesifik (klasifikasi, summarization, QA)? (Benchmark study)
2. **Reproducibility:** Apakah platform open-source seperti AI Lab meningkatkan reproducibility eksperimen LLM dibanding setup manual? (ML Engineering research)
3. **Observability Gaps:** Metrik apa yang paling kritis untuk LLM observability yang belum tersedia di tools mainstream? (HCI / MLOps)
4. **Multi-provider Orchestration:** Strategi routing LLM yang optimal berdasarkan task type, latency, dan anggaran? (Systems research)

---

## Metodologi yang Bisa Digunakan

### Kuantitatif
- Randomized Controlled Trial (RCT) dengan kelompok kontrol (LLM standar) dan eksperimen (2USE)
- Survey longitudinal dengan instrumen tervalidasi
- A/B testing fitur platform
- Log analysis dan behavioral analytics
- Benchmark komparasi (AI Lab)

### Kualitatif
- Semi-structured interviews (siswa, guru, orang tua)
- Focus group discussion (FGD)
- Ethnographic observation di sekolah
- Thematic analysis dari percakapan AI (dengan consent)

### Mixed Methods
- Sequential explanatory design (kuantitatif → kualitatif untuk explain findings)
- Triangulasi data dari log platform, survey, dan interview

---

## Dataset & Infrastruktur Tersedia

| Resource | Tersedia | Catatan |
|----------|----------|---------|
| Kode sumber 2USE | ✅ Open source | github.com/ainjiner/2USE |
| Kode sumber We Will Shine | ✅ Open source | github.com/ainjiner/we-will-shine |
| Kode sumber AI Lab | ✅ Open source | github.com/ainjiner/ai-lab |
| Log interaksi (anonymized) | 🔄 Dalam pengembangan | Butuh ethics approval |
| Dataset kurikulum Kemendikbud | 🔄 Sedang dikurasi | Untuk RAG We Will Shine |
| Benchmark LLM cost | 🔄 Dalam pengembangan | Via AI Lab experiment tracker |
| Akses deployment untuk penelitian | ✅ Bisa diatur | Hubungi kami |

---

## Kolaborasi yang Kami Tawarkan

### Untuk Dosen / Peneliti
- **Research partnership:** Kami menyediakan platform, Anda menyediakan metodologi dan publikasi
- **Data access:** Log interaksi ter-anonymize (dengan ethics clearance dari institusi Anda)
- **Co-authorship:** Terbuka untuk join paper di venue EdTech, HCI, atau AI
- **Thesis supervision support:** Bisa menjadi mitra industri untuk mahasiswa S1/S2/S3

### Untuk Universitas
- **MoU penelitian:** Formalkan kolaborasi untuk akses data jangka panjang
- **Pilot sekolah:** Kami bantu deploy We Will Shine di sekolah mitra universitas Anda
- **Guest lecture:** Tim Ainjiner siap berbicara di kelas atau seminar
- **Capstone / PKM:** Cocok sebagai objek atau platform untuk PKM-K, PKM-T, atau capstone project

### Untuk Lembaga Riset (BRIN, dll.)
- **Joint grant application:** Kami bisa menjadi mitra industri/teknologi
- **Research infrastructure:** AI Lab bisa digunakan sebagai platform eksperimen LLM oleh peneliti BRIN
- **Data sharing agreement:** Siap diskusi formal

---

## Referensi & Literatur Terkait

### Socratic AI & Critical Thinking
- Paul, R., & Elder, L. (2019). *The Miniature Guide to Critical Thinking Concepts and Tools.* Foundation for Critical Thinking.
- Agarwal, P.K. (2021). Retrieval practice & Bloom's taxonomy: Do students need fact knowledge before higher order learning? *Journal of Educational Psychology.*
- Bender, E.M. et al. (2021). On the Dangers of Stochastic Parrots. *FAccT 2021.*

### Student Wellbeing & EdTech Indonesia
- Kementerian Pendidikan dan Kebudayaan RI (2023). *Rapor Pendidikan Indonesia 2023.*
- UNESCO (2019). *School Counselling Ratios: A Global Review.*
- Darmawan, I.P.A. (2022). Digital mental health interventions for Indonesian youth. *Journal of Medical Internet Research.*

### LLM Reproducibility & MLOps
- Dodge, J. et al. (2019). Show Your Work: Improved Reporting of Experimental Results. *EMNLP 2019.*
- Liao, Q.V. & Vaughan, J.W. (2023). AI Transparency in the Age of LLMs. *arXiv:2306.01941.*

---

## Kontak

Untuk diskusi kolaborasi penelitian:

- **Email:** hello@ainjiner.ai
- **GitHub:** https://github.com/ainjiner
- **Dokumen terkait:**
  - [Funding Guide](FUNDING-GUIDE.md)
  - [Partnership Opportunities](PARTNERSHIPS.md)
  - [Impact Statement](docs/IMPACT.md)
  - [Project Roadmap](docs/ROADMAP.md)

Kami merespons semua inquiry penelitian dalam **3 hari kerja**.
