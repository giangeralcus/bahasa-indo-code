---
name: bahasa-indo-code
description: "Use for ANY writing task done in Bahasa Indonesia: README, dokumentasi, commit message, komentar kode, PR description, UI copy, konten produk, chat kerja. Produces natural Indonesian developer writing — correct EYD V, consistent register, proper handling of English tech terms, zero AI-slop patterns. Triggers on 'tulis', 'buat README', 'buat dokumentasi', 'translate', 'bahasa Indonesia', 'write in Indonesian', or any Indonesian-language writing task. Companion skill: lazy-writing (global EN+ID anti-slop)."
---

# Bahasa Indo Code

Nulis dalam Bahasa Indonesia untuk kerjaan dev — README, commit, komentar kode, docs, UI copy — yang kedengeran kayak manusia Indonesia beneran, bukan hasil translate robot.

Masalah yang diselesaikan: teks AI berbahasa Indonesia itu gampang kebongkar. Ada tiga jenisnya: (1) terjemahan kaku ("mari kita menyelami"), (2) slop gaya konten-marketing ("Di era digital yang serba cepat ini"), (3) campur register sembarangan ("gue" nyampur "Anda" dalam satu halaman). Skill ini ngebunuh ketiganya.

## Test Lazy (sama kayak lazy-writing)

Tanya per kalimat: **"kalau gw hapus, apa yang hilang?"** Jawabannya nggak ada → hapus. Kalimatnya masih kepanjangan → potong.

## Aturan Inti

**1. Pilih ragam, konsisten sampai selesai.**
- Ragam **baku**: README, docs publik, laporan kerja, UI copy. Kamu/Anda netral, tanpa slang.
- Ragam **santai**: chat internal, konten komunitas. Default **gw/lu**; pakai *aku/kamu* kalau audiensnya lebih luas/nasional. Pilih satu, konsisten.
- Dilarang campur dalam satu dokumen. Satu dokumen = satu register.

**2. Istilah teknis: pakai yang dipakai developer Indonesia sehari-hari.**
- Biarkan Inggris kalau itu istilah baku dan natural: commit, push, deploy, branch, repo, file, folder, bug, cache, request.
- Jangan terjemahkan jadi kaku: "berkas komputer" (siapa yang ngomong gini?), "lambang penunjuk tetikus" (cukup: kursor).
- Tapi jangan juga semua dianglizikan kalau ada padanan yang hidup: papan ketik (keyboard oke juga), berbagi layar (bukan screen sharing kalau audiens umum).
- Detail lengkap: [references/ragam-dan-istilah.md](references/ragam-dan-istilah.md)

**3. EYD V — jebakan yang paling sering kejadian di teks dev:**
- "di" pisah kalau kata depan: "di server", "di folder", "di mana lokasinya?"
- "di-" sambung kalau imbuhan pasif: "diinstall" salah → "di-install" atau ganti "dipasang". "diupload" → "di-unggah" atau "diupload" (baku: diunggah).
- "dilakukan pengecekan" → "dicek". Pasif berantai = tanda teks AI atau birokrat.
- Lengkap: [references/ragam-dan-istilah.md](references/ragam-dan-istilah.md)

**4. Anti-slop Indonesia — pembunuh klise tercepat:**
- Hapus semua pembuka "Di era digital…", "Seiring berkembangnya…", "Tidak dapat dipungkiri bahwa…", "Penting untuk dicatat bahwa…"
- Hapus penutup "Semoga bermanfaat!", "Demikianlah artikel…", "Jadi, tunggu apa lagi?"
- Hapus ekor tack-on: ", menciptakan pengalaman baru bagi pengguna" — kalau ekornya gak bawa info, buang.
- "hiruk pikuk" terlarang total — penanda AI paling terkenal di Indonesia.
- Daftar lengkap: lihat lazy-writing `references/kata-terlarang-id.md` atau https://github.com/giangeralcus/lazy-writing

**5. Commit message & komentar kode:**
- Commit: imperatif pendek, satu bahasa konsisten per repo. "Perbaiki race condition di parser" atau "Fix race condition in parser" — jangan dicampur dalam satu repo.
- Komentar kode: jelasin KENAPA, bukan APA. Kode udah bilang apa. Komentar Indonesia yang bagus: `# jangan diurutkan di sini; API-nya butuh urutan asli dari DB`.
- Jangan translate-inggris-kan istilah di kode: variabel `pengguna` boleh, tapi konsisten — jangan ada `user` di file lain.

**6. Angka & klaim tetap kewajiban.** Angka tanpa sumber jangan ditulis. "Ribuan pengguna" tanpa data = hapus atau tulis angkanya.

## Contoh Cepat

❌ "Dalam era digital yang terus berkembang pesat ini, hadirnya fitur baru kami tidak hanya mempermudah pekerjaan Anda, tetapi juga menciptakan pengalaman yang seamless."
✅ "Fitur ini bikin import data beres dalam satu klik. Dulu 15 menit, sekarang 3 detik."

❌ "Untuk melakukan instalasi, silakan lakukan eksekusi perintah berikut ini."
✅ "Jalankan perintah ini:"

Contoh panjang sebelum/sesudah: [references/contoh-sebelum-sesudah.md](references/contoh-sebelum-sesudah.md)

## Self-Check

1. Test Lazy per kalimat.
2. Baca keras-keras — kerasa kayak brosur korporat 2010 atau translate Google? → rewrite.
3. Register konsisten? EYD V aman? Istilah teknis konsisten?
4. Angka ada sumbernya?
