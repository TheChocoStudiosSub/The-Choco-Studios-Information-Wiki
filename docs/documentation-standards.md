# Standar Dokumentasi TCS

**Status:** Berlaku untuk seluruh dokumentasi publik dalam repositori ini.

## Tujuan

Menjaga agar informasi TCS mudah dipahami, konsisten, dapat ditelusuri sumbernya, dan tidak menyesatkan pengguna.

## Prinsip penulisan

1. Gunakan bahasa Indonesia yang jelas, profesional, dan tidak berlebihan.
2. Jelaskan fakta yang sudah dikonfirmasi. Jangan mengubah rencana menjadi klaim fitur yang sudah tersedia.
3. Pisahkan informasi produk, panduan penggunaan, kebijakan, dan catatan pengembangan.
4. Hindari janji absolut seperti "bebas bug", "100% aman", atau "selalu tersedia".
5. Gunakan tanggal dengan format **DD Month YYYY** dan zona waktu Indonesia bila waktu spesifik relevan.
6. Tautkan sumber resmi yang dapat diperiksa.
7. Jangan memasukkan kredensial, data pelanggan, informasi pribadi, atau detail internal yang tidak ditujukan untuk publik.

## Status informasi

Gunakan label status berikut bila relevan:

- **Terkonfirmasi:** didukung oleh produk aktif, rilis, atau keputusan yang sudah ditetapkan.
- **Dalam pengembangan:** sedang dikerjakan dan belum boleh dianggap tersedia.
- **Direncanakan:** gagasan atau target yang belum menjadi komitmen rilis.
- **Ditangguhkan:** pekerjaan dihentikan sementara.
- **Tidak tersedia:** fitur atau layanan belum disediakan.
- **Perlu verifikasi:** informasi lama atau sumbernya belum cukup kuat.

Jangan menyimpulkan status hanya dari nama folder, branch, mockup, atau kode yang belum dirilis.

## Struktur halaman produk

Setiap halaman produk sebaiknya memuat:
1. Nama dan ringkasan.
2. Status dan tanggal peninjauan.
3. Pengguna atau kebutuhan yang dituju.
4. Fitur yang benar-benar tersedia.
5. Persyaratan dan kompatibilitas.
6. Cara mendapatkan atau menggunakan produk.
7. Penyimpanan dan pengelolaan data.
8. Keterbatasan yang diketahui.
9. Pembaruan versi.
10. Kanal bantuan.

Bagian yang belum diketahui harus ditandai "Belum dipublikasikan" atau dihilangkan. Jangan mengisi dengan perkiraan.

## Siklus pembaruan

- Perbarui halaman ketika ada rilis, perubahan layanan, perubahan kebijakan, atau koreksi fakta.
- Tinjau tautan dan status halaman secara berkala.
- Cantumkan tanggal peninjauan setelah isi benar-benar diperiksa.
- Catat perubahan penting di `CHANGELOG.md`.
- Gunakan Issue untuk menerima laporan, bukan sebagai pengganti dokumentasi final.

## Sumber dan verifikasi

Urutan sumber yang disarankan:
1. Rilis resmi dan aplikasi yang dapat diakses.
2. Pengumuman atau halaman resmi TCS.
3. Dokumentasi teknis resmi penyedia layanan.
4. Catatan pengembangan yang telah disetujui untuk publik.

Jika sumber berbeda, jangan memilih secara diam-diam. Tandai konflik dan verifikasi sebelum memperbarui klaim.

## Tanggung jawab

Repositori dikelola oleh pemilik TCS. Kontribusi atau usulan dari pengguna dapat ditinjau, tetapi tidak otomatis menjadi kebijakan atau pernyataan resmi sampai diterima dan digabungkan.
