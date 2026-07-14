# 📁 Panduan Memasukkan Gambar ke CrunchCo

## Struktur Folder
Buat folder `images/` di dalam `cookie-shop/`, lalu masukkan semua gambar:

```
cookie-shop/
└── images/
    │
    │── PRODUK COOKIES (dipakai di menu, order, index, tracking)
    ├── choco-chip-classic.jpg
    ├── double-choco-fudge.jpg
    ├── matcha-white-choco.jpg
    ├── blueberry-crumble.jpg
    ├── lemon-zesty.jpg
    ├── strawberry-jam-swirl.jpg
    ├── raspberry-cheesecream.jpg
    ├── peanut-butter-bliss.jpg
    ├── coconut-delight.jpg
    ├── hazelnut-praline.jpg
    ├── vanilla-butter-classic.jpg
    ├── brown-sugar-oatmeal.jpg
    ├── cinnamon-sugar-roll.jpg
    ├── matcha-red-bean.jpg
    ├── ube-cream-cheese.jpg
    ├── black-sesame-mochi.jpg
    ├── salted-caramel-pretzel.jpg
    ├── red-velvet-crinkle.jpg
    ├── tiramisu-espresso.jpg
    ├── pandan-coconut.jpg
    │
    │── HALAMAN ABOUT
    ├── about-story.jpg       ← foto dapur / proses memanggang
    ├── team-sari.jpg         ← foto Founder (portrait)
    ├── team-baskara.jpg      ← foto Operations Manager
    ├── team-nadia.jpg        ← foto Creative Director
    └── team-reza.jpg         ← foto R&D Manager
```

## Ukuran Gambar yang Disarankan

| Dipakai Di | Ukuran CSS | Rekomendasi File |
|---|---|---|
| Hero card (index) | 110px tinggi | min 400×300px |
| Product card (menu, index) | 180–200px tinggi | **min 600×400px** |
| Picker item (order) | 90px tinggi | min 400×300px |
| Summary item (order) | 52×52px kotak | min 200×200px |
| Tracking item | 52×52px kotak | min 200×200px |
| Team photo (about) | 180px tinggi | **min 400×400px** (portrait) |
| Story main (about) | 380px tinggi | min 800×600px |

## Aturan CSS yang Menjaga Ukuran Konsisten
Semua gambar sudah menggunakan:
```css
object-fit: cover;       /* potong agar mengisi kotak */
object-position: center; /* fokus ke tengah */
width: 100%;
height: [tetap]; /* tinggi dikunci, tidak berubah */
```
Artinya: gambar apapun ukurannya (kecil/besar/portrait/landscape)
akan SELALU tampil dengan ukuran yang sama, bagian luar dipotong.

## Tips Format Gambar
- Gunakan **.jpg** untuk foto (lebih kecil filenya)
- Gunakan **.png** jika ada transparansi
- Compress di **squoosh.app** sebelum upload (target < 200KB per gambar)
- Nama file harus **lowercase** dan pakai **tanda minus** (-)
