# User Guide — Creative Design & Game Development Studio

Panduan ini menjelaskan cara menggunakan skill **Creative Design & Game Development Studio** agar AI dapat membantu menghasilkan pekerjaan kreatif dan digital yang terarah, konsisten, dapat diuji, dan siap digunakan.

> **Status:** Panduan penggunaan. Validasi resmi dengan `skills-ref validate` belum dilakukan. Panduan ini tidak menyatakan bahwa paket telah lolos validasi teknis.

## 1. Pahami fungsi skill

Skill ini adalah seperangkat instruksi kerja untuk membantu agen AI menangani tujuh disiplin:

1. Graphic Design & Branding
2. Illustration & 3D
3. UI/UX Design
4. Game Design & Development
5. Interactive Learning
6. Web & Application Development
7. Motion, Animation & Video

**Creative Direction** mengarahkan proses lintas disiplin. Skill ini bukan aplikasi desain, mesin game, atau pengganti perangkat lunak produksi. Skill membantu agen merencanakan, membuat, meninjau, mengintegrasikan, dan mendokumentasikan pekerjaan menggunakan alat yang tersedia.

## 2. Pasang dan aktifkan skill

Ikuti mekanisme instalasi yang didukung oleh platform/agen AI yang digunakan. Secara umum:

1. Buka repositori: https://github.com/khusnajulidar/creative-design-game-development
2. Pastikan agen/platform mendukung format skill yang digunakan.
3. Ikuti petunjuk impor atau instalasi dari platform tersebut. Jangan menganggap menempelkan URL repositori otomatis memasang skill.
4. Jika platform meminta folder atau berkas skill, berikan paket skill sesuai struktur repositori dan pastikan `SKILL.md` berada di lokasi yang dikenali.
5. Aktifkan atau pilih skill sesuai mekanisme platform.
6. Mulai percakapan baru atau muat ulang konteks bila platform mensyaratkannya.
7. Minta agen menyatakan apakah skill berhasil dimuat dan apa keterbatasan aksesnya. Jangan anggap aktif hanya karena file sudah diunggah.

Nama menu dan langkah instalasi dapat berbeda antarplatform. Rujuk dokumentasi resmi platform yang digunakan.

## 3. Mulai dengan brief yang jelas

Untuk pekerjaan baru, jangan hanya menulis “buatkan game bagus” atau “desainkan poster menarik”. Berikan konteks yang cukup agar agen dapat mengambil keputusan profesional.

Sampaikan hal-hal berikut jika relevan:

- **Tujuan:** hasil apa yang ingin dicapai?
- **Pengguna sasaran:** siapa yang akan memakai atau melihat hasilnya?
- **Produk dan platform:** poster cetak, media sosial, web, Android, desktop, game browser, video, dan sebagainya.
- **Ruang lingkup:** apa yang termasuk dan tidak termasuk?
- **Gaya dan referensi:** contoh visual, merek, suasana, atau pengalaman yang diinginkan.
- **Konten:** teks, data, materi, bahasa, sumber, dan aset yang harus dipakai.
- **Fungsi:** fitur, alur, interaksi, aturan, dan perilaku yang diharapkan.
- **Batasan:** ukuran, anggaran, waktu, perangkat, teknologi, lisensi, aksesibilitas, atau aturan khusus.
- **Keluaran:** file final, kode sumber, aset, dokumentasi, atau integrasi yang dibutuhkan.
- **Kriteria selesai:** bagaimana pengguna akan menilai hasilnya benar?

Tidak semua proyek membutuhkan semua detail. Jika informasi penting belum ada, minta agen mengajukan pertanyaan yang paling menentukan, bukan membanjiri pengguna dengan daftar pertanyaan.

Gunakan template [Project Brief](templates/project-brief.md) untuk proyek menengah atau besar.

## 4. Gunakan pola instruksi yang efektif

Instruksi yang baik menyebutkan tujuan, konteks, batasan, dan keluaran yang diharapkan. Contoh:

**Contoh singkat**
> Buat konsep identitas visual untuk produk edukasi anak usia 7–9 tahun. Karakter merek ceria, ramah, dan mudah dikenali. Hindari tampilan korporat yang kaku. Berikan satu konsep terbaik beserta alasan, palet warna, tipografi, penggunaan logo, dan contoh penerapan. Jangan membuat variasi tambahan sebelum konsep utama disetujui.

**Contoh untuk game**
> Rancang game edukasi browser untuk anak usia 8–10 tahun. Tujuan belajar: mengenali kosakata tertentu dan menggunakannya dalam konteks. Platform utama ponsel portrait, tetapi tetap harus nyaman di desktop. Jelaskan core loop, aturan, progres, sistem umpan balik, struktur level, layar utama, kebutuhan aset, dan kriteria penerimaan. Buat prototipe kecil yang dapat diuji sebelum memperluas konten.

