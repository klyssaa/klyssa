nama : Klyssa Fridea

nim : 362358302157

kelas : 2b trpl

Pertanyaan Evaluasi

1. Apa yang dimaksud dengan Laravel Sanctum?
   Laravel Sanctum: Paket autentikasi untuk mengamankan API dan SPA dengan token API sederhana.
2. Bagaimana cara mengelola token autentikasi di Laravel?
   Mengelola Token Autentikasi: Buat token dengan createToken, hapus token dengan revokeToken, dan lindungi route dengan middleware auth:sanctum.
3. Sebutkan langkah-langkah untuk menambahkan otorisasi berbasis peran dalam API
   Otorisasi Berbasis Peran:

Tambah kolom role di tabel users.
Buat middleware untuk cek peran.
Daftarkan middleware di Kernel.php.
Terapkan middleware di route sesuai peran.
