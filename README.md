# Sistem Pengurusan Ahli — DPMM Negeri Johor

Sistem pengurusan ahli berasaskan web untuk Dewan Perniagaan Melayu Malaysia (DPMM) Negeri Johor.

## 🌐 Live App
Setelah deploy ke GitHub Pages, akses di:
`https://<username>.github.io/<repo-name>/`

## 📋 Ciri-ciri
- Dashboard ringkasan ahli
- Senarai ahli dengan carian & penapis
- Pengurusan mengikut daerah
- Penjejakan yuran & SSM
- Eksport CSV
- Data langsung dari Supabase

## 🛠️ Teknologi
- HTML / CSS / JavaScript (satu fail)
- Supabase (pangkalan data)

## 🚀 Cara Deploy ke GitHub Pages

1. **Buat repositori baru** di GitHub (contoh: `sistem-ahli-dpmm-johor`)
2. **Upload** fail `index.html` ke repositori
3. Pergi ke **Settings → Pages**
4. Di bawah *Source*, pilih **Deploy from a branch**
5. Pilih branch `main` dan folder `/ (root)`
6. Klik **Save**
7. Tunggu beberapa minit — URL akan muncul di bahagian Pages

## 🔐 Keselamatan
- Supabase RLS (Row Level Security) diaktifkan
- Akses baca: awam (anon)
- Akses tulis: pengguna yang log masuk sahaja
- Kata laluan login disimpan dalam fail HTML (tukar jika perlu)

## 📁 Struktur Fail
```
index.html    ← Aplikasi penuh (satu fail)
README.md     ← Dokumentasi ini
```
