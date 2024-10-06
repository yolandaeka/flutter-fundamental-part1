#                   LAPORAN PRAKTIKUM
#           JOBSHEET-5 : APLIKASI PERTAMA DAN WIDGET DASAR FLUTTER
                        TUGAS PEMROGRAMAN MOBILE
            Dibimbing oleh: Bapak Ade Ismail, S.Kom., M.TI.
<img src="assets/POLINEMA-LOGO.png">

                        Disusun oleh: 

                    Nama: Yolanda Ekaputri Setyawan
                    NIM : 22241760028
                    KELAS : SIB - 3d
                    JURUSAN TEKNOLOGI INFORMASI
                    PRODI D-IV SISTEM INFORMASI BISNIS
                    POLITEKNIK NEGERI MALANG
                                2024

# Praktikum
## Praktikum 1: Membuat Project Flutter Baru
1.	Buka VS Code, lalu tekan tombol Ctrl + Shift + P maka akan tampil Command Palette, lalu ketik Flutter. Pilih New Application Project.
<img src="assets/new project.png">
2.	Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.
<img src="assets/direktori.png">
3.	Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.
4.	Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" artinya Anda telah berhasil membuat project Flutter baru.
<img src="assets/project ready.png">


## Praktikum 2: Menghubungkan Perangkat Android atau Emulator
1. Melanjutkan dari praktikum 1, Anda diminta untuk menjalankan aplikasi ke perangkat fisik (device Android atau iOS).
<img style="width: 200px" src="assets/emulator.jpeg">


## Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum
1. Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"
<img style="height: 500px" src="assets/repo1.png">

2. Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut.
<img style="height: 500px" src="assets/repo2.png">

3. Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda       
<img src="assets/repo3.png">

4. Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.                                   
<img src="assets/repo4.png">

5. Beri pesan commit "tambah gitignore" lalu klik Commit (✔)                           
<img src="assets/repo5.png">

6. Lakukan push dengan klik bagian menu titik tiga > Push                             
<img src="assets/repo6.png">

7. Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"
<img src="assets/repo7.png">
<br>

8. Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote        
Setelah berhasil, tulis remote name dengan "origin"
<img src="assets/repo7.png">

9. Lakukan hal yang sama pada file README.md mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.
10. Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.
<img style="height: 500px" src="assets/repo8.png">
11. Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.
<img style="height: 500px" src="assets/repo9.png">
12. Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.

## Praktikum 4: Menerapkan Widget Dasar
1. Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. Ketik atau salin kode program berikut ke project hello_world Anda pada file text_widget.dart. 
Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.                                                                                           
<img style="height: 500px" src="assets/text_widget.png">

2. Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.
Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.
<img style="height: 500px" src="assets/img10.png">

## Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino
1. Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
2. Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton. 
Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.
3. Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design. Ubah isi kode main.dart seperti berikut.
4. Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog. Ubah isi kode main.dart seperti berikut.
<img src="assets/img11.png">

5. Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField. Contoh penggunaan TextField widget adalah sebagai berikut:
<img src="assets/img12.png">
6. Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.
<img src="assets/img13.png">