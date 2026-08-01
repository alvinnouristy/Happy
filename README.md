# 💕 Kejutan Anniversary Romantis

Website spesial untuk kejutan anniversary dengan galeri foto dan musik.

## 📁 Struktur Folder

```
/
├── index.html          (File utama website)
├── photos/             (Folder untuk menyimpan foto Anda)
│   ├── photo1.jpg
│   ├── photo2.jpg
│   ├── photo3.jpg
│   ├── photo4.jpg
│   └── ... (tambah lebih banyak sesuai keinginan)
├── music/              (Folder untuk menyimpan musik)
│   └── janjisuci.mp3   (Musik latar - ganti dengan file Anda)
└── README.md           (File ini)
```

## 🖼️ Cara Menambahkan Foto

1. **Letakkan foto di folder `photos/`**
   - Buka folder `photos/` di project
   - Copy/paste foto Anda ke sana

2. **Update nama foto di dalam `index.html`**
   - Buka `index.html` dengan text editor
   - Cari bagian: `<!-- PETUNJUK PENGGANTIAN GAMBAR -->`
   - Ganti link foto dari:
     ```html
     <img src="https://images.unsplash.com/photo-1529156069898-49953e39b3ac?w=400&h=400&fit=crop">
     ```
   - Menjadi:
     ```html
     <img src="photos/photo1.jpg" alt="Foto bersama">
     ```

3. **Minimal 5 foto** untuk carousel yang smooth
   - Bisa ditambah lebih banyak sesuai keinginan
   - Format: JPG, PNG, atau WebP

## 🎵 Cara Menambahkan Musik

1. **Letakkan file musik di folder `music/`**
   - Copy file `janjisuci.mp3` ke folder `music/`

2. **Update link musik di `index.html`**
   - Cari: `<!-- AUDIO / MUSIK -->`
   - Ganti:
     ```html
     <audio id="background-music" loop>
         <source src="music/janjisuci.mp3" type="audio/mpeg">
     </audio>
     ```

## 🚀 Cara Membuka Website

1. Buka folder project di file explorer
2. Klik kanan pada `index.html`
3. Pilih "Open with Browser" atau drag ke browser
4. Atau buka terminal dan ketik: `python -m http.server` (kemudian buka `http://localhost:8000`)

## ✨ Fitur yang Sudah Ada

✅ Halaman intro dengan efek partikel romantis
✅ Galeri foto carousel auto-scroll
✅ Efek bingkai mewah untuk setiap foto
✅ Musik latar yang putar otomatis saat membuka galeri
✅ Animasi fade-in yang smooth
✅ Responsive di semua ukuran layar (mobile, tablet, desktop)
✅ Efek hover interaktif pada foto
✅ Desain tema pink romantis

## 💡 Tips Tambahan

- Untuk hasil terbaik, gunakan foto dengan aspek rasio **1:1 (persegi)**
- Ukuran file foto sebaiknya kurang dari 5MB untuk loading cepat
- Musik MP3 sebaiknya durasi 3-5 menit
- Website ini bekerja offline, tidak perlu internet (setelah foto dan musik disimpan lokal)

Selamat menyiapkan kejutan anniversary yang romantis! ❤️
