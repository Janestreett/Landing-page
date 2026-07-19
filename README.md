# Landing-page
# Noir Atelier — Landing Page

Tugas Praktik 3: Landing Page — X PPLG SMT 2

Landing page bertema **hitam elegan** untuk brand fiktif parfum niche "Noir Atelier". Satu file HTML mandiri (HTML, CSS, JS digabung dalam `noir-atelier-landing.html`).

## Cara Menjalankan

1. Unduh file `noir-atelier-landing.html`.
2. Buka langsung di browser (klik dua kali, atau drag ke jendela browser).
3. Tidak butuh server — murni HTML/CSS/JS statis.

## Fitur Sesuai Instruksi

| Instruksi | Implementasi |
|---|---|
| **Navbar** | Logo "NOIR ATELIER", 3 link navigasi, tombol CTA "Lihat Koleksi", menu hamburger responsif untuk mobile |
| **Hero** | Judul besar bergaya serif miring, deskripsi singkat, dua tombol aksi, ilustrasi botol parfum + efek cahaya berdenyut (CSS) |
| **Card Feature** | 3 kartu keunggulan ("Bahan Langka", "Batch Terbatas", "Diracik Tangan") dengan ikon lingkaran dan garis emas yang muncul saat hover |
| **Footer** | 4 kolom (brand, jelajah, bantuan, kontak) + baris copyright di bagian bawah |

## Palet & Tipografi

- **Warna dasar:** hitam `#0b0b0c`, panel abu gelap `#141416` / `#1c1c1f`
- **Aksen:** emas pudar `#c8a765` (dipakai untuk teks penting, ikon, dan garis hover)
- **Font display:** `Cormorant Garamond` (serif, kesan mewah)
- **Font body:** `Jost` (sans-serif tipis, netral dan bersih)

## Bagian Tambahan

Selain 4 bagian wajib, ditambahkan:
- **Statistik singkat** (jumlah aroma, batch, waktu maserasi, tahun beroperasi)
- **CTA band** sebelum footer untuk mendorong aksi pemesanan

## Interaksi & Responsif

- Hover pada kartu fitur menampilkan garis emas di sisi kiri dan ikon sedikit berputar
- Menu navbar berubah menjadi hamburger di layar < 900px
- Grid kartu, statistik, dan footer menyesuaikan jumlah kolom di breakpoint `900px` dan `560px`
- Mendukung `prefers-reduced-motion` dan `:focus-visible` untuk aksesibilitas

## Catatan

Nama brand, produk, dan copy bersifat fiktif, dibuat khusus untuk keperluan demo tugas.
