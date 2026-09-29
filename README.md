
**PRODUCT REQUIREMENTS DOCUMENT (PRD)**
Website Profil SMAS ANGKASA 1 Jakarta

**Latar Belakang**
SMAS ANGKASA 1 Jakarta membutuhkan media informasi digital yang dapat diakses secara luas oleh calon siswa, orang tua, alumni, dan masyarakat umum. Selama ini informasi mengenai sekolah masih tersebar di berbagai kanal dan belum terpusat, sehingga menyulitkan masyarakat untuk mendapatkan data resmi. Oleh karena itu, dibangunlah sebuah website profil sekolah yang berfungsi sebagai satu pintu informasi yang memuat profil, jurusan, dan kontak sekolah secara terstruktur, ringan, dan mudah diakses. Website ini dikembangkan menggunakan HTML dan CSS murni tanpa framework, sehingga proses pemeliharaannya sederhana dan kecepatan aksesnya tetap optimal.

**Tujuan Produk**
Produk ini memiliki empat tujuan utama. Pertama, menyediakan informasi resmi dan terpusat mengenai profil SMAS ANGKASA 1 Jakarta. Kedua, memperkenalkan jurusan atau program peminatan yang tersedia kepada calon siswa baru. Ketiga, menyediakan kanal komunikasi resmi antara masyarakat dengan pihak sekolah melalui halaman kontak. Keempat, menjadi sarana publikasi identitas sekolah, meliputi logo, visi misi, serta sambutan kepala sekolah, agar citra sekolah semakin dikenal publik.

**Target Pengguna**
Website ini menyasar beberapa kelompok pengguna. Calon siswa baru membutuhkan informasi mengenai jurusan, fasilitas, dan cara menghubungi sekolah. Orang tua siswa mencari informasi resmi, kontak, dan profil sekolah sebagai bahan pertimbangan. Alumni ingin mengetahui perkembangan serta kontak sekolah. Masyarakat umum membutuhkan alamat, nomor telepon, dan informasi publik lainnya. Sementara itu, guru dan staf sekolah dapat memanfaatkannya sebagai referensi resmi identitas sekolah.

**Ruang Lingkup**
Lingkup pengembangan pada versi pertama ini mencakup tiga halaman utama, yaitu Halaman Beranda (Home), Halaman Jurusan, dan Halaman Kontak, yang saling terhubung melalui menu navigasi. Desain yang digunakan bersifat responsif sehingga nyaman diakses melalui perangkat mobile maupun desktop. Selain itu, tersedia form kontak dalam bentuk antarmuka saja tanpa backend. Adapun hal-hal yang tidak termasuk dalam lingkup versi ini antara lain CMS atau panel admin, sistem login dan autentikasi, database, fitur pengiriman email sungguhan, blog berita dinamis, galeri foto dinamis, serta dukungan multi-bahasa.

**Arsitektur dan Teknologi**
Website ini dibangun menggunakan HTML5 sebagai bahasa markup dan CSS3 sebagai pengatur tampilan, di mana seluruh kode CSS diletakkan pada file terpisah bernama style.css. Struktur filenya terdiri dari empat berkas, yaitu index.html, jurusan.html, kontak.html, dan style.css, yang semuanya berada dalam satu folder bernama ProfilSMA. Sistem menggunakan font bawaan perangkat seperti Segoe UI dan Tahoma agar ringan, serta ikon berbasis emoji Unicode untuk mempercantik tampilan. Untuk publikasi, website dapat diunggah ke layanan hosting gratis seperti Netlify, GitHub Pages, atau Vercel.

