# bahasa-indo-code

Skill menulis Bahasa Indonesia buat developer — README, commit, komentar kode, docs, UI copy, chat kerja — yang kedengeran manusia, bukan AI.

100% Bahasa Indonesia. Standalone (gak butuh skill lain), tapi jadi pasangan skill [lazy-writing](https://github.com/giangeralcus/lazy-writing).

## Kenapa perlu

Teks AI berbahasa Indonesia gampang kebongkar: terjemahan kaku ("mari kita menyelami"), slop marketing ("Di era digital yang serba cepat ini"), campur register ("gue" nyampur "Anda" satu halaman). Skill ini ngebunuh ketiganya + aturan EYD V yang paling sering kejadian di teks dev (`diinstall`, `dikarenakan`, pasif berantai).

## Isi

```
SKILL.md                              # aturan inti + test lazy + contoh cepat
references/
  ragam-dan-istilah.md                # baku vs santai, padanan istilah, EYD V, pola slop ID
  contoh-sebelum-sesudah.md           # README, docs, commit, komentar kode, UI copy, chat
  sumber.md                           # kredit lengkap
```

## Pasang

Claude Code:
```bash
cp -r bahasa-indo-code ~/.claude/skills/          # personal
cp -r bahasa-indo-code <repo>/.claude/skills/     # project-scoped
```

Codex:
```bash
cp -r bahasa-indo-code <repo>/.codex/skills/
```

## Test Lazy

Tanya per kalimat: *kalau gw hapus, apa yang hilang?* Jawabannya "nggak ada" → hapus.

MIT.
