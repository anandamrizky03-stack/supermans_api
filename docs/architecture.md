# Arsitektur Proyek - SUPERMANS Backend (Laravel)

Proyek ini menggunakan pola arsitektur **MVC (Model-View-Controller)** yang difokuskan sebagai penyedia RESTful API untuk aplikasi mobile.

## Struktur Direktori Utama
- **`app/Models/`**: Menyimpan definisi entitas database dan relasinya.
- **`app/Http/Controllers/API/`**: Mengelola logika *request* dan *response* API.
- **`app/Http/Requests/`**: Menangani validasi input data dari *client*.
- **`app/Http/Resources/`**: Mengatur format *output* JSON standar.
- **`routes/api.php`**: Mendaftarkan *endpoint* API.
- **`database/migrations/`**: Mengelola skema dan pembuatan tabel database.