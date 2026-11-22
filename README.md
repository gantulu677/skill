# AI Agent Skills Repository

Katalog modular **AI Agent Skills** yang mengutamakan instruksi portabel, tanggung jawab terpisah, dan penggunaan tools berdasarkan ketersediaan serta otorisasi nyata.

## Struktur

```text
skill/
├── README.md
└── skills/
    ├── github-repository-auditor/{SKILL.md,references/}
    ├── react-architecture-designer/{SKILL.md,references/}
    ├── documentation-engineer/{SKILL.md,references/}
    ├── skill-creator/{SKILL.md,references/}
    ├── skill-auditor/{SKILL.md,references/}
    └── prompt-engineer/{SKILL.md,references/}
```

## Katalog

| Skill | Tanggung jawab |
|---|---|
| [github-repository-auditor](skills/github-repository-auditor/SKILL.md) | Audit struktur, konfigurasi, dokumentasi, dependensi, dan konsistensi repository GitHub. |
| [react-architecture-designer](skills/react-architecture-designer/SKILL.md) | Desain dan review arsitektur React, routing, layout, state, dan kontrak komponen. |
| [documentation-engineer](skills/documentation-engineer/SKILL.md) | Menyusun, mengaudit, dan memelihara dokumentasi teknis. |
| [skill-creator](skills/skill-creator/SKILL.md) | Merancang dan menulis AI Agent Skills modular. |
| [skill-auditor](skills/skill-auditor/SKILL.md) | Audit kualitas, keamanan, konsistensi, dan kesiapan Skill. |
| [prompt-engineer](skills/prompt-engineer/SKILL.md) | Merancang, menguji, dan menyempurnakan prompt serta template. |

## Prinsip

1. Satu Skill memiliki satu tanggung jawab utama.
2. Instruksi inti bersifat platform-independent; detail integrasi platform dipisahkan.
3. Skill menjelaskan cara menggunakan kemampuan; tools, konektor, izin, dan runtime menyediakan kemampuan eksekusinya.
4. Tidak ada dependensi tersembunyi antar-Skill.
5. Tindakan yang mengubah sistem eksternal memerlukan otorisasi yang sesuai.
6. Klaim inspeksi, pengujian, kompatibilitas, dan implementasi harus berbasis bukti.

## Konvensi Skill

Setiap `SKILL.md` mendefinisikan metadata `name` dan `description`, tujuan, kondisi penggunaan, ruang lingkup, workflow, batasan, asumsi tools, format keluaran, dan kriteria penyelesaian. Folder `references/` disediakan untuk materi pendukung; isinya ditambahkan saat diperlukan. Folder `scripts/` dan `assets/` bersifat opsional.

## Siklus pengembangan

1. Identifikasi kebutuhan, pengguna, dan trigger.
2. Tetapkan scope, non-goals, input, dan output.
3. Rancang workflow dan batas kemampuan.
4. Tulis instruksi dan referensi yang diperlukan.
5. Uji skenario normal, ambigu, input tidak lengkap, dan kegagalan.
6. Audit konsistensi, keamanan, dan asumsi tools.
7. Catat perubahan dan keterbatasan.

## Status

Enam direktori Skill dan definisi awalnya dibuat sebagai baseline katalog. Dokumen ini tidak menyatakan bahwa Skill telah diuji pada semua platform atau production-ready. Validasi lanjutan dan penyempurnaan dapat dilakukan per Skill.
