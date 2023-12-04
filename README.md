# Redesign Landing Page Qwords

Proyek ini bertujuan untuk melakukan redesign pada halaman depan situs Qwords menggunakan Laravel dan Bootstrap.

## Langkah-langkah Clone Repository:

1. **Persiapan Prasyarat:**
   Pastikan sudah terpasang Git dan Composer pada komputer Anda sebelum melanjutkan.

2. **Clone Repositori:**
   Untuk mengkloning repositori ini, buka terminal atau command prompt, dan jalankan perintah berikut:

    ```bash
    git clone https://github.com/viraalfita/qwords.git
    ```

3. **Instalasi Dependensi:**
   Setelah repositori berhasil di-clone, masuk ke direktori proyek dan jalankan perintah berikut untuk menginstal semua dependensi yang diperlukan:

    ```bash
    cd qwords
    composer install
    ```

4. **Konfigurasi Environment:**
   Salin file `.env.example` menjadi `.env`:

    ```bash
    cp .env.example .env
    ```

    Kemudian lakukan konfigurasi pada file `.env` sesuai dengan pengaturan database dan konfigurasi lainnya yang diperlukan.

5. **Generate App Key:**
   Jalankan perintah untuk menghasilkan kunci aplikasi:

    ```bash
    php artisan key:generate
    ```

6. **Migrasi Database:**
   Jalankan migrasi untuk membuat skema database yang diperlukan:

    ```bash
    php artisan migrate
    ```

7. **Jalankan Server Lokal:**
   Terakhir, jalankan server lokal menggunakan perintah:

    ```bash
    php artisan serve
    ```

    Setelah server berjalan, buka browser dan akses `http://localhost:8000` untuk melihat halaman depan redesign dari situs Qwords.

## Kontribusi:

Jika Anda ingin berkontribusi pada proyek ini, silakan buat _pull request_ dengan perubahan yang diusulkan. Kami sangat menyambut kontribusi dari komunitas!
