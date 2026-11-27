# Workflow, QA & Templates v2.0 

> Status: APPROVED v2.0 — authorized by the user for adoption in the Creative Design & Game Development Studio Project.
> Apply the workflow proportionally. Not every task needs every artifact or stage at full depth.

## 1. Workflow adaptif

1. **Discover** — tujuan, audiens, konteks, platform, constraint, referensi, aset, asumsi, dan kriteria sukses. Validasi brief; tandai informasi yang belum diketahui.
2. **Plan** — ruang lingkup, deliverable, dependensi, risiko, prioritas, tool, jadwal/milestone bila relevan, dan acceptance criteria.
3. **Design** — konsep, struktur, sistem visual, flow, interaksi, spesifikasi, dan rationale keputusan penting.
4. **Produce** — aset, konten, kode, scene, layout, dan media; kelola source/master, versi, dan provenance.
5. **Integrate** — gabungkan dalam produk/lingkungan target; periksa kontrak antarkomponen, kompatibilitas, dan konfigurasi.
6. **QA** — jalankan pemeriksaan proporsional terhadap risiko dan acceptance criteria; simpan bukti.
7. **Refine** — perbaiki temuan, jaga elemen yang disetujui, lakukan regression check, dan catat perubahan.
8. **Deliver** — serahkan hasil, instruksi, status, batasan, dokumentasi, dan handoff; lakukan release bila memang termasuk ruang lingkup.

Tahapan dapat berulang. Untuk tugas sederhana, gabungkan tahap yang sesuai. Jangan menghilangkan pemeriksaan penting hanya demi mengikuti urutan secara formal.

## 2. Project planning & risk register

Pada tahap Plan, identifikasi risiko berdasarkan kemungkinan, dampak, keterpulihan, dan komponen/pengguna terdampak. Gunakan tabel ringkas:

| ID | Risiko/asumsi | Kemungkinan | Dampak | Mitigasi/pemilik | Status |
|---|---|---|---|---|---|

Prioritaskan pekerjaan berdasarkan nilai bagi pengguna, urgensi, dependensi, risiko, dan biaya perubahan. Estimasi harus menyatakan asumsi dan rentang ketidakpastian bila informasi belum cukup.

## 3. Tingkat QA

### Basic
Untuk aset statis dan risiko rendah: ejaan/konten, dimensi, alignment, kontras, keterbacaan, export, dan cacat visual. Periksa juga kesesuaian brief, referensi, dan lisensi bila relevan.

### Advanced
Untuk produk interaktif/multimedia: semua Basic ditambah behavior, navigasi, media, state, input, feedback, responsive behavior, aksesibilitas relevan, dan pemeriksaan lintas perangkat.

### Comprehensive
Untuk game, website, dan aplikasi kompleks: requirement traceability, integration, regression, accessibility, performance, security/privacy, compatibility, backup/restore, dan release readiness sesuai relevansi.

Catat ruang lingkup test, environment/perangkat/browser/versi, langkah, data uji, hasil aktual, bukti, defect, keterbatasan, dan risiko tersisa. Jangan menyatakan lulus jika belum dijalankan. QA level bukan label gengsi; pilih berdasarkan risiko dan kebutuhan.

## 4. Test case & requirement traceability

Gunakan test case untuk fitur atau persyaratan yang perlu bukti terstruktur.

| Field | Keterangan |
|---|---|
| Test ID | Identitas unik pengujian |
| Requirement ID | Persyaratan/acceptance criterion yang diuji |
| Preconditions | Kondisi awal dan data yang diperlukan |
| Test steps | Langkah yang dijalankan |
| Expected result | Hasil yang diharapkan |
| Actual result | Hasil yang diamati |
| Status | Pass / Fail / Blocked / Not tested |
| Evidence | Screenshot, log, video, output, atau referensi bukti |
| Environment | Perangkat, browser, OS, build, atau versi terkait |

Satu requirement dapat memiliki beberapa test case. Requirement yang belum diuji harus tetap terlihat sebagai belum diuji, bukan diasumsikan lulus.

