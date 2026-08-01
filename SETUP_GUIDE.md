# 💕 Panduan Lengkap Website Romantis Anniversary

Selamat! Website kejutan romantic anniversary Anda sudah siap! 

## 📁 Struktur File yang Sudah Ada

```
/vercel/share/v0-project/
├── public/
│   ├── index.html          ✅ File website utama (SUDAH SIAP)
│   ├── photos/             📸 Folder untuk foto (kosong, siap diisi)
│   └── music/              🎵 Folder untuk musik (kosong, siap diisi)
├── photos/                 📸 Folder foto backup
├── music/                  🎵 Folder musik backup
├── README.md              📖 Petunjuk lengkap
└── SETUP_GUIDE.md         📖 File ini
```

## ⚡ Quick Start (3 Langkah)

### 1️⃣ Tambahkan Foto Anda
- **Buka folder:** `photos/` 
- **Copy foto ke sini:** Minimal 5 foto (JPG/PNG)
- **Format terbaik:** Persegi (1:1 ratio) - contoh: 600x600px

### 2️⃣ Update Nama Foto di HTML
- **Buka:** `public/index.html`
- **Cari:** `<!-- PETUNJUK PENGGANTIAN GAMBAR -->`
- **Ganti setiap:** 
  ```html
  <img src="https://images.unsplash.com/photo-..." 
  ```
  Menjadi:
  ```html
  <img src="photos/photo1.jpg" alt="Foto bersama">
  ```
- **Catatan:** Jangan lupa update 10 foto (5 original + 5 duplikasi untuk infinite loop)

### 3️⃣ Tambahkan Musik Anda
- **Buka folder:** `music/`
- **Copy file:** `janjisuci.mp3` ke sini
- **Format:** MP3 (sangat disarankan)
- **Durasi:** 3-5 menit ideal
- **Ukuran:** Kurang dari 10MB

## 🎨 Fitur yang Sudah Jadi

✅ **Halaman Intro Sinematik**
- Desain gelap elegan dengan warna pink gradient
- Efek partikel cahaya jatuh (seperti kelopak mawar)
- Tombol interaktif "Buka Kenangan Kita"
- Teks fade-in animation

✅ **Galeri Carousel Romantis**
- Foto auto-scroll infinite loop
- Efek bingkai mewah dengan border gradient pink
- Glow effect dan cahaya ambient
- Animasi hover - zoom + rotate
- Inner frame untuk kedalaman visual

✅ **Efek Interaktif**
- Hover pada foto: zoom 8% dan rotasi 2 derajat
- Glow effect yang menyala saat hover
- Smooth transitions semua animasi
- Refleksi cahaya glass-like effect

✅ **Musik Latar**
- Auto-play saat klik tombol "Buka Kenangan Kita"
- Volume otomatis 50%
- Tekan tombol **M** untuk mute/unmute
- Loop otomatis

✅ **Responsive Design**
- Sempurna di HP, tablet, dan desktop
- Otomatis menyesuaikan ukuran layar

## 🎯 Cara Menggunakan

### Desktop / Laptop
1. Buka folder: `public/`
2. Double-click: `index.html`
3. Browser akan membuka website secara otomatis

### Mobile (HP/Tablet)
1. Copy folder project ke device
2. Buka file manager
3. Buka `public/index.html`
4. Atau: Share link website ke Vercel/hosting

## 🎨 Kustomisasi Tambahan

### Mengubah Kecepatan Carousel
- Buka `public/index.html`
- Cari: `animation: scroll 20s`
- Ubah `20s` → lebih besar (lebih lambat), lebih kecil (lebih cepat)

### Mengubah Warna (dari Pink → Warna Lain)
- Cari: `#ff69b4` (hot pink) → ganti dengan warna favorit
- Cari: `#ffb6d9` (light pink) → ganti dengan warna aksen

### Mengubah Judul
- Cari: `"Kejutan untuk Firda Amelia"`
- Ganti dengan nama kekasih Anda

