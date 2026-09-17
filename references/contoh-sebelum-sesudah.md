# Contoh Sebelum → Sesudah

## 1. README intro

**❌ Sebelum (AI slop):**
> Dalam era digital yang terus berkembang pesat ini, kebutuhan akan pengelolaan data yang efisien semakin meningkat. Aplikasi ini hadir sebagai solusi terdepan yang tidak hanya mempermudah proses pengelolaan data Anda, tetapi juga menciptakan pengalaman pengguna yang seamless dan modern.

**✅ Sesudah (lazy):**
> Alat CLI buat impor data penjualan dari marketplace ke database lo. Satu perintah, beres. Gak perlu buka-buka spreadsheet lagi.

```bash
npm install -g importir
importir ./penjualan.csv
```

## 2. Dokumentasi instalasi

**❌ Sebelum:**
> Untuk melakukan proses instalasi, silakan lakukan eksekusi perintah di bawah ini pada terminal Anda. Pastikan terlebih dahulu bahwa dependensi yang dibutuhkan telah terpasang dengan baik.

**✅ Sesudah:**
> Butuh Python 3.11+ dan ffmpeg. Cek dulu:
>
> ```bash
> python --version && ffmpeg -version
> ```
>
> Lanjut install:
>
> ```bash
> pip install -r requirements.txt
> ```

## 3. Commit message

**❌ Sebelum:** `Menambahkan fitur validasi pada form pendaftaran guna meningkatkan keamanan aplikasi`
**✅ Sesudah:** `Tambah validasi email di form daftar` (body: "double-opt-in biar gak ada fake signup; captcha udah gak cukup sejak Maret.")

## 4. Komentar kode

**❌ Sebelum:**
```python
# Melakukan iterasi pada setiap elemen data untuk melakukan proses transformasi
for row in data:
    row["total"] = hitung_total(row)
```
(komentar ngulang kode → useless)

**✅ Sesudah:**
```python
# JANGAN sort di sini — API payment butuh urutan asli dari DB (lihat #142)
for row in data:
    row["total"] = hitung_total(row)
```

## 5. UI copy

**❌ Sebelum:** "Dengan fitur unggul ini, pengalaman bertransaksi Anda akan semakin mulus dan menyenangkan!"
**✅ Sesudah:** "Transfer udah? Cek statusnya di sini."

## 6. Pesan chat kerja

**❌ Sebelum:** "Selamat pagi Pak, berikut kami sampaikan bahwa terkait issue yang kemarin telah kami lakukan pengecekan dan diketahui bahwa masalah telah berhasil kami tangani. Demikian informasi ini kami sampaikan. Terima kasih."
**✅ Sesudah:** "Pagi Pak, issue kemarin udah beres. Penyebabnya disk penuh di server 3 — log rapiin, space ditambah 50GB. Monitor 24 jam ke depan aman."