## 5. Defect classification & triage

| Severity | Definisi umum | Respons |
|---|---|---|
| Critical | Produk/fitur inti tidak dapat digunakan, kehilangan/kerusakan data serius, atau risiko keamanan/keselamatan serius | Hentikan release terkait; eskalasi segera |
| High | Fungsi utama gagal atau hasil sangat menyimpang tanpa workaround yang layak | Prioritaskan sebelum release |
| Medium | Fungsi terganggu tetapi ada workaround; dampak terbatas | Jadwalkan perbaikan berdasarkan prioritas |
| Low | Kekurangan minor yang tidak menghalangi penggunaan utama | Perbaiki sesuai kapasitas/prioritas |

Severity menjelaskan dampak; priority menjelaskan urutan penanganan. Catat langkah reproduksi, expected/actual result, environment, bukti, frekuensi, dan workaround. Jangan menutup defect tanpa verifikasi perbaikan atau alasan penutupan.

## 6. Regression & change control

Sebelum perubahan besar, catat baseline: versi/commit, perilaku yang sudah benar, aset, keputusan yang disetujui, dan test yang relevan. Ubah bagian yang diminta saja. Setelah perubahan:
- Periksa fungsi yang diubah.
- Periksa dependensi dan alur yang mungkin terdampak.
- Jalankan regression test yang proporsional.
- Perbarui test evidence, changelog, dan decision log.
- Catat defect baru dan risiko tersisa.

Perubahan ruang lingkup, identitas, fitur yang disetujui, arsitektur utama, biaya, data, keamanan, atau publikasi memerlukan persetujuan sesuai tingkat risikonya.

## 7. Release & deployment management

Jika release/deployment termasuk ruang lingkup, periksa:
- Versi, build, environment, konfigurasi, dan dependency.
- Acceptance criteria dan test penting.
- Kelengkapan aset, konten, metadata, dan dokumentasi.
- Keamanan, privasi, lisensi, dan akses sesuai relevansi.
- Backup/snapshot serta prosedur restore/rollback.
- Release notes, known issues, dan komunikasi pengguna.
- Monitoring pascarilis bila tersedia dan sesuai kebutuhan.

Jangan menyebut Released/Deployed sampai tindakan benar-benar berhasil. Jika rollback tidak tersedia, nyatakan keterbatasan dan mitigasi sebelum release berisiko.

## 8. Versioning & asset management

Gunakan version control untuk source dan dokumen bila sesuai. Tetapkan konvensi nama yang konsisten, misalnya `nama-aset_konteks_vMajor.Minor.ext` atau konvensi proyek yang sudah berlaku.

Pisahkan bila relevan:
- Source/master/editable files.
- Export/final files.
- Preview/proxy.
- Referensi dan sumber eksternal.
- Build/release artifacts.
- Test evidence.

Jangan membuat duplikat final yang membingungkan. Catat sumber, lisensi, perubahan, versi, dan dependensi aset. Backup harus memiliki cakupan dan cara pemulihan yang jelas; backup belum dianggap teruji sampai restore diperiksa.

## 9. Template Project Brief

- Nama proyek:
- Tujuan utama:
- Audiens/pengguna:
- Masalah/kebutuhan:
- Platform/medium:
- Deliverable:
- Ruang lingkup dan yang tidak termasuk:
- Referensi dan elemen wajib dipertahankan:
- Batasan/larangan:
- Aset dan materi tersedia:
- Kriteria keberhasilan/acceptance criteria:
- Tenggat/milestone/dependensi:
- Asumsi dan risiko awal:
- Hal yang belum diputuskan:
- Pihak/persetujuan yang diperlukan:

## 10. Template Design Specification

- Nama/versi:
- Tujuan dan audiens:
- Creative direction dan rationale:
- Requirement/acceptance criteria:
- Struktur/flow:
- Sistem visual:
- Komponen dan perilaku:
- State dan error recovery:
- Konten/data:
- Responsive/accessibility:
- Persyaratan teknis/platform:
- Aset, format, dan dependensi:
- Risiko dan mitigasi:
- Hal yang tidak termasuk ruang lingkup:
- Persetujuan/versi acuan:

## 11. Template QA Checklist

- [ ] Persyaratan dan acceptance criteria jelas.
- [ ] Konten/data benar dan lengkap sesuai sumber yang ditetapkan.
- [ ] Visual sesuai brief dan referensi.
- [ ] Layout, hierarki, dan keterbacaan baik.
- [ ] Interaksi, navigasi, dan state bekerja.
- [ ] Responsif pada target perangkat.
- [ ] Aksesibilitas relevan diperiksa.
- [ ] Performa dan kompatibilitas diperiksa bila relevan.
- [ ] Lisensi, privasi, dan keamanan diperiksa bila relevan.
- [ ] Integration dan regression check dilakukan sesuai dampak perubahan.
- [ ] Temuan, bukti, keterbatasan, dan risiko tersisa dicatat.

Hasil QA: Pass / Pass with issues / Fail / Not tested.
Environment dan ruang lingkup:
Test case/evidence:
Defect dan severity:
Risiko tersisa:
Pemeriksa/tanggal:

## 12. Template Handoff

- Ringkasan hasil:
- File/lokasi/tautan:
- Versi/commit:
- Tujuan dan ruang lingkup:
- Yang sudah Designed:
- Yang sudah Produced:
- Yang sudah Integrated:
- Yang sudah Tested:
- Yang sudah Verified:
- Yang sudah Released:
- Acceptance criteria dan status:
- Cara menggunakan/build:
- Keputusan yang disetujui:
- Isu/keterbatasan/known issues:
- Dependensi dan lisensi:
- Hasil QA dan bukti:
- Langkah berikutnya:
- Persetujuan yang masih diperlukan:

## 13. Template Session & Project Continuity Log

- Nama proyek:
- Tanggal/sesi:
- Source of truth (repository/folder/dokumen):
- Branch/versi/commit terakhir yang diperiksa:
- Tujuan dan ruang lingkup saat ini:
- Keputusan yang telah disetujui:
- Referensi/aset wajib dipertahankan:
- Pekerjaan selesai:
- Pekerjaan yang sedang berlangsung:
- Masalah/defect terbuka:
- Hasil QA terakhir dan bukti:
- Perubahan sejak sesi sebelumnya:
- File/komponen terdampak:
- Risiko/dependensi:
- Langkah berikutnya:
- Persetujuan yang dibutuhkan:
- Hal yang belum diverifikasi:

Gunakan log ini sebagai ringkasan operasional, bukan pengganti source code, repository, atau dokumen proyek yang menjadi sumber kebenaran.

## 14. Perubahan dan kontinuitas

Sebelum revisi besar, catat kondisi awal dan versi. Ubah bagian yang diminta saja. Setelah revisi, periksa dampaknya terhadap komponen terkait. Perbarui changelog/decision log bila proyek berkelanjutan.

Untuk melanjutkan proyek:
1. Periksa sumber proyek aktual yang tersedia.
2. Pastikan versi/commit dan status file.
3. Cocokkan catatan kontinuitas dengan kondisi aktual.
4. Identifikasi perubahan yang belum tersimpan atau konflik.
5. Lanjutkan dari baseline yang benar; jangan mengandalkan ingatan percakapan semata.
6. Catat hasil dan status sebenarnya setelah pekerjaan.

## 15. Status pekerjaan

- **Designed:** rancangan tersedia.
- **Produced:** aset/komponen telah dibuat.
- **Integrated:** telah dimasukkan ke produk sasaran.
- **Tested:** pengujian yang disebutkan benar-benar dijalankan.
- **Verified:** bukti mendukung persyaratan tertentu.
- **Released:** rilis/publikasi berhasil dilakukan.

Status QA keseluruhan: Pass / Pass with issues / Fail / Not tested. Status harus menyebutkan cakupan; satu test yang lulus tidak membuktikan seluruh produk lulus.