**Contoh untuk revisi**
> Revisi hanya bagian navigasi level yang sudah kita sepakati. Pertahankan layout, warna, ukuran tombol, mekanika, dan seluruh fitur lain. Sebelum mengubah kode, tunjukkan file yang terdampak dan risiko regresi. Setelah revisi, uji navigasi level serta alur yang sudah berfungsi sebelumnya.

## 5. Manfaatkan alur kerja bertahap

Untuk proyek yang kompleks, minta agen bekerja melalui tahapan berikut:

1. **Discover** — memahami tujuan, pengguna, konteks, batasan, dan aset.
2. **Plan** — menyusun ruang lingkup, pendekatan, risiko, prioritas, dan kriteria penerimaan.
3. **Design** — membuat arah kreatif, spesifikasi, alur, dan rancangan.
4. **Produce** — membuat aset, konten, kode, atau prototipe.
5. **Integrate** — menyatukan komponen ke produk atau proyek utama.
6. **QA** — menguji kualitas visual, isi, fungsi, kompatibilitas, dan aksesibilitas sesuai kebutuhan.
7. **Refine** — memperbaiki temuan tanpa merusak bagian yang sudah benar.
8. **Deliver** — menyerahkan hasil, sumber, dokumentasi, status, dan langkah berikutnya.

Untuk pekerjaan kecil, tahapan dapat diringkas. Untuk game, aplikasi, atau produk kompleks, jangan melewati perencanaan, integrasi, dan QA.

## 6. Berikan referensi dan kelola aset dengan benar

Saat memberikan gambar, desain, kode, atau contoh:

- Jelaskan apakah referensi harus diikuti secara ketat atau hanya menjadi inspirasi.
- Tandai elemen yang wajib dipertahankan dan bagian yang boleh dieksplorasi.
- Sebutkan aset yang menjadi sumber utama (*source of truth*).
- Berikan nama file, lokasi, versi, ukuran, format, dan lisensi jika diketahui.
- Jangan menganggap agen dapat membuka tautan privat, akun, atau file lokal tanpa akses yang sesuai.
- Minta agen mengonfirmasi aset mana yang benar-benar dapat diakses sebelum menggunakannya.
- Jangan meminta penghapusan watermark atau penyalinan karya pihak lain tanpa hak.

Jika ada satu desain yang telah disetujui, nyatakan secara eksplisit bahwa desain tersebut menjadi acuan. Minta agen tidak mengubah elemen yang telah disetujui tanpa alasan dan persetujuan.

## 7. Bekerja dengan revisi yang terkendali

Saat meminta perubahan, tuliskan:

1. Bagian yang harus diubah.
2. Bagian yang harus dipertahankan.
3. Alasan perubahan.
4. Hasil yang diharapkan.
5. Cara memeriksa bahwa perubahan berhasil.

Minta agen mengidentifikasi file yang terdampak, menjaga salinan atau riwayat versi, dan melakukan pemeriksaan regresi yang proporsional. Hindari instruksi “perbaiki semuanya” jika yang dimaksud hanya satu bagian.

Untuk proyek yang menggunakan Git/GitHub, gunakan commit yang deskriptif dan catat alasan perubahan. Jangan menyatakan perubahan telah masuk ke repositori sebelum commit atau hasilnya diverifikasi.

## 8. Minta bukti, bukan sekadar klaim

Bedakan status berikut:

- **Designed** — rancangan telah dibuat.
- **Produced** — aset, konten, atau kode telah dibuat.
- **Integrated** — komponen telah dipasang ke produk/proyek.
- **Tested** — pengujian tertentu benar-benar dijalankan.
- **Verified** — hasil diperiksa terhadap kriteria yang ditentukan.
- **Released** — versi telah diterbitkan atau diserahkan untuk penggunaan.

Minta agen menyebutkan:
- apa yang diuji;
- lingkungan, perangkat, browser, atau ukuran layar yang digunakan;
- hasil yang berhasil dan gagal;
- bug atau risiko yang belum terselesaikan;
- bagian yang belum dapat diuji.

Tampilan yang terlihat bagus bukan bukti bahwa fungsi bekerja. Kode yang berhasil dibuat bukan bukti bahwa aplikasi telah diuji. Jangan menerima klaim “100% kompatibel” tanpa cakupan pengujian yang mendukungnya.

## 9. Gunakan dokumen proyek untuk menjaga kesinambungan

Untuk proyek yang berlanjut lintas sesi atau dikerjakan beberapa agen, simpan:

- brief dan spesifikasi yang disetujui;
- keputusan dan alasan;
- status pekerjaan;
- struktur file dan sumber aset;
- dependensi dan cara menjalankan proyek;
- hasil QA, masalah, dan risiko;
- riwayat perubahan;
- pekerjaan berikutnya dan hal yang menunggu persetujuan.

Gunakan template:
- [Design Specification](templates/design-specification.md)
- [QA Checklist](templates/qa-checklist.md)
- [Project Handoff](templates/handoff-document.md)

