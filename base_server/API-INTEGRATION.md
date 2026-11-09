# Integrasi API Ruang Laundry

Aplikasi Ruang Laundry menggunakan API yang dibuat dengan Node.js untuk menghubungkan web dengan basis data. Melalui web, pengguna dapat mengelola data pelanggan, layanan, dan pesanan.

Web menggunakan API untuk menampilkan dan memperbarui data. Metode yang digunakan adalah `GET` untuk melihat data, `POST` untuk menambahkan, `PUT` untuk mengubah, dan `DELETE` untuk menghapus.

Endpoint utama:

```text
http://localhost:3000/api/laundry
```

Endpoint tersebut memiliki fitur pelanggan (`/customers`), layanan (`/services`), dan pesanan (`/orders`). API juga dapat diuji secara manual menggunakan Postman.
