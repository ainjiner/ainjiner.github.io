# Ainjiner — Project Roadmap

> **Roadmap 3 tahun untuk AI Lab, 2USE, dan We Will Shine — beserta milestone yang terhubung dengan target pendanaan.**

---

## Ringkasan Roadmap

```
2025 ████████░░░░░░░░░░░░░░░░░░░░░░░░ Foundation
2026 ░░░░░░░░████████████░░░░░░░░░░░░ Growth
2027 ░░░░░░░░░░░░░░░░████████████████ Scale
```

| Fase | Periode | Fokus | Funding Target |
|------|---------|-------|----------------|
| **Foundation** | 2025 | MVP, open source, community | $0 – $15K |
| **Growth** | 2026 | Pilot, research, partnerships | $15K – $100K |
| **Scale** | 2027 | National deployment, sustainability | $100K – $500K |

---

## 2USE — Socratic AI Middleware

### Fase Foundation (2025 — saat ini)

- [x] Arsitektur middleware dasar
- [x] Integrasi dengan OpenAI, Anthropic, Gemini API
- [x] Open source di GitHub (MIT License)
- [x] README dan dokumentasi dasar
- [ ] Socratic question generator v1 (rule-based)
- [ ] REST API endpoint `/intercept`
- [ ] CLI tool untuk testing lokal
- [ ] Dokumentasi untuk developer (API reference)
- [ ] Unit tests & CI pipeline

**Milestone:** 2USE v0.1 — usable by developers

---

### Fase Growth (2026) — Target: $15K–$50K

- [ ] Socratic question generator v2 (LLM-assisted, context-aware)
- [ ] Plugin untuk OpenCode, Continue, Cursor
- [ ] Web demo yang bisa dicoba publik
- [ ] Pilot dengan 2–3 platform edtech Indonesia
- [ ] Paper penelitian: "Socratic AI Middleware: Effects on Critical Thinking" (co-authored dengan universitas mitra)
- [ ] Dashboard analytics untuk edtech operator
- [ ] SDK: `@2use/sdk` untuk JavaScript/TypeScript
- [ ] Konfigurasi Socratic intensity (mild, moderate, strict)

**Funding yang dibutuhkan:**
- 1 developer full-time: $24,000/tahun
- Research collaboration: $5,000
- Infrastructure & API costs: $3,000
- **Total: ~$32,000**

**Milestone:** 2USE v1.0 — production-ready, published paper

---

### Fase Scale (2027) — Target: $50K–$200K

- [ ] Model fine-tuned khusus Socratic reasoning (Bahasa Indonesia)
- [ ] Integrasi dengan LMS (Moodle, Google Classroom, Canvas)
- [ ] Deployment di 20+ platform edtech dan universitas
- [ ] Longitudinal study: dampak 1 tahun penggunaan 2USE
- [ ] Open dataset: Socratic question pairs (Bahasa Indonesia)
- [ ] Komunitas kontributor: 50+ active contributors

**Milestone:** 2USE sebagai standar de facto Socratic AI middleware Indonesia

---

## We Will Shine — Student Wellbeing Platform

### Fase Foundation (2025 — saat ini)

- [x] MVP: AI career guidance
- [x] Jurnal digital anonim
- [x] Dashboard Guru BK (v1)
- [x] Deploy ke GitHub Pages
- [x] Open source (MIT License)
- [ ] Onboarding flow untuk siswa (usia 15–18)
- [ ] Bahasa: 100% Bahasa Indonesia + ragam daerah (Jawa, Sunda)
- [ ] Integrasi RAG dengan data kurikulum Kemendikbud
- [ ] Mobile responsive optimization
- [ ] Privacy policy & terms of service (compliant dengan UU PDP)

**Milestone:** We Will Shine v1.0 — ready for school pilots

---

### Fase Growth (2026) — Target: $20K–$80K

