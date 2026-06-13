# Happy Birthday Queency 🌹

Halaman ucapan ulang tahun interaktif yang cantik dan responsif untuk Queency.

## Fitur

✨ **Lock Screen** - Masukkan PIN tanggal spesial untuk membuka kejutan (14/06)
📸 **Gallery** - Tampilkan foto-foto istimewa dengan slideshow otomatis (otomatis load dari folder `images`)
💕 **Letter** - Pesan khusus dari hati
🌸 **Poem** - Puisi indah untuk hari istimewamu
🎂 **Final Page** - Ucapan terbaik dengan wishes counter

## Responsif & Mobile-Friendly

✓ Desktop (1920x1080 dan lebih besar)
✓ Tablet (768px - 1024px)
✓ Mobile (480px - 768px)
✓ Extra Small Mobile (< 480px)
✓ Landscape Mode

## Cara Menjalankan

### Opsi 1: Python Built-in Server (Recommended)

```bash
cd e:\pi\JOKI\birthday
python -m http.server 8000
```

Lalu buka di browser: **http://localhost:8000/birthday-queency.html**

### Opsi 2: Node.js

Jika punya Node.js dan `http-server`:

```bash
npm install -g http-server
cd e:\pi\JOKI\birthday
http-server
```

### Opsi 3: Live Server (VS Code)

1. Install extension "Live Server" di VS Code
2. Klik kanan file `birthday-queency.html`
3. Pilih "Open with Live Server"

## Memasukkan Foto

Foto akan **otomatis dimuat** dari folder `images/` saat halaman Gallery dibuka. Tidak perlu input atau setup tambahan!

**Cara menambah/mengganti foto:**
1. Simpan foto ke folder `images/`
2. Edit file `images/index.json` dan tambahkan nama file (contoh: `"photo1.jpg"`, `"photo2.png"`, dll)
3. Refresh halaman browser - foto baru akan muncul otomatis

**Contoh `images/index.json`:**
```json
[
  "queency1.svg",
  "queency2.svg",
  "queency3.svg",
  "photo_anda.jpg"
]
```

## PIN untuk Unlock

**PIN: 1406** (14 Juni - tanggal spesial Queency)

## Struktur Folder

```
birthday/
├── birthday-queency.html    (File utama)
├── README.md                (File ini)
├── images/
│   ├── index.json          (Daftar foto yang akan dimuat)
│   ├── queency1.svg        (Contoh foto 1)
│   ├── queency2.svg        (Contoh foto 2)
│   └── queency3.svg        (Contoh foto 3)
<!-- music folder removed: audio page was removed from the web app -->
```

## Tips

- Untuk hasil terbaik, gunakan browser modern (Chrome, Firefox, Safari, Edge)
- Foto akan ditampilkan dengan aspect ratio 4:3 di desktop, 3:2 di mobile
- Server HTTP **diperlukan** untuk fitur loading foto otomatis bekerja
- Akses lokal file (`file://`) akan diblokir oleh browser untuk keamanan

## Customization

Edit file `birthday-queency.html`:
- Ubah PIN: cari `const CORRECT = '1406'`
- Ubah nama: ganti "Queency" dengan nama yang diinginkan
- Ubah pesan: edit bagian "LETTER" dan "POEM"
- Ubah warna: cari hex color codes (#d4537e, #ffd6e8, dll)

## Browser Support

✓ Chrome/Edge 90+
✓ Firefox 88+
✓ Safari 14+
✓ Mobile Chrome
✓ Mobile Safari

---

Dibuat dengan ❤️ untuk hari istimewa Queency
