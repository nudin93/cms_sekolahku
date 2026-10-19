# CMS Sekolahku v2.4.13 — Deskripsi & Kegunaan Aplikasi

CMS Sekolahku (oleh sekolahku.web.id) adalah aplikasi website sekolah lengkap
berbasis CodeIgniter + MySQL: sisi depan untuk publik, sisi belakang untuk
operator. Versi arsip ini: **v2.4.13**.

## Untuk siapa?

- **Operator/admin sekolah** — mengelola seluruh isi website dan data.
- **Humas/TIM IT sekolah** — publikasi berita, foto kegiatan, pengumuman.
- **Panitia PPDB** — mengelola pendaftaran peserta didik baru secara online.
- **Kepala sekolah** — memantau statistik dashboard dan isi website.
- **Orang tua & calon siswa** — membaca profil, berita, dan mendaftar PPDB.

## Apa yang bisa dilakukan?

1. **Profil sekolah online** — visi-misi, sambutan kepala sekolah, sejarah,
   fasilitas, staf, kontak; semua bisa diubah tanpa coding.
2. **Publikasi** — berita/artikel berkategori + tag + komentar, slider
   pengumuman, galeri foto & album kegiatan, halaman statis, tautan terkait.
3. **PPDB online** — atur gelombang, daya tampung/kuota, terima formulir,
   verifikasi berkas, umumkan hasil seleksi.
4. **Administrasi siswa** — database siswa per rombel & tahun ajaran, impor
   dari Excel, kelola alumni.
5. **Administrasi pegawai** — database guru & tenaga kependidikan.
6. **Interaksi** — polling, formulir pesan, langganan info, komentar berita.

## Manfaat

- Sekolah punya website resmi profesional tanpa bayar jasa pembuatan.
- Satu pintu data: website, PPDB, siswa, pegawai dalam satu login admin.
- Mengurangi kertas & antrean saat musim pendaftaran.
- Transparan: pengumuman dan hasil seleksi tampil online.

## Teknologi

PHP + MySQL/MariaDB (CodeIgniter), Bootstrap (tema), jQuery. Berjalan di
hosting cPanel biasa. Installer wizard di folder `install/` memandu
pengisian database, info sekolah, dan pembuatan akun admin pertama
(akun bawaan SQL: `administrator` / `administrator` — wajib diganti).
