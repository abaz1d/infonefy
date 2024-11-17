# InfoNefy

## 1. Nama Sistem
**InfoNefy**

## 2. Deskripsi Umum
InfoNefy adalah sebuah platform berbasis web yang berfungsi sebagai portal informasi terkini serta daftar lowongan kerja yang dapat diakses oleh pengguna secara mudah dan cepat. Website ini dirancang untuk membantu pengguna mendapatkan informasi yang relevan dan terpercaya dalam satu tempat. Sistem ini dikembangkan sebagai bagian dari pembelajaran dan proyek tugas, bukan untuk tujuan komersial.

## 3. Tujuan Pengembangan Sistem
- Menyediakan berita terkini yang akurat dari berbagai sumber terpercaya.
- Memberikan informasi lowongan pekerjaan secara lengkap dan terorganisir.
- Mempermudah akses informasi melalui desain yang responsif dan ramah pengguna.

## 4. Fitur Utama Sistem

### 1. Halaman Beranda
- Menampilkan informasi umum mengenai InfoNefy, fitur utama, serta tautan cepat ke halaman-halaman penting seperti berita, lowongan kerja, dan tentang kami.

### 2. Halaman Berita
- Berisi daftar artikel berita terkini dari berbagai kategori, seperti teknologi, ekonomi, dan pendidikan.
- Dilengkapi dengan fitur pencarian (search) untuk memudahkan pengguna menemukan berita tertentu berdasarkan kata kunci.
- Menerapkan infinite scroll sebagai metode pagination untuk memberikan pengalaman membaca yang lebih nyaman tanpa perlu mengklik tombol berikutnya.

### 3. Halaman Lowongan Kerja
- Menampilkan daftar lowongan pekerjaan yang diperbarui secara berkala.
- Pengguna dapat mencari lowongan kerja dengan menggunakan fitur pencarian (search) berdasarkan kategori, lokasi, atau posisi pekerjaan.
- Menggunakan infinite scroll untuk pagination agar pengguna dapat menelusuri lebih banyak lowongan secara berkelanjutan tanpa memuat ulang halaman.

### 4. Halaman Tentang Kami (About)
- Memberikan informasi singkat mengenai tujuan, visi, dan misi InfoNefy, serta layanan yang ditawarkan kepada pengguna.

## 5. Teknologi yang Digunakan

### Front-End:
- HTML dan CSS (menggunakan framework TailwindCSS untuk gaya responsif).
- Library JavaScript jQuery untuk menangani permintaan data API.
- FontAwesome untuk menampilkan ikon pada antarmuka pengguna.

### Back-End:
- API IDX (PT Bursa Efek Indonesia) untuk mengambil data terkini tentang pasar modal.
- API JobStreet by Seek untuk mendapatkan daftar lowongan kerja terkini.  
  *Catatan: Penggunaan API ini semata-mata untuk tujuan pembelajaran dan memenuhi tugas proyek, tanpa dimaksudkan untuk kepentingan komersial.*

### Hosting:
- Website dihosting di platform gratis Vercel, sehingga dapat diakses secara online dengan mudah dan cepat.

## 6. Keunggulan Sistem
- **Desain Responsif**: Dapat diakses dengan baik di perangkat desktop maupun mobile.
- **Kemudahan Navigasi**: Struktur website sederhana dan intuitif sehingga pengguna dapat dengan mudah menemukan informasi yang dibutuhkan.
- **Informasi Terpercaya**: Data lowongan kerja dan berita dikurasi dari sumber terpercaya melalui API.
- **Ikon Menarik**: Penggunaan FontAwesome untuk meningkatkan pengalaman visual pengguna.

## 7. Target Pengguna
- Individu yang membutuhkan informasi pasar modal secara ringkas.
- Profesional dan pelajar yang sedang mencari peluang karir.
- Komunitas yang membutuhkan platform informasi yang terorganisir.

## 8. Alur Kerja Sistem
1. Pengguna membuka halaman utama InfoNefy.
2. Pengguna memilih salah satu fitur utama: Berita, Lowongan Kerja, atau Tentang Kami.
3. Jika memilih halaman berita, pengguna dapat membaca artikel atau melihat daftar berita terkini yang diambil dari API IDX.
4. Jika memilih halaman lowongan kerja, pengguna dapat menelusuri pekerjaan sesuai kategori atau lokasi yang diambil dari API JobStreet.

## 9. Akses Website dan Source Code
- Website InfoNefy dapat diakses melalui tautan berikut:  
  [https://infonefy.vercel.app/](https://infonefy.vercel.app/)
- Source code dari sistem ini dapat ditemukan di repositori GitHub:  
  [https://github.com/abaz1d/infonefy](https://github.com/abaz1d/infonefy)

## 10. Screenshot Sistem Informasi
(Anda dapat menambahkan gambar-gambar tampilan sistem di bawah bagian ini)

## 11. Daftar Pustaka
- **PT Bursa Efek Indonesia (IDX)**  
  API IDX digunakan untuk mengambil data terkait informasi pasar saham. Informasi lebih lanjut dapat diakses di: [https://www.idx.co.id](https://www.idx.co.id).
  
- **JobStreet by SEEK**  
  API JobStreet digunakan untuk mengambil data lowongan pekerjaan. Informasi lebih lanjut dapat diakses di: [https://www.jobstreet.co.id](https://www.jobstreet.co.id).
