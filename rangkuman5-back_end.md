## Rangkuman Minggu Ke -1 Back-End
## Day-1 Web Server & RESTful API
### A. Web Server
### 1. Pengertian Web Server
Web server adalah sebuah perangkat lunak yang berfungsi untuk memberikan layanan berupa data, dan berfungsi menerima permintaan HTTP atau HTTPS dari klien yang menggunakan browser (chrome, firefox, dll).
Web server terbagi menjadi hardware dan software.
Dari pengertian hardware, web server adalah sebuah perangkat yang menyimpan komponen website seperti dokumen HTML, gambar, CSS stylesheets, dan JavaScript.
Sedangkan dari pengertian software, web server termasuk dalam beberapa bagian yang mengontrol setiap permintaan yang diajukan oleh klien menggunakan browser.

### 2. Fungsi Web Server
Fungsi utama web server adalah menerima permintaan HTTP atau HTTPS dari klien atau web browser.
Kemudian web server akan meresponnya dengan menampilkan halaman web HTML, foto, video, dokumen, atau yang lainnya.
Selain itu web server juga memiliki fungsi lain yaitu :
- Memeriksa sistem security yang berasal dari permintaan HTTP yang diminta oleh klien atau web browser.
- Membersihkan semua cache yang ada pada penyimpanana dan dokumen yang sudah tidak dipakai lagi.
- Menyediakan data sesuai permintaan yang masuk untuk menjamin kelancaran keamanan sistem yang berjalan.

### Cara Kerja Web Server

