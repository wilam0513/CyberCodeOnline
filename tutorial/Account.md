# Memulai CyberCode Online

CyberCode Online ditata seperti editor kode populer [Visual Studio Code](https://code.visualstudio.com/). Di sisi kiri Anda akan menemukan beberapa ikon. Yang teratas adalah yang paling penting, karena itu adalah Explorer tempat Anda mengakses file kode sebenarnya untuk gim tersebut. Gim ini dimainkan seolah-olah Anda adalah seorang pengembang yang mengedit proyek di editor kode Anda!

<br />

Di File Explorer, kolom sebelah kiri adalah tempat Anda akan menemukan berbagai "file" yang akan terbuka di sisi kanan yang memungkinkan Anda mengakses berbagai bagian karakter dan permainan Anda. File default adalah `Surrounding.ts` yang menggambarkan lingkungan Anda, di mana pun Anda berada secara geografis dalam permainan. Ini akan memiliki lokasi Anda dan status pemain saat ini yang didefinisikan sebagai variabel. Di bawahnya, ini akan memberi tahu Anda jika ada **Tindakan** yang dapat Anda lakukan, jika ada **Musuh** atau **Sekutu** di sekitar, dan di mana Anda dapat **Perjalanan**.

<br />

Pastikan untuk memeriksa halaman tutorial lainnya untuk info yang membahas fitur dari berbagai file seperti `surroundingTutorial.ts` yang membahas area Shangri La dan cara melakukan perjalanan di antara mereka.
<br />

## Pembuatan & Masuk Akun

Anda dapat login dengan akun Google Anda dengan mengklik `signInWithGoogle()` lalu masukkan email dan kata sandi Anda. Setelah login, ketik `displayName` di antara tanda kutip `""` dan klik `save()`.

![Login with Google](../resources/desktop-tutorial/google_create.gif)

<br />

Atau buat akun menggunakan alamat email Anda dengan mengetiknya di antara tanda kutip `""` di bagian `const email="";` di area `signUp()` serta kata sandi di kedua `const password=""; ` dan `const passwordConfirm="";` lalu klik `signUp()` sendiri untuk menyelesaikan pembuatan akun. Setelah akun dibuat, ketik `displayName` dan klik `save()`.

![Sign up](../resources/desktop-tutorial/email_create.gif)
