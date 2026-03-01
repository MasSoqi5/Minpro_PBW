# Portofolio Website - Syauqi Etna Lazhuardhy

## Tampilan Section

1. Home (Hero section)
   - Foto profile
   - Nama dan Deskripsi

<img width="1910" height="1071" alt="image" src="https://github.com/user-attachments/assets/286e4c20-0994-4996-b935-b9fa0459618b" />

2. About Me
   - deskripsi diri
   - Skills dengan progress bar
   - Pengalaman organisasi dan project

<img width="1904" height="1068" alt="image" src="https://github.com/user-attachments/assets/00a97aac-3711-45d5-8771-467ffb06ece2" />

3. Certificates
   - 1 sertifikat dalam bentuk card layout digital grid

<img width="941" height="1069" alt="image" src="https://github.com/user-attachments/assets/7df003f0-ccec-40d6-bc44-5c976fbbaaf9" />


## Penjelasan pada section & fitur yang ada

### Struktur dasar HTML

- <!DOCTYPE html> → Menentukan bahwa ini adalah dokumen HTML5

- <html> → Elemen utama HTML

- <head> → Berisi metadata seperti title dan link CSS

- <meta name="viewport"> → Membuat website responsive di device mobile

- <link rel="stylesheet"> → Menghubungkan file CSS eksternal

- <body> → Tempat semua konten website ditampilkan

### Navbar

- <nav> → Digunakan untuk navigasi website

- class="navbar" → Digunakan untuk styling dengan CSS

- <ul> dan <li> → Membuat daftar menu

- href="#home" → Digunakan untuk scroll ke section tertentu


### CSS Navbar

- display: flex; → Mengatur layout horizontal

- justify-content: space-between; → Logo kiri, menu kanan

- position: fixed; → Navbar tetap di atas saat scroll


### Home Section (Hero Section)

- <section> → Membagi halaman menjadi bagian terstruktur

- id="home" → Agar bisa diakses dari navbar

Hero berisi:

Judul <h1>

Deskripsi <p>

Tombol <a>

Gambar <img>

### CSS Hero Section

- height: 100vh; → Tinggi penuh layar

- display: flex; → Membuat teks dan gambar sejajar

- background: linear-gradient; → Memberi efek warna gradasi


### About Me Section

Section ini berisi:

- Deskripsi diri

- Skill dengan progress bar
**Ada beberapa tambahan**
progress → Background bar

progress-bar → Isi bar

style="width: 90%" → Menentukan level skill

atau border-radius → Membuat sudut melengkung

Warna berbeda untuk membedakan skill level

- Pengalaman

**Menggunakan <ul> untuk daftar pengalaman

Struktur sederhana agar mudah dibaca**


### Certificates Section

Menggunakan CSS Grid untuk layout card.

- display: grid; → Mengaktifkan grid system

- auto-fit → Menyesuaikan jumlah kolom otomatis

- minmax() → Ukuran minimal dan maksimal kolom

adapun card styling yang berisi

- box-shadow → Memberi efek bayangan

- transition → Membuat animasi halus

- transform: translateY(-5px); → Efek hover naik


### Footer

untuk hak cipta yang diperlukan

### Responsive Design

Menggunakan Media Query:

@media(max-width: 768px) {
    .home-content {
        flex-direction: column;
    }
}

Penjelasan:

Jika layar < 768px

Layout berubah dari horizontal ke vertical

Cocok untuk tampilan mobile



## Teknologi yang digunakan

- HTML5 → Untuk struktur dasar website

- CSS3 → Untuk styling, layout, warna, dan responsive design

- Flexbox → Untuk layout horizontal seperti navbar dan hero section

- CSS Grid → Untuk layout card pada section certificates

- Media Query → Untuk membuat website responsif