**Kebutuhan Fungsional**
Pada Halaman Beranda, website harus menampilkan header yang berisi logo sekolah, nama sekolah, dan menu navigasi. Halaman ini juga harus memuat sambutan Kepala Sekolah beserta fotonya, penjelasan Visi sekolah, serta daftar Misi sekolah dalam bentuk bullet list minimal lima poin. Di bagian bawah, ditampilkan footer berisi copyright.
Pada Halaman Jurusan, website harus menampilkan daftar jurusan minimal empat jurusan menggunakan elemen h2, p, dan ul. Selain itu, terdapat tabel yang menampilkan data jumlah siswa per jurusan dengan kolom No, Jurusan, Kelas XI, Kelas XII, dan Total Siswa. Header dan footer pada halaman ini harus konsisten dengan halaman lainnya.
Pada Halaman Kontak, website harus menampilkan informasi kontak berupa alamat, nomor telepon, email, dan jam operasional. Halaman ini juga dilengkapi form kontak dengan tiga input, yaitu nama (text), email (email), dan pesan (textarea), serta tombol submit "Kirim Pesan". Header dan footer kembali harus konsisten dengan halaman lain.
Untuk Navigasi Global, menu Home, Jurusan, dan Kontak harus dapat diklik dan berpindah halaman dengan benar. Menu yang sedang aktif ditandai dengan class active, dan logo di header idealnya dapat diklik untuk kembali ke halaman Beranda.

**Kebutuhan Non-Fungsional**
Dari sisi kualitas, website ini harus responsif sehingga tampil baik di desktop, tablet, maupun mobile. Tampilannya juga harus konsisten dari segi warna, font, dan tata letak di seluruh halaman. Website harus ringan karena tidak menggunakan library eksternal, sehingga waktu muatnya cepat. Dari sisi pemeliharaan, kode harus mudah diperbarui karena CSS dipisahkan di file tersendiri. Website juga harus aksesibel dengan memanfaatkan tag semantik seperti header, nav, main, dan footer, serta kompatibel dengan browser modern seperti Chrome, Firefox, Edge, dan Safari versi terbaru.

**Panduan Desain**
Dari segi visual, website ini menggunakan palet warna yang terdiri atas biru tua #003366 untuk header, footer, judul, dan tombol; biru terang #00509e untuk efek hover dan aksen; putih #ffffff untuk latar card dan teks header; abu terang #f4f7f6 untuk latar halaman; serta abu netral #333333 untuk teks utama. Tipografi menggunakan font Segoe UI dengan fallback Tahoma, Geneva, Verdana, dan sans-serif, dengan ukuran judul nama sekolah sekitar 1.6rem dan line height 1.6. Logo sekolah ditampilkan dengan ukuran 90px × 90px dan dapat disesuaikan melalui file style.css.

**Kriteria Penerimaan**
Sebuah halaman dinyatakan selesai apabila ketiga file HTML dapat dibuka tanpa error, menu navigasi berfungsi di semua halaman, logo tampil dengan ukuran 90px dan proporsional, Halaman Beranda memuat Sambutan, Visi, dan Misi, Halaman Jurusan menampilkan empat jurusan beserta tabel data siswa, Halaman Kontak menampilkan form dengan input text, email, textarea, dan button, tampilan responsif di layar mobile, seluruh CSS berada di file style.css terpisah, serta footer copyright muncul di setiap halaman.

**Rencana Pengembangan Selanjutnya**
Ke depannya, website ini direncanakan berkembang secara bertahap. Pada versi 1.1 akan ditambahkan halaman galeri foto. Versi 1.2 akan menambahkan halaman berita atau pengumuman serta halaman ekstrakurikuler. Pada versi 2.0, form kontak akan dilengkapi backend menggunakan PHP atau Node.js agar pesan benar-benar terkirim. Selanjutnya, pada versi 2.1 akan dikembangkan panel admin (CMS) sederhana, dan pada versi 2.2 akan ditambahkan dukungan multi-bahasa (Indonesia dan Inggris).

Penutup
PRD ini disusun sebagai acuan resmi dalam pengembangan Website Profil SMAS ANGKASA 1 Jakarta. Dokumen ini bersifat dinamis dan dapat diperbarui seiring dengan kebutuhan sekolah dan masukan dari para pemangku kepentingan. Dengan adanya PRD ini, diharapkan proses pengembangan dapat berjalan terarah, terukur, dan menghasilkan produk digital yang bermanfaat bagi seluruh civitas akademika serta masyarakat luas.