![cara-kerja-web-server](https://user-images.githubusercontent.com/114325558/199008632-791ea946-6a9c-4381-8776-bf3cff30a374.JPG)

Pada saat klien atau browser seperti Safari meminta data kepada web server, permintaan tersebut akan dikemas pada TCP dan dikirimkan ke alamat yang dibutuhkan baik itu HTTP atau HTTPS agar ditampilkan di browser.
Namun, jika data yang diminta tidak bisa ditemukan, maka web server akan secara otomatis menolak permintaan tersebut. Itulah kenapa kita sering menemukan Page Not Found atau Error 404 saat mengakses informasi atau website melalui internet.

### B. RESTful API
### 1. Pengertian RESTful API
Application Programming Interface atau API adalah serangkaian standar dan protokol yang mengintegrasikan user dengan aplikasi sehingga pengguna bisa mengakses dan menggunakan fungsi software aplikasi tersebut. 
Fungsinya yaitu sebagai mediator atau komunikator antara pengguna dan sistem. Oleh karena itu, API sangat penting untuk mempermudah akses dan pengembangan aplikasi di internet. 
REST adalah singkatan dari Representational State Transfer dan merupakan salah satu tipe arsitektur software. REST mewakili serangkaian batasan yang harus diikuti saat Anda mengembangkan aplikasi di internet.
Suatu API akan disebut sebagai RESTful API apabila mampu memenuhi ketentuan dan batasan yang ditetapkan oleh gaya arsitektur REST ini. Kriteria tersebut ditujukan untuk menstandarkan proses komunikasi antar berbagai platform dan menjadikannya lebih fleksibel.

### 2. Cara Kerja RESTful API
RESTful API bekerja dengan cara memanipulasi resource dan representasi. Representasi ini saling dipertukarkan di antara pengguna dan server melalui antarmuka terstandar dan protokol komunikasi tertentu, biasanya HTTP. 
Jadi, saat pengguna ingin menggunakan fungsi suatu aplikasi, perangkatnya akan mengirimkan permintaan melalui HTTP ke server. Server akan mencari resource dan mengomunikasikan representasi state sebagai respons kepada pengguna melalui protokol yang sama. Representasi ini bisa dibuat dalam berbagai format, seperti JSON atau XML.

### 3. Metode Pada Rest API
- GET berfungsi untuk membaca data/resource dari REST server
- POST berfungsi untuk membuat sebuah data/resource baru di REST server
- PUT berfungsi untuk memperbaharui data/resource di REST server
- DELETE berfungsi untuk menghapus data/resource dari REST server

&nbsp;

## Day-2
### Intro & Essential Node JS
### 1. Pengenalan Node Js
Node.js adalah runtime environment untuk JavaScript yang bersifat open-source dan cross-platform. Dengan Node.js kita dapat menjalankan kode JavaScript di mana pun, tidak hanya terbatas pada lingkungan browser. Dengan adanya Node.js, JavaScript menjadi bahasa multiplatform yang banyak menggiring developer untuk menggunakannya. JavaScript menjadi salah satu pilihan tepat dalam membangun web server bukan hanya dari sisi Front-End tetapi juga dari sisi Back-End. Node.js juga menyediakan banyak library/module JavaScript yang membantu menyederhanakan pengembangan aplikasi web.

### 2. Instalasi Node Js pada Windows
- Node js dapat diunduh pada link : https://nodejs.org/.
- Buka official page Node.js untuk mendownload installer untuk Windows, lalu pilih opsi “Windows Installer”.
- Download Node js sesuai bit laptop/komputer yang dimiliki.
- Langkah selanjutnya jalankan file installer yang telah didownload, dan klik next hingga Node Js selesai terinstall.
- Untuk mengecek apakah Node Js telah terinstall dapat menggunakan command node -v pada git bash.

### 3. Package pada Node Js
- Console merupakan module bawaan dari javascript yang ada di node JS untuk digunakan sebagai debug atau menampilkan code secara interface.
- Process adalah modules yang digunakan untuk menampilkan dan mengontrol prosess Node JS yang sedang dijalankan.
- OS module merupakan module yang digunakan untuk menyediakan informasi terkait sistem operasi komputer yang digunakan user.
- Util merupakan alat bantu / utilities untuk mendukung kebutuhan internal API di Node JS.
- Errors merupakan modules yang dapat digunakan untuk mendefinisikan error di Node JS sehingga lebih informatif.
- Buffer merupakan modules yang digunakan untuk mengakses, mengelola dan mengubah tipe data raw atau tipe data bytes.
- Fs atau “file system” merupakan module yang dapat membantu berinteraksi dengan file yang ada diluar code. 
- Timers merupakan modules yang digunakan untuk melakukan scheduling atau mengatur waktu pemanggilan fungsi yang dapat diatur di waktu tertentu.

### 4. Membuat Web Server Dengan Node Js
- Node Js Web Server

![menambahkan-http-header](https://user-images.githubusercontent.com/114325558/199010227-975e8bb4-f529-45fc-bb85-d993aae2c4fd.JPG)

  - Untuk menggunakan modul HTTP, gunakan require().
  - Gunakan method createServer() untuk membuat server HTTP.
  - Callback function yang digunakan pada method http.createServer(), akan dijalankan ketika seseorang mencoba mengakses komputer pada port 8080.

- Membaca Query String

![membaca query string](https://user-images.githubusercontent.com/114325558/199010404-b201c510-7a36-43b7-a4a7-af970b8cfa82.JPG)

  - Callback function pada method http.createServer() memiliki argumen req yang mewakili request dari klien, sebagai objek (objek http.IncomingMessage).
  - Objek ini memiliki sebuah properti yang disebut "url" yang menyimpan informasi url yang sedang mengakses.

&nbsp;

## Day-3
### Express Js
### 1. Pengenalan Express Js
Express.js adalah framework web app untuk Node.js yang ditulis dengan bahasa pemrograman JavaScript. Framework open source ini dibuat oleh TJ Holowaychuk pada tahun 2010. Express.js adalah framework back end. Artinya, ia bertanggung jawab untuk mengatur fungsionalitas website, seperti pengelolaan routing dan session, permintaan HTTP, penanganan error, serta pertukaran data di server.  Express Js memiliki arsitektur MVC (Model View Controller). Dengan begitu, setiap data diolah pada Model, dihubungkan melalui Controller, lalu ditampilkan menjadi informasi melalui View. Express.js di JavaScript adalah framework yang menggunakan pendekatan Unopinionated dalam proses pengembangan. Artinya, pengguna punya kebebasan dalam menentukan metode yang akan digunakan untuk mengeksekusi suatu perintah.

### 2. Apa itu Back End Web Application ?
Back end app adalah aplikasi yang berjalan di server-side yang bekerja untuk memberikan informasi berupa data sesuai request dari client / browser / front end app. Umumnya server-side app membuat REST API. Kelebihan dari framework ini terletak pada fitur caching, support dengan Google V8 Engine, JavaScript, serta didukung oleh komunitas dan skalabilitas aplikasi yang baik.

### 3. Routing

![routing](https://user-images.githubusercontent.com/114325558/199008794-356c2683-df8c-4583-bac6-d6f8fdd1d92e.JPG)

Routing adalah metode yang digunakan website (server) untuk merespons permintaan dari browser (client). Misalnya, permintaan untuk menampilkan halaman tertentu. 
Cara kerja routing di Express.js adalah dengan sebuah metode bernama app. Metode tersebut akan merespons setiap permintaan berbentuk HTTP. Misalnya GET, POST, PUT, dan DELETE.

### 4. Middleware

![middleware](https://user-images.githubusercontent.com/114325558/199008860-8ab894b4-5c02-479a-8a16-44943b42c82a.JPG)

Middleware adalah fungsi yang digunakan untuk mengakses permintaan object (req), respons object (res), dan setiap siklus permintaan dan respon tersebut (next).
Pada Express.js, cara kerja Middleware adalah dengan mengeksekusi setiap skrip, membuat perubahan terhadap permintaan dan respons object, mengakhiri siklus permintaan-respons, lalu menyiapkan Middleware untuk siklus berikutnya.
Berikut adalah skrip Middleware sederhana pada website Hello World:

&nbsp;

## Day-4
### Design Database With MySQL : "Entity & attributes"
### 1. Entity 
Entitas adalah obyek yang mewakili sesuatu dalam dunia nyata dan dapat dibedakan antara satu dengan lainnya (unique).Setiap entitas memiliki beberapa atribut yang mendeskripsikan karakteristik dari objek. Entitas dapat berupa:
- Data Fisik (seperti mobil, rumah, manusia, pegawai, peserta diklat.
- Abstrak atau konsep (seperti department, pekerjaan, mata pelajaran)
- Kejadian (pembelian, penjualan, peminjaman, dll)
Entitas dapat dibedakan menjadi dua macam yaitu Entitas kuat dan entitas lemah. Entitas lemah adalah yang keberadaannya tergantung pada entitas lain. Gambar dibawah ini menjelaskan notasi umum entitas kuat dengan nama entitas pegawai dan entitas lemah dengan nama entitas tanggungan. 

### 2. Atribute
Attribute merupakan karakteristik dari entitas atau relationship, yang menyediakan penjelasan detail tentang entitas atau relationship. Dalam penerapannya (level fisik) atribut merupakan field atau kolom dari sebuah tabel. Misalnya entitas mahasiswa memiliki atribute nama, alamat, NIM. Berdasarkan karakteristik atau sifatnya, atribut dapat dikelompokkan menjadi;
- #### Simple attribute dan composite attribute. 
Simple Attribute atau atomic attribute adalah attribut terkecil yang tidak dapat dibagi-bagi lagi menjadi atribut yang lebih kecil. Contohnya adalah atribut JenisKel pada entitas pegawai.
Sedangkan, composite attribute adalah atribut yang dapat dibagi menjadi atribut yang lebih kecil. Attribut ini dapat diartikan attribute atomic yang menggambarkan atribut dasar dengan suatu arti tertentu.
Contoh: atribut Nama pada entitas pegawai dapat dipecah menjadi atribut NmDepan, Inisial dan NmBlk.

- #### Single valued attribute dan multi valued attribute
Single value Attribute adalah suatu atribut yang hanya mempunyai satu nilai. Misalnya atribut NmDepan pada entitas pegawai. NmDepan seorang pegawai selalu bernilai satu nilai, tidak mungkin lebih dari satu.
Sedangkan, multi Value attribute adalah atribut yang dapat memiliki lebih dari satu nilai yang jenisnya sama dari sebuah data tunggal. Misalnya atribut lokasi pada entitas departemen dapat berisi 2 nilai atau lebih seperti Surabaya atau Jakarta. Gambar diatas menjelaskan simbol atau notasi Multi Value attribute. 

- ### Mandatory attribute
Mandatory Attribute adalah merupakan sejumlah atribut yang ada pada suatu table yang harus berisi data dan tidak boleh kosong.

- ### Derived attribute (attribut turunan) dan key attribute.
Derived Attribute atau Atribut Turunan adalah atribut yang nilai- nilainya diperoleh dari pengolahan atau dapat diturunkan dari atribut atau tabel lain yang berhubungan. Misalnya atribut JmlPegawai pada entitas Departemen.
Sedangkan, key attribute adalah satu atau beberapa atribut yang mempunyai nilai unik sehingga dapat digunakan
untuk membedakan data pada suatu baris/record dengan baris lain pada suatu entitas. Key attribute dibedakan menjadi tiga yaitu:
- Superkey 
- Candidat Key
- Primary key

&nbsp;

## Day-5
### Design Database With MySQL : "Relasi & Query"
### 1. Relasi pada Database
Ada beberapa jenis relasi database yaitu :
- Relasi One to One
One to one adalah sebuah relasi dimana satu baris data dari sebuah tabel (Tabel A) hanya terhubung dengan satu baris data di tabel lain (Tabel B).
One to one menjadi salah satu dari bentuk kemungkinan yang bisa terjadi dalam hubungan antar tabel di database. one to one sebetulnya salah satu hubungan antar tabel yang jarang digunakan. Hal ini dikarenakan ada kecendrungan entitas tabel B dapat disatukan dengan menjadikannya sebagai atribut tabel A.
Notasi one to one sebagai berikut :

![notasi one to one](https://user-images.githubusercontent.com/114325558/199009119-3fdcc09e-97d9-43c8-8909-676eae901ec0.JPG)

Contoh relasi one to one sebagai berikut :

![contoh2 one to one](https://user-images.githubusercontent.com/114325558/199009180-f7365f2d-e547-4b3f-89c4-e60b76953644.JPG)

- Relasi One to Many

![one to many](https://user-images.githubusercontent.com/114325558/199009252-60e956e9-e162-4d23-bd4e-42e7a886082a.JPG)

Relasi One to Many adalah relasi dimana suatu baris di table A memiliki relasi di beberapa baris di table B.

- Relasi Many to Many

![many to many](https://user-images.githubusercontent.com/114325558/199009349-48b1d94e-94fd-4abe-9abc-43582dce5d95.JPG)

Relasi Many to Many adalah relasi dimana setiap lebih dari satu baris data dari tabel A berhubungan dengan lebih dari satu baris data pada tabel B. Artinya, kedua tabel masing-masing dapat mengakses banyak data dari tabel yang direlasikan. Maka dari itu, relasi Many to Many butuh tabel C sebagai perantara tabel A dan tabel B

### 2. Query Database
Query adalah syntax atau perintah yang memiliki fungsi untuk mengakses dan menampilkan data pada sistem database. Berikut 4 contoh query pada database :
- create database : digunakan untuk membuat database baru.

![create database](https://user-images.githubusercontent.com/114325558/199009412-4d6e32ef-cd1e-4225-b50e-95d6d3ff016a.JPG)

- create table : digunakan untuk membuat tabel data baru dalam sebuah database.

![create table](https://user-images.githubusercontent.com/114325558/199009449-1079e116-777d-4fe5-8f06-f3d150c39f23.JPG)

- select : digunakan untuk memilih data dari table database.

![select](https://user-images.githubusercontent.com/114325558/199009482-67c3cbaa-2708-48a1-aca1-e3065f2b752c.JPG)

- Where : digunakan untuk memfilter data pada perintah Select.

![where](https://user-images.githubusercontent.com/114325558/199009534-9321dc7c-3452-4ba0-89fd-f9d5f60fdfb0.JPG)

