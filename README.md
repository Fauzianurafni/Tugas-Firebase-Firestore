# Alur Pengerjaan Project Firebase Firestore

Nama  : Fauzia Nurafni
NIM   : 2230511059

Link Demo Project : https://drive.google.com/file/d/1ffWrJGOJGQdaDWVjk2smnAcdPpEtquBs/view?usp=drive_link

Berikut adalah langkah-langkah dalam mengerjakan project Firebase Firestore menggunakan Flutter:
1.	Buat project di Firebase Console. Masuk ke Firebase Console, buat project baru, dan tambahkan aplikasi Flutter ke dalamnya.
2.	Tambahkan dependensi Firebase di file pubspec.yaml dengan menambahkan firebase_core dan cloud_firestore, lalu klik pub get yang ada di kanan atas untuk menginstall dependensi.
3.	Inisialisasikan Firebase di main.dart dengan Firebase.initializeApp().
4.	Buat folder model/ di dalam directory lib dan buat file user_model.dart yang merepresentasikan data pengguna yang akan disimpan di Firestore.
5.	Buat folder repositories/ di dalam directory lib dan buat file firestore_repository.dart untuk berkomunikasi dengan Firestore. Repository ini akan digunakan untuk mengambil, menambahkan, memperbarui, dan menghapus data pengguna.
6.	Membuat tampilan home screen. Buat folder screens/ didalam directory lib
7.	Kemudian buat file home_screen.dart untuk menampilkan daftar pengguna menggunakan StreamBuilder.
8.	Membuat form tambah pengguna. Buat file add_user_screen.dart di dalam folder screens/ untuk menambahkan pengguna baru.
9.	Membuat form edit pengguna. Buat file edit_user_screen.dart di dalam folder screens/ agar pengguna dapat memperbarui data yang sudah ada.
10.	Membuat halaman detail pengguna. Buat file detail_user_screen.dart di dalam folder screens/ untuk menampilkan detail informasi pengguna ketika daftar pengguna diklik.
11.	Setelah semua langkah sudah dilakukan, jalankan aplikasi.

