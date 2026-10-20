# Elea Skill, Folder Structure

```
elea-skill/
│
├── SYSTEM-PROMPT.md                          # System prompt utama Elea (LOAD PERTAMA KALI)
├── SKILL.md                                  # Skill detail Elea (BACA SETELAH SYSTEM PROMPT)
├── BRAND-PROFILE.md                          # Konteks brand Monacruz permanen (menyatu, dibaca paling awal)
│
├── standards/                                # Standar per capability + humanize + anti-generik
│   ├── _FINAL-AI-humanize-writing-guide.md  # ⚠️ WAJIB BACA SELALU. Standar gaya tulisan + protokol scan
│   ├── standar-branding-lifecycle.md        # ⚠️ Checklist menyusun / menyesuaikan / merawat brand
│   ├── standar-brand-audit.md               # Framework & standar Brand Audit (Brand Vitals 5C)
│   ├── standar-positioning.md               # Standar penyusunan positioning & differentiation strategy
│   ├── standar-brand-personality.md         # Standar personality, archetype, voice & tone, Sosok Brand
│   ├── standar-communication-strategy.md    # Standar penyusunan communication framework
│   ├── standar-brand-conversion.md          # Standar brand funnel & Brand dan Jualan Balance
│   └── anti-generik-rules.md                # ⚠️ Red-flag phrases & standar spesifisitas (WAJIB BACA)
│
├── frameworks/                              # Framework analisis & evaluasi
│   ├── brand-vitals-framework.md            # Brand Vitals (5C) + scoring system
│   ├── competitive-analysis-framework.md    # Analisis & mapping kompetitor brand
│   ├── brand-shift-framework.md             # Brand Shift: spektrum evolusi & repositioning
│   ├── premium-triangle-framework.md        # Premium Triangle (Exclusivity × Identity × Storytelling)
│   ├── value-stick-framework.md             # Value Stick (WTP/WTS, value creation vs capture)
│   ├── brand-core-system-framework.md       # Brand Core System (Makna, Gerak, Nalar)
│   └── marketing-evolution-framework.md     # Evolusi marketing 1.0-6.0 (Kotler/Kartajaya/Setiawan)
│
└── references/                              # Referensi konteks & contoh interaksi
    ├── interaction-examples.md              # Contoh interaksi Elea di berbagai skenario
    ├── case-pattern-library.md              # Pola strategis brand building dari studi kasus nyata
    └── brand-wisdom-indonesia.md            # Insight branding perspektif Indonesia (Brand Ladder, naming, adopsi)
```

## Urutan Baca

1. **BRAND-PROFILE.md**: dibaca paling awal tiap sesi. Konteks brand user yang jadi fondasi semua output.
2. **SYSTEM-PROMPT.md**: identitas Elea, prinsip berpikir, Guard Konteks, humanize, cara kerja, arsenal, kemampuan, interaksi dengan skills lain, batasan.
3. **SKILL.md**: detail teknis 8 capabilities, standar output, format output, gaya penulisan, batasan.
4. **standards/**: ⚠️ WAJIB dibaca sebelum mengerjakan capability tertentu. `_FINAL-AI-humanize-writing-guide.md` dibaca SELALU.
5. **frameworks/**: dibaca saat perlu kerangka analisis, scoring, atau evaluasi.
6. **references/**: dibaca saat perlu template profil, contoh interaksi, atau pola kasus.

## Prinsip

- **BRAND-PROFILE.md** = konteks brand user (SIAPA brand yang sedang ditangani)
- **SYSTEM-PROMPT.md** = identitas + fondasi berpikir (SIAPA Elea, BAGAIMANA Elea berpikir)
- **SKILL.md** = logic + capability detail (APA yang Elea bisa kerjakan, BAGAIMANA mengerjakannya)
- **Standards** = quality gate (standar minimum per capability yang TIDAK BOLEH dilanggar)
- **Frameworks** = model (kerangka konseptual analisis & evaluasi)
- **References** = konteks (template profil, contoh interaksi, pola kasus sebagai referensi lensa)

## Catatan untuk Builder

Skill ini dirancang modular dan extensible:
- **Menambah knowledge base:** Tambahkan file .md baru di `references/` dan update pointer di SYSTEM-PROMPT.md
- **Menambah framework:** Tambahkan file .md baru di `frameworks/` dan update pointer di SKILL.md
- **Menambah standar baru:** Tambahkan file .md baru di `standards/` dan update pointer di SKILL.md
- **Menambah contoh interaksi:** Update `references/interaction-examples.md`

## Catatan Brand Profile (tinggal colok)

`BRAND-PROFILE.md` di root adalah konteks brand Monacruz yang permanen dan menyatu di dalam skill. Isinya ada di antara penanda `<!-- BRAND_PROFILE_START -->` dan `<!-- BRAND_PROFILE_END -->`, dan dibaca Elea paling awal tiap sesi sebagai fondasi semua output.

## Tambahan
- references/skill-ecosystem.md (roster peran + peta handoff antar-skill)
