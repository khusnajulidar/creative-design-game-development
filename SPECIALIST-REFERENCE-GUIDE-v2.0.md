# Specialist Reference Guide v2.0 

> Status: APPROVED v2.0 — authorized by the user for adoption in the Creative Design & Game Development Studio Project.
> Use only disciplines relevant to the task. For multi-disciplinary projects, coordinate their outputs as one coherent experience. Creative Direction is cross-cutting, not an additional specialist discipline.

## 1. Creative Direction (cross-cutting)

Tetapkan tujuan komunikasi/pengalaman, audiens, positioning, pesan utama, konsep, mood, hierarki, medium, dan kriteria keberhasilan. Pastikan keputusan visual, interaksi, konten, dan teknis saling mendukung. Hindari dekorasi yang tidak punya fungsi.

Tambahan standar:
- Validasi brief: bedakan kebutuhan, preferensi, constraint, asumsi, dan hal yang belum diputuskan.
- Tetapkan creative direction dan design principles yang dapat dipakai lintas deliverable.
- Catat rationale untuk keputusan penting dan elemen referensi yang wajib dipertahankan.
- Evaluasi konsistensi hasil terhadap tujuan, audiens, merek, dan platform.
- Kelola perubahan konsep melalui change control; jangan mengubah arah yang disetujui secara diam-diam.

Output yang lazim: creative brief, moodboard/reference analysis, concept direction, design rationale, creative review, dan acceptance criteria.

## 2. Graphic Design & Branding

Periksa strategi merek, audiens, diferensiasi, pesan, identitas visual, logo, warna, tipografi, grid, hierarki, komposisi, konsistensi, keterbacaan, dan adaptasi lintas media. Pastikan output punya ukuran, format, resolusi, mode warna, bleed/safe area bila untuk cetak, dan file final yang sesuai kebutuhan. Bedakan master editable dan export final.

Tambahan standar:
- Kelola font, plugin, template, foto, ilustrasi, dan aset pihak ketiga beserta sumber dan lisensinya.
- Periksa keterbacaan, kontras, safe area, crop, dan konsistensi pada ukuran penggunaan nyata.
- Tentukan spesifikasi export: dimensi, rasio, format, profil warna, transparansi, kompresi, bleed, dan toleransi cetak bila relevan.
- Jaga file master tetap terstruktur; gunakan penamaan versi yang jelas dan hindari duplikasi membingungkan.
- Siapkan handoff yang menyertakan linked assets, font/licensing notes, dan panduan penggunaan bila dibutuhkan.

Pemeriksaan khusus: font missing, link aset rusak, transparansi, clipping, rasterisasi, overprint/bleed, dan kualitas export.

## 3. Illustration & 3D

Tentukan gaya, siluet, proporsi, material, pencahayaan, kamera, perspektif, lingkungan, detail, dan konsistensi antar-aset. Periksa anatomi/stylization, clipping, artefak, tekstur, UV/material bila relevan, polygon/performance untuk real-time, serta resolusi render. Ikuti batasan karakter atau representasi khusus yang tercantum dalam brief proyek; jangan menggeneralisasikannya.

Tambahan standar:
- Tentukan asset specification: ukuran, skala, pivot/origin, orientasi, naming, format, channel, dan target platform.
- Pisahkan source/master asset dari export/optimized asset.
- Untuk real-time, evaluasi polygon/triangle budget, texture size, material count, draw calls, LOD, collider, dan memory sesuai target.
- Untuk 2D, periksa alpha/transparency, edge artifacts, slicing, sprite dimensions, dan consistency antar-frame bila relevan.
- Catat asal, lisensi, hak modifikasi, dan batas redistribusi aset eksternal atau generatif.
- Pastikan aset dapat dipakai oleh pipeline implementasi tanpa kehilangan kualitas atau metadata penting.

## 4. UI/UX Design

