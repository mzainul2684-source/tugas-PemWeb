
# Tugas Praktikum Modul 5 - Bootstrap

## 1. Pengertian Bootstrap

**Pertanyaan:** Jelaskan apa itu Bootstrap dan apa kegunaannya!

**Jawaban:**

Bootstrap adalah framework frontend yang membantu kita membuat tampilan website dengan lebih mudah dan cepat. Bootstrap menyediakan berbagai komponen dan class CSS yang siap digunakan, seperti navbar, tombol, form, card, dan grid.

Dengan Bootstrap, kita tidak perlu membuat semua desain dari awal menggunakan CSS manual. Kita cukup menggunakan class yang sudah disediakan untuk mengatur tampilan website.

Selain itu, Bootstrap juga bisa digunakan untuk membuat website responsif, sehingga tampilannya dapat menyesuaikan ukuran layar laptop, tablet, maupun HP.

## 2. Memasang Bootstrap

**Pertanyaan:** Sebutkan cara-cara untuk mengimpor atau menggunakan Bootstrap pada project!

**Jawaban:**

Ada beberapa cara untuk menggunakan Bootstrap dalam project, yaitu:

1. **Menggunakan CDN**

   Kita cukup menambahkan link CSS dan JavaScript Bootstrap ke dalam file HTML. Cara ini paling gampang karena kita tidak perlu mengunduh atau menginstal Bootstrap secara manual. Namun, kita membutuhkan koneksi internet untuk memuat filenya.

2. **Download Bootstrap**

   Kita bisa mengunduh file CSS dan JavaScript dari website resmi Bootstrap, lalu menyimpannya di folder project. File tersebut kemudian dihubungkan ke HTML.

3. **Menggunakan NPM**

   Bootstrap bisa diinstal melalui terminal menggunakan perintah:

   `npm install bootstrap@5.3.8`

   Cara ini biasanya digunakan pada project yang menggunakan Node.js.

4. **Menggunakan package manager lain**

   Selain NPM, Bootstrap juga dapat dipasang menggunakan Yarn atau pnpm.

Pada tugas ini, saya menggunakan CDN karena lebih sederhana, mudah dan cocok untuk project HTML yang masih dasar.

## 3. Grid dan Breakpoint

**Pertanyaan:** Jelaskan mengenai class grid dan kegunaan breakpoint!

**Jawaban:**

Grid adalah sistem layout yang disediakan Bootstrap untuk mengatur susunan dan lebar elemen pada halaman website. Sistem grid Bootstrap menggunakan 12 kolom yang bisa dibagi sesuai kebutuhan.

Beberapa class yang biasa digunakan adalah:

- `container` untuk membungkus dan mengatur lebar konten.
- `row` untuk membuat baris.
- `col` untuk membuat kolom.
- `col-6` untuk membuat kolom dengan lebar setengah dari total 12 kolom.

Sementara itu, breakpoint digunakan untuk menentukan kapan tampilan website perlu berubah berdasarkan ukuran layar perangkat.

Berikut breakpoint yang tersedia di Bootstrap:

| Breakpoint | Ukuran Layar |
|------------|--------------|
| xs | Kurang dari 576px |
| sm | Mulai 576px |
| md | Mulai 768px |
| lg | Mulai 992px |
| xl | Mulai 1200px |
| xxl | Mulai 1400px |

Contohnya, class `col-12 col-md-6` membuat elemen memiliki lebar penuh pada layar kecil. Ketika ukuran layar mencapai 768px, lebarnya berubah menjadi setengah dari baris.

Jadi, grid dan breakpoint membantu kita membuat tampilan website lebih rapi dan tetap nyaman digunakan di berbagai perangkat.

## 4. Class Bootstrap

**Pertanyaan:** Sebutkan minimal lima class Bootstrap beserta kegunaannya!

**Jawaban:**

Bootstrap menyediakan banyak class yang bisa langsung digunakan untuk mengatur tampilan website. Berikut beberapa contohnya:

| Class | Kegunaan |
|-------|----------|
| `container` | Mengatur lebar konten agar lebih rapi. |
| `row` | Membuat baris dalam sistem grid. |
| `col-md-6` | Membuat kolom selebar setengah baris mulai layar medium. |
| `btn` | Memberikan tampilan dasar pada tombol. |
| `btn-success` | Membuat tombol berwarna hijau. |
| `bg-light` | Memberikan warna latar belakang terang. |
| `text-center` | Membuat teks berada di tengah. |
| `form-control` | Mengatur tampilan input pada form. |
| `card` | Membuat wadah konten berbentuk kartu. |
| `mt-3` | Memberikan jarak luar pada bagian atas elemen. |

Dengan class tersebut, kita bisa mengatur tampilan website tanpa harus menulis banyak CSS sendiri.

## 5. Gambar Responsif

**Pertanyaan:** Bagaimana cara agar foto atau gambar pada website responsif menyesuaikan ukuran layar perangkat?

**Jawaban:**

Agar gambar bisa menyesuaikan ukuran layar, kita dapat menggunakan class `img-fluid` dari Bootstrap.

Class ini membuat gambar mengikuti lebar elemen pembungkusnya dan menjaga perbandingan ukuran gambar agar tidak terlihat gepeng atau melebar secara berlebihan.

Contoh penggunaannya:

```html
<img src="gambar.jpg" class="img-fluid" alt="Contoh gambar">
```

Pada kode tersebut:

- `src` digunakan untuk menentukan lokasi gambar.
- `img-fluid` digunakan agar gambar responsif.
- `alt` digunakan untuk memberikan deskripsi gambar.

Jadi, dengan menggunakan `img-fluid`, gambar dapat menyesuaikan ukuran layar secara otomatis tanpa harus mengatur lebar dan tingginya secara manual untuk setiap perangkat.

