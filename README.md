# SEWASINI 🏠
**Platform Digital Pencarian dan Pemesanan Kos/Kontrakan**

SEWASINI adalah proyek kerja praktek sistem informasi berbasis web yang dirancang untuk mempermudah pencari hunian menemukan kos atau kontrakan, serta membantu pemilik properti mengelola penyewaan secara efisien. Proyek ini dibangun menggunakan **Framework Laravel** dan bahasa pemrograman **PHP**.

---

## 📅 Waktu Pengerjaan
Proyek ini dikembangkan dalam kurun waktu:  
**15 Januari 2026 – 27 April 2026**

---

## 🏗️ Arsitektur Sistem (Diagram)

### 📊 Diagram Class
![Class Diagram](./img/Diagram.png)

### 👤 Use Case Diagram
![Use Case Diagram](./img/Use.png)

---

## 👥 Hak Akses User
Sistem ini mendukung 4 level otoritas pengguna:
1. **Super Admin**: Akses penuh ke seluruh sistem dan manajemen admin.
2. **Admin**: Verifikasi properti, verifikasi pembayaran, dan pengelolaan laporan.
3. **Pemilik Kos**: Mengelola data kos, memantau hunian, dan penarikan saldo (Withdrawal).
4. **Pencari Kos**: Mencari unit, melakukan booking, dan melihat riwayat transaksi.

---

## 📸 Dokumentasi Tampilan

<details>
  <summary>Klik untuk melihat screenshot</summary>

  #### Halaman Awal
  ![Home Page](./img/home.png)

  #### Halaman Login
  ![Login Page](./img/login.png)

  #### Halaman Dashboard
  ![Dashboard Page](./img/dash.png)
</details>

---

## ⚙️ Fitur Utama & Integrasi
- **Manajemen Finansial**: Fitur bagi hasil (Fee Admin 5%) dan sistem saldo pemilik.
- **Sistem Withdrawal**: Penarikan dana otomatis bagi pemilik properti yang terverifikasi admin.
- **Multi-Photo Galeri**: Setiap tipe kamar dapat memiliki banyak foto.
- **Integrasi API**:
  - [Midtrans](https://midtrans.com/) - Payment Gateway untuk pembayaran digital.
  - [Indoregion](https://github.com/azishapidin/indoregion) - Basis data wilayah administratif Indonesia.

---

## ⚠️ Keterbatasan Sistem
Meskipun fungsional, sistem saat ini memiliki beberapa keterbatasan:
- [ ] Pengguna (Pemilik/Pencari) belum dapat mengubah profil secara mandiri.
- [ ] Struktur input tipe kamar masih kaku (Satu postingan fokus pada satu tipe/unit utama).
- [ ] Filter pencarian detail (seperti fasilitas spesifik atau range harga) masih dalam pengembangan.
- [ ] Sinkronisasi otomatis Midtrans ke status database masih memerlukan penyempurnaan (Webhook).
- [ ] Sistem notifikasi otomatis kepada user belum diimplementasikan.

---

## 👨‍💻 Kontributor
- [@PaguhEsatrio](https://github.com/PaguhEsatrio)
- [@valentianoaudy](https://github.com/valentianoaudy)

---

## 🙌 Ucapan Terima Kasih
<p align="left">
  <img src="https://media.licdn.com/dms/image/v2/C560BAQGyTlT3cNArqA/company-logo_200_200/company-logo_200_200/0/1630647806765?e=2147483647&v=beta&t=-4MLBy1LU9-CfBHUY8t96E-bfh044bgUk7Abj-HS8KM" width="100" alt="Logo Mitra">
</p>

Terima kasih kepada seluruh pihak yang telah mendukung kelancaran proyek kerja praktek ini.
