## Waitlist Poply - Referral Booster

Skrip ini otomatis mengirimkan sejumlah email ke API waitlist menggunakan kode referral yang dimasukkan. Ini berguna untuk mempercepat kenaikan peringkat di sistem waitlist berbasis referral.

## 🛠️ Fitur Utama

Email Generator: Menghasilkan alamat Gmail acak secara otomatis.

Referral Code Input: Bisa memasukkan kode referral sendiri atau pakai default.

Progress Bar: Menampilkan kemajuan pengiriman email secara real-time.

Error Logging: Menangani error dan mencatat kegagalan pengiriman email.

Hasil dalam Tabel: Menampilkan hasil pengiriman dalam bentuk tabel rapi.


## 🔁 Alur Kerja Skrip

1. Menampilkan Banner
Saat skrip dijalankan, akan muncul banner yang memperkenalkan program.


2. Memasukkan Kode Referral
Pengguna diminta memasukkan kode referral (atau tekan Enter untuk memakai default).


3. Memasukkan Jumlah Email
Pengguna menentukan berapa banyak email yang ingin dikirim (misal: 5, 10, 20).


4. Menghasilkan Email Acak
Skrip membuat alamat Gmail acak berdasarkan nama dan angka random.


5. Mengirim Email ke API Waitlist

Mengirim data email dan referral ke API menggunakan fetch.

Menunggu respons dari server untuk mengetahui status sukses/gagal.



6. Menampilkan Proses dan Hasil

Progress Bar menunjukkan seberapa banyak email yang telah dikirim.

Tabel Hasil mencatat setiap email dan status pengiriman (Success/Failed).



7. Mengakhiri Program
Setelah semua email dikirim, skrip menutup koneksi dan menampilkan ringkasan.



## 🏁 Instalasi

Pastikan Node.js sudah terinstall di perangkat Anda.

1. Clone atau download repository ini:


```
git clone https://github.com/Yuurichan-N3/Poply-Auto-Reff-.git
cd Poply-Auto-Reff-
```


2. Instal semua dependensi:


```
npm install
```


3. Jalankan skrip:


```
node bot.js
```


## ⚙️ Konfigurasi API

API yang digunakan untuk mengirim email sudah diatur di dalam skrip:


Pastikan waitlist_id sesuai dengan kebutuhan Anda (default: 10321).

## 📘 Dependencies

Semua library yang diperlukan sudah ada dalam package.json:

node-fetch: Mengirim request ke API.

colors: Memberi warna pada teks terminal.

cli-progress: Menampilkan progress bar.

cli-table3: Membuat tabel hasil pengiriman email.

winston: Logging untuk mencatat info/error.

gradient-string: Memberi efek gradasi pada teks.


## 📜 Lisensi  

Script ini didistribusikan untuk keperluan pembelajaran dan pengujian. Penggunaan di luar tanggung jawab pengembang.  

Untuk update terbaru, bergabunglah di grup **Telegram**: [Klik di sini](https://t.me/sentineldiscus).


---

## 💡 Disclaimer
Penggunaan bot ini sepenuhnya tanggung jawab pengguna. Kami tidak bertanggung jawab atas penyalahgunaan skrip ini.
