# PABW - Muhammad Lutfi Ilham

Repository ini digunakan untuk menyimpan tugas mata kuliah Pengembangan Aplikasi Berbasis Web (PABW) selama satu semester.

## Daftar Pertemuan

### Pertemuan 3 - HTML5 Semantik, Form, Media & Aksesibilitas

Folder: `worksheet-p3`

Topik: Daftar film yang pernah saya tonton.

File:
- `worksheet-p3/profil.html`
- `worksheet-p3/avengers-endgame.jpg`

## Pertemuan 4 — Design token halaman profil

Pekerjaan P4 merupakan lanjutan dari halaman P3. Bagian P4 disimpan di folder `worksheet-p4` dan menggunakan CSS terpisah.

### Berkas gaya

- `worksheet-p4/tokens.css` — primitive token dan semantic token.
- `worksheet-p4/base.css` — reset, box-sizing, tipografi, warna dasar, tabel, dan gambar.
- `worksheet-p4/layout.css` — header, navigasi, main, section, figure, dan footer menggunakan flexbox serta gap.
- `worksheet-p4/komponen.css` — form, input, button, focus state, pesan galat, dan pengalih tema.
- `worksheet-p4/tema.css` — tema gelap otomatis dan manual dengan perubahan semantic token.

### Warna utama

Warna utama menggunakan `--color-primary: var(--blue-700)` pada tema terang. Warna ini dipusatkan pada semantic token agar komponen menggunakan satu nama token, bukan nilai warna primitive secara langsung.

### Token yang dipilih

| Token | Fungsi |
|---|---|
| `--color-bg` | Latar halaman |
| `--color-fg` | Warna teks utama |
| `--color-surface` | Latar permukaan seperti header, form, dan footer |
| `--color-border` | Garis batas |
| `--color-primary` | Warna utama tautan dan tombol |
| `--color-danger` | Pesan kesalahan form |
| `--color-focus` | Focus ring |
| `--space-1` s.d. `--space-6` | Spacing |
| `--radius-sm`, `--radius-md` | Radius |
| `--text-sm` s.d. `--text-2xl` | Ukuran teks |

### Kriteria maintainability satu baris

Jika nilai `--color-primary` diubah satu kali di `tokens.css`, warna utama tombol dan tautan yang menggunakan token tersebut ikut berubah tanpa mengedit setiap komponen.

### Urutan CSS

`tokens.css` → `base.css` → `layout.css` → `komponen.css` → `tema.css`

### Catatan penggunaan AI

AI digunakan untuk membantu menyusun dan merapikan CSS sesuai instruksi worksheet P4, termasuk pembagian primitive/semantic token, layout flexbox, komponen form, dan tema gelap. Isi halaman, topik film, data tabel, serta keputusan konten berasal dari pekerjaan saya sendiri. Kode tetap saya periksa dan sesuaikan dengan worksheet.

### Keaslian

Topik dan isi halaman merupakan pekerjaan saya sendiri dan tidak menyalin pekerjaan teman.
