# Aplikasi Penyewaan Tempat (Admin & User)

Aplikasi web sederhana tanpa backend untuk alur 2 peran:

- **Admin**: menambahkan dan menghapus data tempat sewa.
- **User**: membuat pesanan berdasarkan tempat yang sudah dibuat admin, termasuk memasukkan data customer dan permintaan customer.

## Fitur

- Menu/tab terpisah antara **Admin** dan **User**.
- Admin dapat input tempat: nama, lokasi, harga per hari, fasilitas.
- User dapat input pesanan: nama user, nama customer, pilih tempat, tanggal, durasi, dan permintaan customer.
- Total biaya dihitung otomatis berdasarkan tempat dan durasi.
- Riwayat pesanan disimpan di browser (`localStorage`).

## Menjalankan

Buka langsung file `index.html` di browser, atau jalankan server lokal:

```bash
python3 -m http.server 8000
```

Lalu akses `http://localhost:8000`.