- [ ] **Pilot sekolah:** 10 SMA/SMK di 5 kota berbeda
- [ ] Modul: tes minat-bakat (adaptasi dari Holland's RIASEC)
- [ ] Modul: simulasi wawancara kerja berbasis AI
- [ ] Integrasi dengan data BPS (lapangan kerja, prospek karier per jurusan)
- [ ] Notifikasi wellbeing alert untuk Guru BK
- [ ] Multi-school management dashboard
- [ ] Training material untuk Guru BK
- [ ] Evaluasi pilot: laporan dampak semester 1

**Funding yang dibutuhkan:**
- 1 developer full-time: $24,000/tahun
- 1 UX researcher/designer: $12,000/tahun
- Pilot sekolah (perjalanan, pelatihan): $8,000
- Infrastruktur hosting: $6,000
- **Total: ~$50,000**

**Milestone:** 1,000 siswa aktif, laporan dampak terpublikasi

---

### Fase Scale (2027) — Target: $80K–$300K

- [ ] **50 sekolah** di 15 kabupaten/kota
- [ ] Integrasi dengan DAPODIK (data pokok pendidikan Kemendikbud)
- [ ] Modul orang tua: insight dan panduan mendampingi anak
- [ ] API untuk dinas pendidikan kab/kota
- [ ] White-label untuk NGO dan yayasan pendidikan
- [ ] Studi dampak jangka panjang (1 tahun) terpublikasi di jurnal internasional
- [ ] Roadmap menuju sustainability: model freemium untuk sekolah swasta

**Milestone:** Coverage 50,000+ siswa, sustainable revenue model

---

## AI Lab — ML/LLM Engineering Platform

### Fase Foundation (2025 — saat ini)

- [x] Provider registry: 10 provider
- [x] Model catalog dengan search & compare
- [x] Experiment tracker
- [x] Analytics & budget management
- [x] REST API (Hono) + CLI + Web UI (Qwik)
- [x] Config sync: OpenCode, Cursor, Continue, Aider
- [x] SQLite persistence (self-hosted)
- [ ] Dokumentasi API lengkap (OpenAPI spec)
- [ ] Docker image untuk self-hosting mudah
- [ ] Tutorial: "Self-host your own LLM dashboard in 5 minutes"

**Milestone:** AI Lab v1.0 — stable, documented, Docker-ready

---

### Fase Growth (2026) — Target: $10K–$30K

- [ ] Provider tambahan: Mistral, Cohere, Together AI, Perplexity
- [ ] Model playground dengan streaming langsung di Web UI
- [ ] Team collaboration features (multi-user)
- [ ] Webhook & alerting (budget exceeded, latency spike)
- [ ] Export ke Prometheus/Grafana
- [ ] Integrasi LangChain dan LlamaIndex
- [ ] Paket `@ai-lab/openai-compatible` dirilis ke npm

**Funding yang dibutuhkan:**
- 1 developer part-time: $12,000/tahun
- Infrastructure & testing: $3,000
- **Total: ~$15,000**

**Milestone:** 500+ GitHub stars, 100+ active self-hosters

---

### Fase Scale (2027) — Target: $30K–$100K

- [ ] Cloud-hosted option (SaaS lite) untuk tim yang tidak mau self-host
- [ ] RAG/CAG support built-in
- [ ] Enterprise features: SSO, audit log, role-based access
- [ ] Benchmark dataset: LLM performance per task type Indonesia
- [ ] Komunitas: 1,000+ GitHub stars, 200+ contributors

**Milestone:** Go-to open-source LLM management tool di Indonesia

---

## Linimasa Konsolidasi

```
Q3 2025  ▶ 2USE v0.1 + AI Lab Docker + WS v1.0 ready
Q4 2025  ▶ Apply ke NLnet, Mozilla Tech Fund, GitHub Fund
Q1 2026  ▶ Pilot sekolah WS (batch 1: 3 sekolah)
Q2 2026  ▶ Kedaireka submission (dengan mitra universitas)
Q3 2026  ▶ 2USE v1.0 + paper submission
Q4 2026  ▶ Laporan dampak WS pilot + apply ke Ford Foundation
Q1 2027  ▶ Scale WS ke 50 sekolah
Q2 2027  ▶ AI Lab v2.0 + SaaS lite
Q4 2027  ▶ Review sustainability model
```

---

## Bagaimana Funding Mempengaruhi Kecepatan

| Kondisi Funding | Kecepatan | Yang Bisa Dicapai di 2026 |
|-----------------|-----------|---------------------------|
| $0 (saat ini) | 10% | Hanya maintenance |
| $15K | 30% | 1 developer part-time, pilot kecil |
| $50K | 70% | 2 developer, pilot 10 sekolah, 1 paper |
| $100K | 100% | Full team, 50 sekolah, research program |
| $250K+ | 150% | Ekspansi regional ASEAN |

---

*Roadmap ini bersifat living document dan diperbarui setiap kuartal. Lihat [IMPACT.md](IMPACT.md) untuk target dampak sosial, dan [BUDGET.md](BUDGET.md) untuk rincian anggaran.*
