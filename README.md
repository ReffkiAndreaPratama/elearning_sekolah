# RuangKelas — E-Learning Sekolah

Dashboard front-end untuk platform pembelajaran sekolah. Dibuat dengan HTML, CSS, dan JavaScript murni sebagai prototipe UI yang bisa dibuka langsung di browser.

## Fitur demo
- Dashboard siswa dengan statistik belajar.
- Kartu kelas dengan progres dan pencarian.
- Jadwal pelajaran hari ini.
- Daftar tugas dan interaksi menandai tugas selesai.
- Mode gelap/terang yang tersimpan di browser.
- Layout responsif untuk desktop dan perangkat mobile.

## Menjalankan
Buka `index.html` di browser modern. Tidak memerlukan Node.js, database, atau API key.

## Batasan prototipe
Data kelas, jadwal, dan tugas pada versi ini adalah data contoh. Belum ada login nyata, penyimpanan server, pengiriman tugas, atau presensi GPS/QR. Untuk versi produksi, tambahkan backend, database, autentikasi berbasis peran (admin/guru/siswa), serta validasi server untuk presensi.

## Rencana pengembangan
1. Backend API dan database.
2. Manajemen kelas, materi, dan akun.
3. Pengumpulan tugas dan penilaian.
4. Presensi GPS dan QR dengan sesi kedaluwarsa.
5. Dashboard guru dan admin.

## Struktur
```
elearning_sekolah/
├── index.html
├── style.css
├── app.js
└── README.md
```

Lisensi: MIT (tambahkan file LICENSE jika akan mendistribusikan versi final).