Mulai dari kebutuhan pengguna, konteks, tugas utama, dan hambatan. Petakan information architecture, user flow, wireframe, state, feedback, error recovery, responsive behavior, dan design system. Periksa affordance, konsistensi, navigasi, kontras, ukuran target sentuh, keyboard access, screen reader semantics, dan empty/loading/error/success states. Jangan menganggap mockup sebagai implementasi yang sudah berfungsi.

Tambahan standar:
- Rumuskan hipotesis usability dan tugas utama yang perlu diselesaikan pengguna.
- Lakukan heuristic review atau usability testing yang proporsional; catat metode, peserta/konteks, temuan, dan keterbatasan.
- Periksa alur utama, alur alternatif, validasi input, pencegahan kesalahan, recovery, dan feedback.
- Periksa responsive breakpoints, orientation, zoom, keyboard-only navigation, focus order, labels, semantics, dan reduced motion bila relevan.
- Siapkan design-to-development handoff: komponen, token, ukuran, state, behavior, responsive rules, aset, dan acceptance criteria.
- Bedakan fidelity mockup/prototype dengan implementasi produksi.

## 5. Game Design & Development

Definisikan target pemain, fantasy/tema, core loop, mekanik, aturan, kontrol, feedback, progression, tingkat kesulitan, balancing, konten, reward, onboarding, dan kondisi menang/kalah. Periksa game state, save/progress, input, responsivitas, performa, audio/visual feedback, edge cases, dan perilaku pada perangkat target. Uji permainan nyata, bukan hanya tampilan statis.

Tambahan standar:
- Dokumentasikan game loop, state diagram/transition, rules, controls, scoring, progression, reward, fail/retry, pause/resume, dan reset.
- Uji state transition, boundary values, input berulang/bersamaan, invalid input, interruption, reload, dan recovery.
- Periksa integritas save/progress, migration bila ada, serta perilaku offline/online sesuai desain.
- Lakukan playtesting berbasis skenario; catat tujuan, perangkat, temuan, dan keterbatasan. Jangan menyamakan developer self-test dengan validasi pemain.
- Balancing didasarkan pada data playtest atau alasan desain yang terdokumentasi; hindari klaim seimbang tanpa bukti.
- Evaluasi onboarding, kesulitan, pacing, kejelasan feedback, aksesibilitas, dan potensi frustrasi.
- Analytics/telemetry bersifat opsional dan harus proporsional; kumpulkan data minimum, transparan, dan dengan dasar/izin yang sesuai.
- Periksa performa, memory, frame rate, loading, audio, input latency, dan compatibility pada perangkat sasaran.

## 6. Interactive Learning

Mulai dari capaian belajar, usia/kemampuan sasaran, prasyarat, dan bukti penguasaan. Selaraskan tujuan, materi, aktivitas, latihan, feedback, dan asesmen. Pastikan jawaban benar, distraktor, urutan, tingkat kesulitan, dan umpan balik akurat secara materi. Hindari interaksi yang hanya dekoratif. Pertimbangkan aksesibilitas, beban kognitif, pengulangan bermakna, dan motivasi yang sehat.

Tambahan standar:
- Rumuskan learning outcomes dengan perilaku atau bukti yang dapat diamati.
- Petakan alignment antara outcome, materi, aktivitas, feedback, dan assessment.
- Validasi kunci jawaban, distraktor, pembahasan, urutan, tingkat kesulitan, dan kemungkinan ambiguitas.
- Bedakan content validation, instructional validation, dan evidence of learning.
- Gunakan pre/post check, rubric, mastery criteria, atau metode lain bila sesuai; jangan mengklaim efektivitas tanpa data yang memadai.
- Sesuaikan bahasa, beban kognitif, durasi, aksesibilitas, dan bentuk interaksi dengan usia serta kemampuan.
- Untuk materi domain khusus, tetapkan sumber rujukan, tanggal/versi bila relevan, dan pemeriksa yang kompeten. Tandai hal yang belum dapat diverifikasi.
- Gunakan reward untuk mendukung motivasi, bukan menggantikan tujuan belajar atau mendorong perilaku tidak sehat.

## 7. Web & Application Development

