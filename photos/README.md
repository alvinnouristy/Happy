# 🖼️ Folder Foto

Letakkan foto Anda di folder ini untuk ditampilkan di galeri carousel.

## Cara Menambahkan Foto

### 1. Siapkan Foto Anda
- Minimal **5 foto** untuk carousel yang smooth
- Format: JPG, PNG, atau WebP
- Ukuran: Kurang dari 5MB per foto (untuk loading cepat)
- Aspek rasio: **1:1 (Persegi)** untuk hasil terbaik
  - Contoh: 400x400px, 600x600px, 1000x1000px

### 2. Copy Foto ke Folder Ini
- Buka folder `photos/`
- Copy/paste foto Anda ke sini
- Beri nama yang mudah diingat: `photo1.jpg`, `photo2.jpg`, dll

### 3. Update Nama File di `index.html`
- Buka file `index.html` dengan text editor (Notepad, VS Code, dll)
- Cari bagian:
  ```
  <!-- PETUNJUK PENGGANTIAN GAMBAR -->
  ```
- Ganti setiap link foto. Dari:
  ```html
  <img src="https://images.unsplash.com/photo-1529156069898-49953e39b3ac?w=400&h=400&fit=crop" alt="Foto bersama 1">
  ```
  
  Menjadi:
  ```html
  <img src="photos/photo1.jpg" alt="Foto bersama 1">
  ```

### 4. Duplikasi Untuk Seamless Loop
- Ubah 5 foto yang diduplikasi di bawah juga dengan nama yang sama
- Ini membuat carousel terkesan infinite

## 📸 Contoh Struktur

```
photos/
├── photo1.jpg      ← Foto pertama
├── photo2.jpg      ← Foto kedua
├── photo3.jpg      ← Foto ketiga
├── photo4.jpg      ← Foto keempat
├── photo5.jpg      ← Foto kelima
└── README.md       ← File ini
```

## ✨ Fitur Foto di Website

Setiap foto akan ditampilkan dengan:
- ✅ **Bingkai mewah** dengan border gradient pink
- ✅ **Efek cahaya** (glow effect)
- ✅ **Animasi hover** - zoom dan rotate ketika mouse diarahkan
- ✅ **Transisi smooth** - pergerakan yang halus
- ✅ **Refleksi cahaya** - efek glass-like yang elegan
- ✅ **Inner frame** - bingkai dalam untuk kedalaman visual

## 🎨 Tips Untuk Hasil Terbaik

1. **Pilih foto berkualitas tinggi**
   - Jelas, terang, dan warna natural
   - Hindari foto yang terlalu gelap

2. **Gunakan foto dengan latar belakang neutral**
   - Lebih fokus pada subjek (Anda dan pasangan)
   - Latar yang tidak terlalu ramai

3. **Konsistensi pencahayaan**
   - Foto yang terang/gelap secara konsisten terlihat lebih harmonis

4. **Ukuran persegi (1:1)**
   - Paling ideal untuk carousel ini
   - Jika tidak persegi, akan dipotong otomatis

5. **Urutan foto**
   - Susun dari masa lalu ke sekarang untuk cerita yang menarik
   - Atau mix dengan momen spesial

## 🔄 Mengganti Foto Kemudian

Anda bisa ganti foto kapan saja:
1. Replace file di folder `photos/` dengan foto baru
2. Ganti nama jika diperlukan di `index.html`
3. Refresh browser untuk melihat perubahan

## 💡 Bantuan Teknis

**File tidak muncul?**
- Pastikan nama file di `index.html` sama dengan nama file di folder
- Case-sensitive: `photo1.jpg` ≠ `Photo1.jpg`
- Pastikan format file adalah JPG, PNG, atau WebP

**Foto terlihat blur?**
- Gunakan foto dengan resolusi tinggi (minimal 600x600px)
- Format PNG biasanya lebih tajam daripada JPG berkualitas rendah

**Carousel terlalu cepat/lambat?**
- Edit `index.html`, cari `animation: scroll 20s`
- Ubah angka `20s` menjadi lebih besar (lebih lambat) atau lebih kecil (lebih cepat)

---

**Selamat menyiapkan galeri foto romantis Anda!** ❤️
