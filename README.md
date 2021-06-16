# lab11_php_ci

### Praktikum 11 : Belajar CI

##### Nama : Windy Septiani
##### NIM : 311910673
##### Kelas : 19.TI.F.1

### Jawaban Tugas Praktikum 11
##### Menambahkan source code di file footer.php
![Gambar 1](Screenshot/ss24.png)
![Gambar 2](Screenshot/ss25.png)
![Gambar 3](Screenshot/ss26.png)

##### Tampilan di web browser
![Gambar 4](Screenshot/ss27.png)
![Gambar 5](Screenshot/ss28.png)
![Gambar 6](Screenshot/ss29.png)

### Tugas Praktikum 11
##### Buka PHP(php.ini) di 'config' dari 'Apache'
![Gambar 7](Screenshot/ss1.png)

##### Lalu hapus tanda ';' yang di depan kata 'extension'
![Gambar 8](Screenshot/ss2.png)
![Gambar 9](Screenshot/ss3.png)

##### Download 'codeigniter 4' di website https://codeigniter.com/download
![Gambar 10](Screenshot/ss4.png)

##### Lalu extrak file zip Codeigniter, ubah nama a direktory framework-4.x.xx menjadi ci4
![Gambar 11](Screenshot/ss5.png)

##### Klik 'Start' pada 'Apache' dan 'MySQL' di 'Xampp', lalu buka browser dengan alamat http://localhost/lab11_ci/ci4/public/
![Gambar 12](Screenshot/ss6.png)

##### Untuk mengakses CLI, buka command prompt dan ketik 'php spark' setelah mengarahkan lokasi direktori sesuai dengan direktori kerja project dibuat. Ketik 'php spark serve' jika menemukan eror
![Gambar 13](Screenshot/ss7.png)
![Gambar 14](Screenshot/ss8.png)
![Gambar 15](Screenshot/ss9.png)

##### Source code untuk mengarahkan rute ke halaman home, dengan cara ditambahkan di dalam 'routes.php'
![Gambar 16](Screenshot/ss10.png)

##### Untuk mengetahui route yang ditambahkan sudah benar, buka CLI dan jalankan perintah 'php spark routes' di 'command prompt'
![Gambar 17](Screenshot/ss11.png)

##### Lalu buka browser dengan alamat url 'http://localhost:8080/about'. Bila tampilannya seperti ini, maka harus membuat 'Contoller' yang sesuai dengan rounting yang dibuat ; 'Contoller Page'
![Gambar 18](Screenshot/ss12.png)

##### Source code untuk membuat 'Controller Page' dengan file baru bernama 'page.php' pada direktori 'Controller'
![Gambar 19](Screenshot/ss13.png)
##### Tampilan di web browser akan jadi seperti ini
![Gambar 20](Screenshot/ss14.png)

##### Source code untuk menambahkan method baru pada Controller Page
![Gambar 21](Screenshot/ss15.png)
##### Tampilan di web browser akan jadi seperti ini
![Gambar 22](Screenshot/ss16.png)

##### Source code untuk file 'about.php' yang dibuat pada direktori view (app/view/about.php)
![Gambar 23](Screenshot/ss17.png)
##### Source code untuk mengubah method 'about' pada class 'Controller Page'
![Gambar 24](Screenshot/ss18.png) 
##### Tampilan di web browser akan jadi seperti ini
![Gambar 25](Screenshot/ss19.png)

##### Source code untuk file header.php yang dibuat dalam folder template pada direktori view (app/view/template/header.php)
![Gambar 26](Screenshot/ss20.png)
##### Source code untuk file footer.php yang dibuat dalam folder template pada direktori view (app/view/template/footer.php)
![Gambar 27](Screenshot/ss21.png)
##### Source code untuk perubahan file about.php pada direktori view (app/view/about.php)
![Gambar 28](Screenshot/ss22.png)
##### Tampilan di web browser akan jadi seperti ini
![Gambar 29](Screenshot/ss23.png)