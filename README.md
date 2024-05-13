
## Cara Install

Berikut adalah langkah-langkah untuk menginstal dan menjalankan aplikasi:

1. Lakukan git clone repository ini:

    ```bash
    [git clone https://github.com/PowerGabb/absensi.git]
    ```

2. Pindah ke dalam folder yang telah di-clone:

    ```bash
    cd perpustakaan-yasfat
    ```

3. Buka terminal di folder tersebut dan jalankan:

    ```bash
    composer install
    ```

4. Setelah itu, jalankan:

    ```bash
    php artisan key:generate
    ```

5. Setelah itu, jalankan:

    ```bash
    npm install
    ```
6. Setelah itu, jalankan:

    ```bash
    npm run build
    ```

7. Buat database dan setup file `.env` dengan mengisi informasi yang diperlukan:

    ```bash
    cp .env
    ```

    Sesuaikan informasi database pada file `.env`:

    ```env
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=nama_database
    DB_USERNAME=nama_pengguna_database
    DB_PASSWORD=sandi_database
    ```

8. Lakukan migration dan seeding:

    ```bash
    php artisan migrate:fresh
    ```


