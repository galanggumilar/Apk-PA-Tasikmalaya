# PA-Tasikmalaya Panjar Calculator

Deskripsi singkat:  
Aplikasi berbasis CodeIgniter 4 untuk menghitung biaya panjar perceraian di Pengadilan Agama Tasikmalaya.

## Fitur
- Dropdown dinamis kecamatan → desa via AJAX
- Perhitungan biaya panjar cerai talak & gugat
- Laporan penggunaan fitur (save sekali per kalkulasi)

## Tech Stack
- PHP 8 + CodeIgniter 4  
- MySQL  
- Bootstrap 5, jQuery  
- Hosted on InfinityFree (HTTPS)

## Instalasi Lokal
1. Clone repo  
2. `cp env.example .env` lalu isi credential DB  
3. `composer install`  
4. Setup database dengan `php spark migrate` atau import `.sql`  
5. `php spark serve` → akses `http://localhost:8080`

## Cara Deploy
- Upload ke hosting (CI4: pindahkan isi `public/` ke `htdocs/`)  
- Sesuaikan `baseURL` di `app/Config/App.php`  
- Pastikan assets dimuat via HTTPS  

## Screenshot
![Form Cerai Talak](docs/cerai_talak_form.png)
