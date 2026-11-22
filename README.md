# AI Agent Skills Repository

Repositori ini menjadi tempat pengembangan, pemeliharaan, dan dokumentasi **AI Agent Skills** yang modular, reusable, dan dapat dipelihara dalam jangka panjang.

> **Status:** Inisialisasi repository  
> **Branch utama:** `main`  
> **Dokumen ini:** README v0.1.0

## Tujuan

Repository ini bertujuan untuk:

- Mengorganisasi kumpulan AI Agent Skills dalam satu struktur yang konsisten.
- Menyediakan standar untuk merancang, menulis, menguji, dan memelihara Skill.
- Menjaga instruksi Skill agar jelas, operasional, dan tidak saling bertentangan.
- Mengelola dokumentasi, referensi, serta dependensi setiap Skill.
- Memudahkan audit kualitas dan pengembangan Skill secara bertahap.

## Ruang Lingkup

Repository ini berfokus pada siklus hidup Skill:

1. Perencanaan kebutuhan dan ruang lingkup.
2. Perancangan arsitektur Skill.
3. Penulisan instruksi utama dan materi pendukung.
4. Pengelolaan dependensi dan referensi.
5. Validasi struktur serta kualitas instruksi.
6. Pemeliharaan, versioning, dan audit perubahan.

Repository ini tidak mengasumsikan bahwa seluruh standar atau struktur direktori telah ditetapkan. Kontrak dan aturan bersama akan didefinisikan secara bertahap sebelum diterapkan secara luas.

## Prinsip Pengembangan

- **Architecture before implementation** — tetapkan tujuan, batasan, dan kontrak sebelum implementasi.
- **Single source of truth** — hindari definisi yang sama tersebar tanpa sumber otoritatif.
- **Modularity** — pisahkan Skill dan dokumentasi berdasarkan tanggung jawab yang jelas.
- **Explicit dependencies** — nyatakan hubungan dan kebutuhan antarberkas secara eksplisit.
- **Consistency** — gunakan konvensi penamaan, struktur, dan format yang konsisten.
- **Verifiability** — setiap aturan penting harus dapat diperiksa.
- **Maintainability** — perubahan harus dapat ditelusuri dan tidak merusak kontrak yang sudah disepakati.

## Komponen Repository

Komponen berikut merupakan cakupan konseptual yang akan ditata lebih lanjut:

| Komponen | Tanggung jawab |
|---|---|
| Repository Architecture | Struktur direktori dan organisasi repository |
| Skill Definitions | Instruksi utama untuk setiap Skill |
| References | Panduan dan materi pendukung |
| Contracts & Standards | Kontrak format, metadata, dan aturan penulisan |
| Dependency Management | Pemetaan dependensi antarberkas |
| Validation & QA | Checklist, pemeriksaan, dan audit kualitas |
| Governance | Versioning dan pengelolaan perubahan |

## Struktur Direktori

Struktur direktori final belum ditetapkan. Struktur akan dirancang setelah inventaris kebutuhan, jenis dokumen, dan hubungan dependensi ditinjau.

Setiap usulan struktur harus menjelaskan:

- Tujuan setiap direktori.
- Jenis berkas yang boleh ditempatkan di dalamnya.
- Batas tanggung jawab dan kepemilikan dokumen.
- Hubungan dengan komponen repository lainnya.

## Standar Setiap Skill

Setiap Skill yang ditambahkan ke repository nantinya harus memiliki kontrak yang menjelaskan sekurang-kurangnya:

- Identitas dan tujuan Skill.
- Ruang lingkup serta batasan.
- Kondisi penggunaan dan pemicu yang relevan.
- Instruksi operasional.
- Dependensi dan referensi pendukung.
- Aturan keluaran dan perilaku yang diharapkan.
- Kriteria validasi dan pemeliharaan.

Rincian format dan field wajib akan ditetapkan dalam **Skill Contract** tersendiri. README ini tidak menggantikan kontrak tersebut.

## Alur Kerja

Alur pengembangan yang direncanakan:

1. Inspeksi repository dan kebutuhan.
2. Analisis requirement.
3. Perancangan arsitektur dan kontrak.
4. Persetujuan desain.
5. Implementasi Skill dan dokumentasi.
6. Audit silang dan validasi.
7. Pencatatan perubahan dan pemeliharaan.

Perubahan arsitektur atau kontrak yang berdampak luas harus ditinjau sebelum diterapkan.

## Quality Standards

Sebelum dinyatakan siap, setiap Skill perlu diperiksa terhadap kriteria berikut:

- Tujuan dan ruang lingkup tidak ambigu.
- Instruksi dapat dijalankan dan tidak saling bertentangan.
- Input, proses, dan keluaran dijelaskan sesuai kebutuhan.
- Referensi dan dependensi tersedia serta relevan.
- Tidak ada duplikasi yang tidak diperlukan.
- Struktur dan format memenuhi kontrak yang berlaku.
- Perubahan kompatibel dengan dokumen atau Skill yang bergantung padanya.

## Kontribusi dan Perubahan

Pengembangan repository dilakukan secara bertahap dan berbasis kontrak. Sebelum mengubah dokumen yang sudah menjadi acuan:

1. Periksa sumber kebenaran dan dependensinya.
2. Identifikasi dampak perubahan.
3. Pertahankan keputusan yang telah disetujui.
4. Perbarui dokumentasi terkait.
5. Lakukan validasi silang.

## Status Pengembangan

Repository berada pada tahap inisialisasi. Prioritas berikutnya adalah:

- [ ] Audit kebutuhan dan rancangan repository.
- [ ] Menetapkan Repository Architecture.
- [ ] Menetapkan Skill Contract.
- [ ] Menetapkan Documentation Contract.
- [ ] Menetapkan Dependency Management.
- [ ] Menetapkan standar validasi dan QA.
- [ ] Menetapkan governance dan versioning.

Checklist ini menunjukkan pekerjaan yang direncanakan, bukan klaim bahwa standar tersebut sudah tersedia atau diterapkan.

---

README ini merupakan titik awal dokumentasi repository dan akan diperbarui seiring disetujuinya arsitektur serta kontrak repository.
