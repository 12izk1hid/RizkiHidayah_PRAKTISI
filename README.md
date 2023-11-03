Aplikasi mobile saya terdiri dari 3 halaman :
1. Halaman Home :
2. Halaman Profile
3. Halaman Setting

A. Halaman Home
1. Kode tersebut menggunakan Jetpack Compose untuk membuat antarmuka pengguna (UI) dalam bentuk komposisi (Composable)
2. Terdapat penggunaan mutableStateOf dan remember untuk mengelola state aplikasi.
   Variabel angka digunakan untuk menyimpan nilai yang bisa berubah.
3. Kode ini menggunakan komponen layout seperti Box dan Column untuk mengatur tampilan UI
4. Terdapat tombol "Increment" yang mana apabila tombol tersebut d tekan oleh pengguna maka
   nilai variabel angka akan meningkat.
 ![home](https://github.com/12izk1hid/RizkiHidayah_PRAKTISI/assets/146097556/5c5e1836-23ab-488b-82e2-1e542d353675)



B. Halaman Profile
1.	Kode memiliki fungsi Profile, yang merupakan komponen Compose UI yang menampilkan tampilan utama (profil) dengan latar belakang warna putih.
2.	Melalui fungsi getJSONData, kode memanfaatkan Retrofit untuk mengambil data dari server eksternal. 
3.	Kode ini menggunakan Retrofit untuk membangun koneksi ke server dengan menentukan URL basis dan endpoint API. 
4.	Kode ini memiliki fungsi callback yang menangani respons dari server. Jika respons berhasil, data JSON diuraikan dan dimasukkan ke dalam daftar courseList. Jika terjadi kegagalan, kesalahan ditampilkan melalui Toast dan dicatat di Log.
5.	Fungsi displayListView menggunakan LazyColumn untuk menampilkan data dalam daftar. Setiap elemen dalam daftar adalah Text yang mewakili bahasa, dan ada garis pemisah Divider di antara setiap elemen. 
![profile](https://github.com/12izk1hid/RizkiHidayah_PRAKTISI/assets/146097556/92bd5bf4-dc88-4974-8a3e-11748896e56b)


C. Halaman Setting
1. Fungsi Setting menerima parameter number dengan tipe data String. Ini memungkinkan untuk mengirim data atau informasi ke komponen Setting saat menggunakannya.
2. teks yang menggambarkan "This is settings screens, the number is $number". Variabel number yang diterima sebagai parameter digunakan untuk mengisi nilai yang akan ditampilkan pada layar. Ini
3. memungkinkan tampilan informasi yang dinamis tergantung pada nilai number.
4. Warna Latar Belakang: Anda menggunakan background Color.White untuk mengatur latar belakang layar menjadi warna putih.
![setting](https://github.com/12izk1hid/RizkiHidayah_PRAKTISI/assets/146097556/b5d0c20f-0be4-48b4-938d-8a4d518cf2fb)


   