Ubah kebutuhan menjadi requirement dan acceptance criteria. Rancang arsitektur, struktur data, state, komponen, API, autentikasi/otorisasi, error handling, logging, deployment, dan strategi backup sesuai skala. Perhatikan keamanan, privasi, validasi input, performa, maintainability, kompatibilitas browser/perangkat, dan aksesibilitas. Jalankan test/build yang relevan dan laporkan hasil sebenarnya.

Tambahan standar:
- Pisahkan environment development, staging, dan production bila skala/risiko membutuhkannya.
- Kelola konfigurasi dan secrets secara aman; jangan commit credential.
- Gunakan automated tests, linting, type checks, build checks, dan dependency/security checks sesuai stack.
- CI/CD diterapkan bila memberi manfaat; pipeline harus memiliki pemeriksaan dan kontrol yang sesuai.
- Siapkan backup, restore verification, migration plan, rollback, dan release notes sesuai risiko.
- Periksa API contract, error handling, logging tanpa membocorkan data sensitif, authorization boundaries, dan rate/resource limits bila relevan.
- Dokumentasikan browser/perangkat yang diuji, versi, environment, hasil, dan batasan.
- Jangan menyebut deployed/released tanpa bukti tindakan berhasil.

## 8. Motion, Animation & Video

Tentukan tujuan, durasi, format, platform, rasio aspek, frame rate, storyboard, pacing, transisi, tipografi, audio, caption, dan safe area. Jaga konsistensi visual, timing, sinkronisasi, keterbacaan, loudness, dan kualitas export. Periksa format codec/container dan spesifikasi distribusi.

Tambahan standar:
- Kelola project file, source media, proxy, cache, font, audio, dan linked assets secara terstruktur.
- Pisahkan master project, master render, dan distribution export.
- Tentukan codec, container, bitrate, resolution, frame rate, color space, audio sample rate, loudness target, subtitle/caption format, dan platform preset bila relevan.
- Periksa frame drop, flicker, clipping, aliasing, audio peak, sync, caption timing, safe area, dan playback pada target.
- Pastikan lisensi musik, footage, font, voice, dan aset lain sesuai penggunaan serta distribusi.
- Catat versi final dan perubahan penting.

## 9. Integrasi lintas disiplin

- Pastikan brand, ilustrasi, UI, dan motion memakai sistem visual yang konsisten.
- Pastikan desain game mendukung tujuan pembelajaran jika produk bersifat edukatif.
- Pastikan spesifikasi desain dapat diterjemahkan menjadi implementasi.
- Pastikan QA memeriksa baik kualitas tiap komponen maupun pengalaman end-to-end.
- Tetapkan format, ukuran, naming, metadata, state, dan acceptance criteria pada handoff antardisiplin.
- Kelola dependensi dan perubahan: perubahan satu komponen harus dievaluasi terhadap komponen lain yang terdampak.
- Jangan menganggap keberhasilan komponen secara individual otomatis berarti pengalaman produk secara keseluruhan berhasil.

## 10. Domain-specific validation

Untuk proyek dengan materi khusus, gunakan proses verifikasi sesuai domain dan tingkat risikonya:
- Tetapkan sumber primer/otoritatif dan standar rujukan yang relevan.
- Catat klaim atau konten yang perlu diverifikasi.
- Bedakan fakta sumber, interpretasi, penyederhanaan pedagogis, dan keputusan desain.
- Libatkan pemeriksa kompeten bila diperlukan dan tersedia.
- Catat versi/tanggal sumber serta isu yang belum terselesaikan.
- Jangan mengklaim validasi ahli atau otoritas bila tidak dilakukan.

## 11. Specialist handoff minimum

Setiap handoff antardisiplin setidaknya memuat:
- Tujuan dan konteks penggunaan.
- File master dan export yang relevan.
- Format, dimensi, resolusi, skala, dan platform.
- Naming/version dan dependensi.
- Elemen yang wajib dipertahankan.
- State/perilaku bila aset interaktif.
- Lisensi/sumber dan batas penggunaan.
- Acceptance criteria dan pemeriksaan yang sudah dilakukan.
- Keterbatasan serta isu terbuka.