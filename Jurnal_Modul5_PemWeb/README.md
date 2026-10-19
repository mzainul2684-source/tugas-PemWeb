# Tugas Praktikum Modul 5 - Bootstrap

## 1. Pengertian Bootstrap

Bootstrap adalah framework frontend yang digunakan untuk mempermudah kita dalam membuat tampilan website. Di dalam Bootstrap sudah tersedia berbagai komponen dan class CSS yang bisa langsung digunakan, seperti navbar, tombol, form, card, dan grid. Jadi, kita tidak perlu membuat semua desain dari awal menggunakan CSS sendiri. Selain mempermudah pengerjaan, Bootstrap juga membantu membuat website menjadi responsif, sehingga tampilannya bisa menyesuaikan ukuran layar perangkat seperti laptop, tablet, maupun HP.

## 2. Memasang Bootstrap

Ada beberapa cara untuk menggunakan Bootstrap dalam sebuah project. Cara pertama adalah menggunakan CDN, yaitu dengan menambahkan link CSS dan JavaScript Bootstrap ke dalam file HTML tanpa perlu mengunduhnya terlebih dahulu. Cara kedua adalah dengan mengunduh file Bootstrap dari website resminya, lalu menyimpannya di folder project agar bisa digunakan secara lokal. Selain itu, Bootstrap juga bisa diinstal menggunakan NPM melalui perintah `npm install bootstrap@5.3.8` atau menggunakan package manager lain seperti Yarn dan pnpm. Untuk tugas ini, saya menggunakan CDN karena caranya lebih praktis dan tidak memerlukan proses instalasi tambahan.

## 3. Grid dan Breakpoint

Grid adalah sistem layout pada Bootstrap yang digunakan untuk mengatur susunan dan lebar elemen dalam sebuah halaman website. Bootstrap menggunakan sistem 12 kolom yang bisa kita bagi sesuai kebutuhan. Beberapa class yang sering digunakan adalah `container` untuk membungkus konten, `row` untuk membuat baris, dan `col` untuk mengatur kolom. Sementara itu, breakpoint digunakan untuk menentukan perubahan tampilan berdasarkan ukuran layar perangkat. Bootstrap memiliki beberapa breakpoint, yaitu `xs` untuk layar di bawah 576px, `sm` mulai 576px, `md` mulai 768px, `lg` mulai 992px, `xl` mulai 1200px, dan `xxl` mulai 1400px. Contohnya, ketika kita menggunakan class `col-12 col-md-6`, elemen akan memiliki lebar penuh pada layar kecil dan berubah menjadi setengah lebar ketika ukuran layar mencapai 768px. Dengan adanya grid dan breakpoint, tampilan website bisa tetap rapi meskipun dibuka menggunakan perangkat yang berbeda.

## 4. Class Bootstrap

Bootstrap menyediakan banyak class yang bisa kita gunakan untuk mengatur tampilan website tanpa harus menulis CSS secara manual. Contohnya, class `container` digunakan untuk mengatur lebar konten agar lebih rapi, sedangkan `row` digunakan untuk membuat baris dalam sistem grid. Ada juga `col-md-6` yang digunakan untuk membuat kolom dengan lebar setengah baris pada layar berukuran medium ke atas. Untuk membuat tombol, kita bisa menggunakan class `btn`, lalu menambahkan `btn-success` jika ingin memberikan warna hijau. Selain itu, class `bg-light` digunakan untuk memberikan warna latar belakang terang, `text-center` untuk membuat teks berada di tengah, `form-control` untuk mengatur tampilan input, `card` untuk membuat kotak konten, dan `mt-3` untuk memberikan jarak pada bagian atas elemen. Dengan menggunakan class-class tersebut, kita bisa membuat tampilan website dengan lebih cepat dan mudah.

## 5. Gambar Responsif

Agar gambar pada website bisa menyesuaikan ukuran layar perangkat, kita dapat menggunakan class `img-fluid` yang sudah disediakan Bootstrap. Class ini membuat gambar mengikuti lebar elemen pembungkusnya tanpa melebihi ukuran aslinya, sehingga gambar tidak keluar dari area yang tersedia. Selain itu, tinggi gambar akan menyesuaikan secara otomatis agar bentuknya tetap proporsional. Contoh penggunaannya adalah `<img src="gambar.jpg" class="img-fluid" alt="Contoh gambar">`. Pada kode tersebut, `src` digunakan untuk menentukan lokasi gambar, `img-fluid` membuat gambar responsif, dan `alt` memberikan deskripsi gambar. Jadi, dengan menggunakan class ini, kita nggak perlu mengatur ukuran gambar secara manual untuk setiap perangkat.

