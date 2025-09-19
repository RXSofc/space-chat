Space Chat - Real-time Group Chat Application

Space Chat adalah aplikasi chat grup real-time dengan tema luar angkasa yang dibangun menggunakan HTML, CSS, JavaScript, dan Firebase Realtime Database.

🌟 Fitur

· Chat Real-time: Kirim dan terima pesan secara instan
· Tema Luar Angkasa: Desain futuristik dengan efek bintang dan animasi
· Auto Login: Penyimpanan username di local storage
· Reply Message: Balas pesan tertentu dengan mudah
· Admin Panel: Hapus semua chat dengan PIN (1903)
· Online Counter: Melihat jumlah pengguna online
· Responsif: Bekerja dengan baik di desktop dan mobile

🚀 Cara Menggunakan

1. Masuk ke Chat:
   · Masukkan username Anda (maksimal 20 karakter)
   · Centang "Ingat saya" untuk auto login di kunjungan berikutnya
   · Klik "Gabung Chat"
2. Mengirim Pesan:
   · Ketik pesan di input box
   · Tekan Enter atau klik tombol "Kirim"
3. Membalas Pesan:
   · Klik pada pesan yang ingin dibalas
   · Section reply akan muncul
   · Ketik balasan dan kirim seperti biasa
4. Menghapus Semua Chat:
   · Klik tombol "Hapus Semua Chat"
   · Masukkan PIN: 1903
   · Semua chat akan terhapus

🛠️ Teknologi

· Frontend: HTML5, CSS3, JavaScript (ES6+)
· Backend: Firebase Realtime Database
· Icons: Font Awesome
· Effects: CSS Animations

📁 Struktur File

```
space-chat/
├── index.html          # File utama aplikasi
├── firebase-config.js  # Konfigurasi Firebase
└── README.md           # Dokumentasi ini
```

🔧 Konfigurasi Firebase

Aplikasi ini menggunakan Firebase Realtime Database. Untuk menggunakan dengan project Firebase Anda sendiri:

1. Buat project baru di Firebase Console
2. Enable Realtime Database
3. Ganti konfigurasi di kode dengan kredensial project Anda

🌐 Deployment

Aplikasi dapat di-deploy di berbagai platform:

· GitHub Pages: Upload file ke repository dan aktifkan GitHub Pages
· Firebase Hosting: Gunakan Firebase CLI untuk deploy
· Netlify: Drag and drop folder ke interface Netlify
· Vercel: Connect repository GitHub untuk auto deploy

📱 Kompatibilitas

· Browser: Chrome, Firefox, Safari, Edge (versi terbaru)
· Device: Desktop, Tablet, Mobile
· Connection: Require internet connection (Firebase dependency)

🎨 Customization

Anda dapat mengkustomisasi aplikasi dengan mudah:

· Warna: Ubah variabel CSS di section style
· PIN Admin: Ganti constant ADMIN_PIN di JavaScript
· Effects: Modifikasi animasi di keyframes CSS

⚠️ Catatan Penting

· Pastikan koneksi internet stabil untuk pengalaman terbaik
· Data chat disimpan di Firebase Realtime Database
· Username disimpan secara lokal di browser pengguna

👨‍💻 Developer
Dikembangkan oleh @riixs4k

Note: Aplikasi ini dibuat untuk tujuan edukasi dan demonstrasi. Pastikan untuk mengikuti kebijakan privasi dan persyaratan layanan saat mengimplementasikan di production environment.
