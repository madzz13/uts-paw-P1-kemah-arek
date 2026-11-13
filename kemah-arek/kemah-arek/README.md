# Kemah Arek: Sewa Alat Kemah Surabaya

UTS Pemrograman Antarmuka Web, Teknik Informatika ITATS. Situs: `https://<akun>.github.io/uts-paw-<kelas>-kemah-arek/`

## Anggota
| NPM | Nama | Akun GitHub | Halaman |
|---|---|---|---|
| ... (ketua) | ... | ... | index.html, panduan.html, README, deploy |
| ... | ... | ... | katalog.html, tentang.html |
| ... | ... | ... | pemesanan.html, terima-kasih.html, validasi dan aksesibilitas |

## Sub-tema
Sub-tema 10, Sewa alat kemah / outdoor. Usaha fiktif **Kemah Arek**. Target pengguna: mahasiswa dan pendaki pemula di Surabaya dan sekitarnya.

## Sitemap
`index.html` -> `katalog.html`, `pemesanan.html` -> `terima-kasih.html`, `tentang.html`, `panduan.html`
Sketsa denah mobile dan desktop: *(lampirkan gambar)*

## Token (custom property)
| Token | Terang | Gelap | Fungsi |
|---|---|---|---|
| --bg | #edf2f0 | #0d1612 | latar halaman |
| --surface | #ffffff | #16231d | kartu, header |
| --text / --muted | #14231c / #40524a | #eaf1ed / #b4c4bb | teks |
| --primary / --on-primary | #1d4d3b / #fff | #8fd8b0 / #0d1612 | tombol, tautan |
| --accent / --on-accent | #ffc247 / #14231c | sama | badge, fokus |
| --line, --danger | #c3d1ca, #a4161a | #2f443a, #ff8d8f | garis, error |
| --font-head, --font-body, --space, --radius | Bricolage Grotesque, Public Sans, 1rem, .75rem | | tipografi, spasi |

## Breakpoint
| Nama | Lebar | Perubahan |
|---|---|---|
| Dasar | < 40em | 1 kolom, navbar tertutup |
| Tablet | 40em | statistik 2 kolom |
| Desktop | 64em | hero 2 kolom (grid-template-areas), statistik 4 kolom, artikel + aside sticky |

## Framework vs CSS sendiri
- **Bootstrap 5.3 (CDN):** navbar responsif, grid `row/col`, card, button, form control, table.
- **CSS sendiri:** hero (grid areas), galeri `auto-fit`, badge `absolute`, header `sticky`, dark mode, token.
- **Kustomisasi:** variabel `--bs-*` ditimpa token sendiri di `style.css` (dimuat setelah Bootstrap).
- **Perbandingan:** tombol dengan Bootstrap cukup `class="btn btn-primary"` dan warna ditimpa lewat variabel `--bs-btn-*`. Dengan CSS murni perlu menulis padding, radius, hover, dan fokus sendiri. Dipilih Bootstrap karena lebih cepat dan konsisten, sementara identitas visual tetap dari token sendiri.

## Hasil uji (isi setelah deploy)
- Tangkapan layar 360px, 768px, 1280px, dan mode gelap: *(lampirkan)*
- Lighthouse Accessibility per halaman: ...
- W3C Validator: ...
- Uji keyboard: ...

## Sumber dan AI
- Foto di `img/` (hero, tenda, sleeping bag, matras, kompor, carrier): isi sumber, fotografer, URL, dan lisensi tiap foto di sini. Foto di-crop ke rasio 3:2.
- Font: Google Fonts. Framework: Bootstrap 5.3.
- AI: Claude (Anthropic) dipakai untuk draf awal struktur HTML dan CSS; seluruh anggota sudah membaca dan memahami kodenya.
