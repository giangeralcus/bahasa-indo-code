# Ragam & Istilah — Panduan Singkat Dev Indonesia

## 1. Ragam baku vs santai

| Aspek | Baku (docs publik) | Santai (chat/konten) |
|---|---|---|
| Sapaan | kamu / Anda (pilih satu, konsisten) | lu (default) / kamu |
| Dirinya | saya | gw (default) / aku / saya |
| Konjungsi | tetapi, namun, karena | tapi, soalnya |
| Emoji | tidak / sangat terbatas | boleh, 0–2 per pesan |
| Slang | tidak | secukupnya (maks 1–2 per paragraf) |

Aturan utamanya satu: jangan campur. "Silakan klik tombol berikut ya bestie!" itu bencana dua dunia.

## 2. Padanan istilah teknis — kapan pakai yang mana

Prinsip: ikut yang dipakai developer Indonesia sehari-hari. Istilah yang sudah "menetap" dalam bahasa Indonesia formal boleh dipakai di docs baku; versi Inggris tetap sah di konteks teknis.

| Pakai (natural) | Hindari (kaku/aneh) | Catatan |
|---|---|---|
| file, folder | berkas, berkas komputer | "berkas" sah di docs pemerintah/formal; "map" cuma di UI terjemahan resmi (Windows/MS) — dev tetap bilang folder |
| unduh / download | mengunduh berkas | keduanya hidup; konsisten satu dokumen |
| unggah / upload | muat naik | "muat naik" kebanyakan cuma di KBBI |
| server | pelayan | jangan |
| peramban | browser | "peramban" sah di docs baku |
| surel / email | pos-el | keduanya oke, konsisten |
| tautan / link | pranala | "pranala" wikipedisme; jarang dipakai dev |
| basis data | database | "database" lebih umum di dev |
| kerangka kerja | framework | jangan; framework saja |
| masuk (log in) | login | "login" sudah menetap |
| pengguna | user | konsisten per dokumen/diprojek |

## 3. EYD V — jebakan frekuensi tinggi

| Salah | Benar | Kenapa |
|---|---|---|
| di server, di folder, di layar | di server | "di" + kata depan = pisah |
| dimana sistem ini jalan | di mana sistem ini jalan | "di mana" = pertanyaan/kata depan + mana |
| diinstall, di-Install | di-install, dipasang, diinstal | imbuhan pasif + asing = pakai tanda hubung; baku KBBI: "instal" → diinstal |
| diupload | diunggah (baku), di-upload (sah) | "diupload" umum di informal — docs baku pakai diunggah/di-upload, konsisten satu bentuk |
| dikarenakan | karena | "dikarenakan" = pasif berantai, bunyi birokrat/AI |
| melakukan pengecekan | mengecek / cek | kata kerja trivial buat berimbuhan |
| dapat dilihat bahwa | (hapus) | filler |
| kalo, gini, udah (di docs) | kalau, begini, sudah | slang cuma buat ragam santai |
| 25jt, Rp25.000.000 (di naskah) | 25 juta, Rp25 juta | tulis yang bisa dibaca |
| dsb., dll. (di kalimat formal) | dan lain-lain (maks 1x), atau sebut langsung | jarangi |

## 4. Pola kalimat AI bahasa Indonesia (ringkas)

1. Pembuka era: "Di era digital…", "Seiring dengan perkembangan…", "Dalam dunia yang terus berkembang…"
2. Penghemat tanggung jawab: "Tidak dapat dipungkiri bahwa…", "Penting untuk dicatat bahwa…"
3. Transisi lem: "Selain itu,", "Tak kalah penting,", "Dengan demikian," (di setiap paragraf)
4. Tack-on ekor: ", menciptakan …", ", menjadikannya …", ", menandakan …"
5. Penutup ritual: "Semoga bermanfaat!", "Demikianlah …", "Tunggu apa lagi?"
6. Rule of three: tiga kata sifat, tiga bullet, tiga contoh — selalu tiga.
7. "bukan hanya … tetapi juga …" — pola negative parallelism, favorit detektor.
8. Pasif berantai: "dilakukan", "diberikan", "dapat digunakan untuk" — ganti aktif.

Daftar lengkap + sumber: https://github.com/giangeralcus/lazy-writing
