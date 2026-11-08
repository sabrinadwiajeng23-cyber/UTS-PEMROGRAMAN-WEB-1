BOOKNEST - TUGAS UTS PEMROGRAMAN WEB 1

CARA MENJALANKAN
1. Ekstrak folder tugas-uts-web1.
2. Buka folder menggunakan Visual Studio Code.
3. Jalankan index.html menggunakan browser atau ekstensi Live Server.
4. Login menggunakan akun demo:
   Email    : adminmoderator1booknest@gmail.com
   Password : 020304

HALAMAN
- index.html       : halaman login (login.html diarahkan ke sini)
- dashboard.html  : dashboard dengan greeting sesuai waktu lokal
- stok.html       : katalog, pencarian, filter, tambah, edit, dan hapus buku
- checkout.html   : tambah pesanan, ubah jumlah buku, data pemesan, pembayaran, riwayat
- tracking.html   : pencarian nomor DO dan simulasi progress pengiriman

STRUKTUR
tugas-uts-web1/
|-- index.html
|-- dashboard.html
|-- stok.html
|-- tracking.html
|-- checkout.html
|-- css/style.css
|-- js/script.js
|-- js/data.js
|-- assets/
|-- img/

CATATAN
- Aplikasi ini front-end saja. Data awal ada di js/data.js.
- Data katalog dan transaksi baru disimpan di localStorage browser.
- Login hanya simulasi dan tidak memakai server/database.
- Nomor DO demo: DO-2026-001 dan DO-2026-002.
- Untuk mengulang data awal, hapus localStorage dengan menu Developer Tools > Application > Local Storage.
