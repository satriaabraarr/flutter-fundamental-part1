# LAPORAN PRAKTIKUM MODUL 5

Nama : Satria Abrar S.W.P <br>
Kelas : 3B/25

## Praktikum 1

### Langkah 1
Buka VS Code, lalu tekan tombol Ctrl + Shift + P maka akan tampil Command Palette, lalu ketik Flutter. Pilih New Application Project.<br>
![alt text](image.png)

### Langkah 2
Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.<br>
![alt text](image-1.png)

### Langkah 3
Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.<br>
![alt text](image-2.png)

### Langkah 4
Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" artinya Anda telah berhasil membuat project Flutter baru.
![alt text](image-3.png)

## Praktikum 2

Melanjutkan dari praktikum 1, Anda diminta untuk menjalankan aplikasi ke perangkat fisik (device Android atau iOS). Silakan ikuti langkah-langkah pada codelab tautan berikut ini.

## Praktikum 3

### Langkah 1
Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"<br>
![alt text](image-4.png)

### Langkah 2
Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut.<br>
![alt text](image-5.png)

### Langkah 3
Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.

### Langkah 4
Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.<br>
![alt text](image-6.png)

### Langkah 5
Beri pesan commit "tambah gitignore" lalu klik Commit (✔)<br>
![alt text](image-7.png)

### Langkah 6
Lakukan push dengan klik bagian menu titik tiga > Push<br>
![alt text](image-8.png)

### Langkah 7
Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"<br>
![alt text](image-9.png)

### Langkah 8
Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote<br>
![alt text](image-10.png)

Setelah berhasil, tulis remote name dengan "origin"<br>
![alt text](image-11.png)

### Langkah 9
Lakukan hal yang sama pada file README.md mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.<br>
![alt text](image-12.png)

### Langkah 10
Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.<br>
![alt text](image-13.png)

### Langkah 11
Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.<br>
![alt text](image-14.png)

### Langkah 12
Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.<br>
![alt text](image-15.png)
![screenshoot hello world!](images/01.png)

## Praktikum 4

### Langkah 1: Text Widget
Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. Ketik atau salin kode program berikut ke project hello_world Anda pada file text_widget.dart.<br>
![alt text](image-16.png)
Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.<br>
![alt text](image-17.png)

### Langkah 2: Image Widget
Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.<br>
![alt text](image-18.png)
Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.<br>
Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.<br>
![alt text](image-19.png)