Di awal sesi lanjutan, minta agen membaca dokumentasi proyek dan memeriksa kondisi repositori terkini sebelum mengubah apa pun.

## 10. Berikan otonomi yang tepat

Skill ini dirancang dengan pendekatan **Professional Proactive**. Agen seharusnya dapat mengambil keputusan rutin, menyampaikan rekomendasi, mengantisipasi masalah, dan tidak sekadar menyetujui semua usulan.

Namun, tetapkan batas dengan jelas:
- keputusan rutin yang tidak mengubah arah boleh dikerjakan mandiri;
- perubahan besar pada konsep, identitas, arsitektur, mekanika inti, data, atau ruang lingkup perlu dibahas;
- tindakan destruktif, publikasi, pembelian, atau perubahan akses memerlukan izin eksplisit sesuai konteks;
- agen harus jujur jika alat, akses, atau kemampuan yang diperlukan tidak tersedia.

## 11. Skenario uji awal yang disarankan

Setelah skill berhasil dimuat, lakukan pengujian bertahap. Gunakan proyek contoh atau salinan, bukan langsung proyek produksi yang penting.

| Uji | Instruksi | Hal yang dinilai |
|---|---|---|
| Brief | Minta agen mengembangkan brief poster sederhana | Apakah tujuan, audiens, format, dan kriteria hasil dikenali? |
| Arah kreatif | Berikan referensi visual dan minta satu konsep terbaik | Apakah referensi diikuti sesuai instruksi? |
| UI/UX | Minta alur aplikasi sederhana | Apakah alur, keadaan, dan aksesibilitas dipikirkan? |
| Game | Minta rancangan satu level game | Apakah aturan, progres, umpan balik, dan kondisi menang jelas? |
| Revisi | Minta perubahan satu komponen tanpa mengubah lainnya | Apakah batas revisi dipatuhi? |
| QA | Minta checklist dan laporan pengujian | Apakah agen membedakan rencana uji dari uji yang benar-benar dijalankan? |
| Handoff | Minta ringkasan untuk agen/sesi berikutnya | Apakah keputusan, status, file, masalah, dan langkah berikutnya tercatat? |

Catat prompt, hasil, bagian yang sesuai, kesalahan, dan perbaikan yang diperlukan. Ulangi tes setelah perubahan instruksi agar dampaknya dapat dibandingkan.

## 12. Cara memberi umpan balik yang paling berguna

Hindari hanya mengatakan “bagus”, “kurang bagus”, atau “belum sesuai”. Jelaskan perbedaan antara hasil dan harapan.

Contoh:
> Hasil ini belum sesuai karena tombol utama terlalu kecil untuk layar ponsel. Pertahankan warna, bentuk kartu, dan susunan konten. Perbesar area sentuh tombol, pastikan jarak antar tombol cukup, lalu periksa ulang pada lebar layar 360 px.

Umpan balik spesifik membantu agen memperbaiki masalah tanpa menafsirkan ulang seluruh desain.

## 13. Batasan dan tanggung jawab pengguna

Skill meningkatkan konsistensi proses, tetapi tidak menjamin hasil sempurna atau menggantikan penilaian manusia. Pengguna tetap perlu memeriksa fakta, hak penggunaan aset, keamanan, privasi, materi sensitif, dan kesesuaian hasil dengan kebutuhan nyata. Untuk materi profesional, pendidikan, keagamaan, hukum, kesehatan, atau domain berisiko tinggi, tetapkan sumber otoritatif dan lakukan pemeriksaan ahli yang sesuai.

Ketersediaan fitur juga bergantung pada platform, model, alat, koneksi, izin, dan file yang benar-benar dapat diakses.

## 14. Prompt pembuka yang dapat digunakan

Salin dan sesuaikan prompt berikut setelah skill dimuat:

> Gunakan skill Creative Design & Game Development Studio untuk membantu proyek ini. Sebelum mulai, identifikasi disiplin yang relevan dan baca pedoman yang sesuai. Bantu saya melalui alur Discover, Plan, Design, Produce, Integrate, QA, Refine, dan Deliver sesuai skala proyek. Bersikap proaktif dalam keputusan rutin, tetapi minta persetujuan untuk perubahan besar atau tindakan berisiko. Pertahankan semua keputusan dan bagian yang telah disetujui. Jangan mengklaim file telah diubah, fitur telah terintegrasi, atau tes telah berhasil kecuali benar-benar dilakukan dan dapat diverifikasi. Mulailah dengan memahami brief dan ajukan hanya pertanyaan yang paling penting.

---

**Prinsip penggunaan terbaik:** berikan konteks dan referensi yang jelas, tetapkan batas perubahan, minta hasil nyata, dan selalu minta bukti pengujian. Skill ini akan paling bermanfaat ketika dipakai sebagai mitra kerja kreatif dan teknis yang menjaga kualitas serta kesinambungan proyek, bukan sekadar generator ide.
