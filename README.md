# Aplikasi Pomodoro Timer dan Daftar Tugas

Aplikasi ini menggabungkan fitur **Pomodoro Timer** dan **To-Do List** yang dirancang untuk meningkatkan produktivitas dengan teknik Pomodoro dan membantu Anda mengelola tugas dengan efisien. 

## Deskripsi
- **Pomodoro Timer**: Sebuah timer untuk membantu Anda bekerja dalam interval waktu, biasanya 25 menit, diikuti dengan istirahat 5 menit.
- **Daftar Tugas**: Mengelola tugas-tugas yang harus diselesaikan, menandai tugas yang sudah selesai, serta menetapkan tenggat waktu untuk setiap tugas.
- **Mode Gelap**: Aplikasi ini mendukung mode gelap untuk kenyamanan mata di malam hari.

## Fitur
- **Timer Pomodoro**: Atur durasi waktu kerja dan istirahat.
- **Pencatatan Sesi**: Melacak jumlah sesi yang sudah diselesaikan dan total waktu belajar yang sudah dijalani.
- **Daftar Tugas**: Menambahkan tugas baru, menetapkan tenggat waktu, dan menandai tugas yang telah selesai.
- **Mode Gelap**: Beralih antara mode terang dan gelap untuk kenyamanan visual.
- **Menyimpan Tugas Secara Lokal**: Data tugas disimpan di localStorage sehingga tetap ada meskipun halaman dimuat ulang.

## Teknologi yang Digunakan
- **HTML5** untuk struktur halaman
- **CSS3** untuk styling dan tema responsif menggunakan **Bootstrap 5**
- **JavaScript** untuk logika timer Pomodoro dan manajemen daftar tugas
- **localStorage** untuk menyimpan data tugas di browser

## Instalasi

Untuk mencoba aplikasi ini, Anda cukup mendownload atau meng-clone repositori ini dan membuka file `index.html` di browser favorit Anda.

Langkah-langkah:
1. Clone repositori ini:
 [https://github.com/anggraini-27/UAS-KBP-A.git]
2. Buka file `index.html` di browser.

## Cara Menggunakan

### Pomodoro Timer
1. **Setel Durasi Waktu Kerja dan Waktu Istirahat**: Anda dapat mengatur waktu kerja dan waktu istirahat sesuai kebutuhan. Secara default, waktu kerja adalah 25 menit dan waktu istirahat adalah 5 menit.
2. **Mulai Timer**: Klik tombol **Mulai** untuk memulai sesi kerja.
3. **Jeda Timer**: Klik tombol **Jeda** untuk menghentikan timer sementara.
4. **Reset Timer**: Klik tombol **Reset** untuk mengatur ulang timer ke 00:00.
5. Setelah selesai setiap sesi, kutipan motivasi akan muncul untuk memberi semangat.

### Daftar Tugas
1. **Menambahkan Tugas**: Ketikkan tugas baru di kolom input dan klik **Simpan Tugas**.
2. **Menambahkan Tenggat Waktu**: Anda dapat menambahkan tenggat waktu (opsional) untuk setiap tugas.
3. **Menandai Tugas sebagai Selesai**: Klik tombol ceklis (✔) untuk menandai tugas yang telah selesai.
4. **Menghapus Tugas**: Klik tombol hapus (✖) untuk menghapus tugas dari daftar.

### Mode Gelap
Klik tombol **Mode Gelap** di bagian atas untuk beralih antara mode terang dan mode gelap.


## Skrip JavaScript

### Pomodoro Timer
- Timer menggunakan `setInterval()` untuk menghitung mundur waktu kerja dan istirahat.
- Ketika sesi selesai, timer akan beralih antara sesi kerja dan istirahat.
- Waktu yang sudah dihabiskan dicatat dan ditampilkan, serta kutipan motivasi akan muncul.

### Daftar Tugas
- Menyimpan daftar tugas di **localStorage**, sehingga data tetap ada meskipun halaman dimuat ulang.
- Setiap tugas dapat dihapus, ditandai selesai, atau memiliki tenggat waktu.

### Mode Gelap
- Tombol **Mode Gelap** mengubah tema aplikasi dengan menambahkan kelas CSS `dark-mode` ke elemen `<body>`.

## Peningkatan yang Dapat Dilakukan
- **Pengingat Notifikasi**: Menambahkan pengingat untuk tugas atau sesi yang akan datang.
- **Pencatatan Detail Tugas**: Menambahkan fitur untuk mengedit detail tugas setelah ditambahkan.
- **Tema Kustom**: Membuat lebih banyak opsi tema untuk menyesuaikan pengalaman pengguna.

## Lisensi
Aplikasi ini dilisensikan di bawah **MIT License**.

## Kontribusi
Silakan fork repositori ini dan kirimkan pull request jika Anda memiliki fitur atau perbaikan yang ingin dibagikan.

---

Terima kasih telah menggunakan aplikasi **Pomodoro Timer & Daftar Tugas** ini. Semoga membantu Anda untuk tetap fokus dan produktif!

