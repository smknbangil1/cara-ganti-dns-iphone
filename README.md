# cara-ganti-dns-iphone
Terkadang HP IPhone susah terhubung ke jaringan hotspot mikrotik, hal itu disebabkan oleh DNS internal iphone tidak mendukung jaringan hotspot mikrotik, untuk itulah kita perlu mengganti DNS iphone secara manual, untuk mengganti DNS di jaringan Wi-Fi di iPhone, ikuti langkah-langkah berikut:

1. **Buka Pengaturan (Settings)** di iPhone Anda.
2. **Pilih "Wi-Fi"** dari menu Pengaturan.
3. Cari jaringan Wi-Fi yang sedang terhubung, kemudian **ketuk ikon "i" (informasi)** di sebelah nama jaringan tersebut.
4. Gulir ke bawah hingga menemukan opsi **"Configure DNS"** (Konfigurasi DNS).
5. Ketuk **"Configure DNS"**, kemudian ubah dari **"Automatic"** menjadi **"Manual"**.
6. Setelah itu, tambahkan DNS baru dengan mengetuk **"Add Server"**, lalu masukkan alamat DNS yang Ada di Mikrotik Anda, seperti:
   - `172.16.8.1`   
7. Setelah selesai, ketuk **"Save"** untuk menyimpan perubahan.

DNS Anda kini telah diubah di jaringan Wi-Fi tersebut.