### Mengubah Pesan
- Edit teks: "Dari Alvin Nouristy"
- Edit: "Selamat Hari GirlFriend Sayang"
- Edit: "Dan Selamat atas 1 tahun berlangsungnya kita ❤️"

## 📸 Tips Foto Terbaik

1. **Pilih foto berkualitas tinggi**
   - Jelas, terang, warna natural
   - Hindari terlalu gelap

2. **Gunakan foto persegi (1:1)**
   - Ideal: 600x600px, 800x800px, atau 1000x1000px
   - Jika tidak persegi, akan auto-crop

3. **Konsistensi pencahayaan**
   - Terang/gelap konsisten terlihat lebih harmonis

4. **Urutan menarik**
   - Masa lalu → sekarang
   - Atau: Mix momen spesial

5. **Fokus pada subjek**
   - Latar yang tidak terlalu ramai
   - Highlight kalian berdua

## 🔊 Tips Musik Terbaik

1. **Format MP3** (paling kompatibel)
   - Juga support: WAV, OGG, M4A/AAC

2. **Durasi 3-5 menit**
   - Cukup untuk menikmati galeri
   - Tidak terlalu lama

3. **Volume balance**
   - Jangan terlalu keras
   - Musik latar, bukan pengalih

4. **Musik berkualitas**
   - Clear audio, no static
   - Hindari musik dengan bass terlalu berat

## 🛠️ Troubleshooting

**Q: Foto tidak muncul?**
A: 
1. Pastikan nama file di HTML sama dengan nama file di folder
2. Case-sensitive: `photo1.jpg` ≠ `Photo1.jpg`
3. Format support: JPG, PNG, WebP

**Q: Musik tidak diputar?**
A:
1. Pastikan file ada di folder `music/`
2. Nama file: `janjisuci.mp3`
3. Browser mungkin butuh permission - klik "Allow" jika diminta

**Q: Carousel terlalu cepat?**
A: 
1. Edit `public/index.html`
2. Cari: `animation: scroll 20s`
3. Ubah ke `30s` atau `40s`

**Q: Bagaimana cara upload ke internet?**
A:
1. Gunakan Vercel Deploy (gratis!)
2. Atau GitHub Pages
3. Atau hosting lainnya yang support HTML statis

## 💝 Final Checklist

- [ ] Sudah copy 5+ foto ke folder `photos/`
- [ ] Sudah update nama foto di `index.html`
- [ ] Sudah copy `janjisuci.mp3` ke folder `music/`
- [ ] Sudah test buka `index.html` di browser
- [ ] Sudah test klik tombol "Buka Kenangan Kita"
- [ ] Sudah lihat carousel berputar
- [ ] Musik sudah diputar

## 🚀 Deploy ke Internet (Optional)

Ingin share website ini ke Firda via link? Ikuti langkah ini:

### Opsi 1: Vercel (Gratis & Cepat)
1. Buka: https://vercel.com
2. Login/Sign up
3. Klik: "Add New Project"
4. Connect GitHub atau upload folder ini
5. Klik: "Deploy"
6. Dapatkan link publik!

### Opsi 2: GitHub Pages (Gratis)
1. Push folder ke GitHub
2. Settings → Pages → Enable GitHub Pages
3. Website akan live di: `https://username.github.io/repo`

### Opsi 3: Hosting Lainnya
- Netlify (https://netlify.com)
- Firebase (https://firebase.google.com)
- AWS S3 (https://aws.amazon.com)

## 📞 Bantuan Lebih Lanjut

Jika ada pertanyaan atau masalah:
1. Baca README.md di folder `photos/` dan `music/`
2. Check console browser: F12 → Console tab
3. Coba refresh page: Ctrl+R (atau Cmd+R di Mac)

---

**Selamat membuat kejutan anniversary yang tak terlupakan untuk Firda!** ❤️

Ingat: Yang terpenting bukan teknologinya, tapi cinta dan perhatian yang Anda tunjukkan. Good luck! 🍀
