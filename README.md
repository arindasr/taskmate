# 🎓 Tugas Kelompok 5 - Bahasa Pemrograman 1
### TASKMATE - Web Manajemen & Reminder Tugas

Repository ini berisi *source code* aplikasi **TASKMATE**, sebuah platform berbasis web yang dirancang khusus untuk membantu mencatat, mengelola, dan memberikan pengingat (*reminder*) tugas kuliah atau harian. Proyek ini dibuat untuk memenuhi tugas kelompok pada mata kuliah Bahasa Pemrograman 1.

## 👥 Anggota Kelompok 5
* Arinda Setyo Rini
* Ansar Abdi Dwi Saputra
* Dziqri Restu Ramanda

## 🚀 Fitur Utama
* **Dashboard Informatif:** Menampilkan ringkasan seluruh tugas yang aktif dan mendekati *deadline*.
* **Manajemen Tugas (CRUD):** Bisa menambah tugas baru, melihat daftar tugas, mengedit detail/status tugas, dan menghapus tugas yang sudah selesai.
* **Sistem Reminder:** Fitur pengingat berbasis tanggal jatuh tempo (*due date*) agar tidak ada tugas yang terlewat.
* **Autentikasi Pengguna:** Sistem Login dan Logout yang aman untuk menjaga privasi data tugas masing-masing pengguna.

## 🛠️ Teknologi yang Digunakan
* **Backend:** PHP (Native)
* **Database:** MySQL / MariaDB
* **Frontend:** HTML, CSS, JavaScript (Custom Styling)
* **Tools:** Visual Studio Code, XAMPP / Laragon

## 📁 Struktur Folder Proyek
Proyek ini dikembangkan dengan struktur folder yang rapi dan terorganisir:
* `assets/css/` - Menyimpan file *styling* (`dashboard.css`, `form.css`).
* `assets/js/` - Menyimpan file interaktivitas JavaScript (`dashboard.js`, `form.js`).
* `includes/` - Berisi modul logika utama:
  * `auth.php` - Validasi login dan hak akses pengguna.
  * `db.php` - Koneksi utama ke database MySQL.
  * `task_functions.php` - Kumpulan fungsi (*logic*) untuk memproses data tugas.
* `config.php` - File konfigurasi global sistem.
* `dashboard.php` - Halaman utama visualisasi daftar tugas pengguna.
* `form.php` - Halaman formulir untuk tambah dan edit tugas.
* `logout.php` - Proses menghapus sesi login pengguna.
