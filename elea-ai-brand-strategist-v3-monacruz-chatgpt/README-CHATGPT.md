# Cara Setup Elea di ChatGPT (Custom GPT)

Paket ini adalah versi Elea untuk ChatGPT Custom GPT. Isinya dan standarnya sama dengan versi Claude, yang beda cuma cara pasang.

## Kenapa dipisah dua bagian

Kolom instruction Custom GPT punya batas sekitar 8.000 karakter. SYSTEM-PROMPT Elea yang lengkap jauh lebih panjang. Jadi pemasangannya dibagi dua, tanpa membuang satu pun isi esensial:

1. Kolom instruction Custom GPT diisi versi padat pengarah inti (`SYSTEM-PROMPT-CHATGPT.md`).
2. Knowledge Custom GPT diisi file-file lengkap.

Versi padat bukan ringkasan yang membuang isi. Isinya semua protokol wajib, prinsip inti, konteks brand, dan perintah membaca file knowledge. Detail panjangnya tetap utuh di file knowledge.

## Langkah Pemasangan

### 1. Isi kolom Instructions Custom GPT
Buka `SYSTEM-PROMPT-CHATGPT.md`. Salin seluruh isinya ke kolom Instructions di GPT Builder. Ukurannya sekitar 7,382 karakter, muat di bawah batas.

### 2. Upload Knowledge
Upload file berikut ke bagian Knowledge Custom GPT:
- Seluruh folder `standards/`
- Seluruh folder `frameworks/`
- Seluruh folder `references/`
- `BRAND-PROFILE.md` (konteks Monacruz permanen, menyatu)
- `SYSTEM-PROMPT.md` (versi lengkap, rujukan detail)
- `SKILL.md`
- `FOLDER-STRUCTURE.md`

### 3. Selesai
Elea di ChatGPT punya pengarah di instruction dan detail lengkap di knowledge.

## Dua penegasan khusus di versi ChatGPT

1. **Wajib cek source, jangan halu.** Instruction versi ini menegaskan Elea selalu cek dan baca dulu file di knowledge project (project knowledge) sebelum menjawab, dan membedakannya dari memori atau riwayat chat. Elea dilarang mengarang, dan wajib jujur kalau suatu hal di luar cakupan knowledge base.

2. **Humanize di dua konteks.** Aturan humanize berlaku saat chat dengan user DAN saat menghasilkan output apa pun.

## Catatan

Kalau ChatGPT mengubah batas karakter instruction di kemudian hari, versi instruction bisa disesuaikan. Prinsipnya tetap: esensi tidak dipangkas, hanya diatur antara instruction dan file knowledge.
