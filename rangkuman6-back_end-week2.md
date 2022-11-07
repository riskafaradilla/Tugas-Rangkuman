## Rangkuman Minggu Ke-2 Back_End Web Development
## Day-6
### Database & Mysql
### A. Database
### 1. Pengertian Database
Pengertian database adalah sekumpulan data yang dikelola berdasarkan ketentuan tertentu yang saling berkaitan sehingga memudahkan dalam pengelolaannya. Dihimpun 
dari berbagai sumber, secara sederhana, database atau basis data merupakan sekumpulan data atau informasi yang tersimpan secara sistematis. Database memiliki 
peran penting dalam perangkat untuk mengumpulkan informasi, data, atau file secara terintegrasi. Database membuat penyimpanan dan pengelolaan data menjadi lebih 
efisien.

### 2. Database Management System (DBMS)
Database Management System atau DBMS adalah software yang digunakan untuk mengelola, menyimpan, dan mengambil database. Software ini menyediakan antarmuka yang 
memungkinkan user membaca, membuat, menghapus, dan memperbarui data. contoh dari DBMS yaitu : Mysql, PostgreSQL, MongoDB, Oracle, dll.

### 3. Istilah yang Digunakan dalam Database
- Table
 Dalam database, table merupakan kumpulan elemen menggunakan model kolom vertikal dan baris yang horizontal.
 
- Query
Query dapat didefinisikan sebagai kumpulan perintah yang digunakan untuk mengolah data dalam table ataupun database itu sendiri.

- Field
Field merupakan kumpulan karakter yang terdapat dalam suatu atribut yang menunjukkan atau menampilkan suatu item, seperti noMahasiswa, namaMahasiswa, 
tanggal_lahir dan jenisKelamin merupakan contoh dari field.

- Record
Dalam database, record disebut juga dengan tuple merupakan kumpulan elemen-elemen dalam field yang saling berkaitan untuk memberikan informasi mengenai suatu entitas 
dengan lengkap. Entitas itu sendiri berupa orang, tempat, kejadian dan konsep. Contoh pada Tabel mahasiswa memiliki kumpulan data value berupa noMahasiswa, 
namaMahasiswa, tanggal_lahir dan jenisKelamin.

### B. Mysql
### 1. pengertian Mysql
MySQL dibaca MY-ES-KYOO-EL [maɪˌɛsˌkjuːˈɛl]. Beberapa orang juga membaca MySQL sebagai “my sequel”. MySQL adalah sistem manajemen database relasional (RDBMS) 
open-source berbasis SQL yang bekerja dengan model client-server.  Kegunaan atau fungsi MySQL adalah untuk data warehousing (gudang data), yaitu pengumpulan data 
dari berbagai sumber, untuk e-commerce, maupun aplikasi logging.

### 2. Type Data dalam SQL
- Number
Tipe data Number adalah data yang berisi kumpulan karakter angka. 
  - int
  - float
  - decimal
  
- String
Tipe data string adalah tipe data berupa kumpulan karakter termasuk karakter simbol
  - char
  - varchar
  - text
  
- Boolean
Tipe ini hanya menyimpan 2 tipe data yaitu TRUE dan FALSE, dan dapat di convert menjadi int dengan representasi TRUE = 1, dan FALSE = 0

- Date time
Tipe ini hanya menyimpan 2 tipe data yaitu TRUE dan FALSE, dan dapat di convert menjadi int dengan representasi TRUE = 1, dan FALSE = 0

### 3. Key dalam SQL
- Primary key
Primary Key disebut juga dengan Kunci Primer. Kunci Primer tersebut dipilih sebagai identifikasi untuk membedakan satu baris dengan baris lainnya dalam suatu tabel.
Pada dasarnya, setiap tabel hanya memiliki satu primary key saja.

- Foreign key
Secara sederhana, foreign key dapat diartikan sebagai kunci asing. Definisi tersebut juga berlaku dalam pengolahan relasional database. Kunci asing (Foreign Key) 
adalah sebuah atribut atau gabungan atribut yang terdapat dalam suatu tabel yang digunakan untuk menciptakan hubungan (relasi) antara dua tabel. 

### 2. Perintah dalam SQL
- Create database
- Use Database
- Create table
- Insert into
- Select

## Day -7
### Mysql (Lanjutan)

## Day -8
### Authentication & Authorization
### 1. Pengertian Authentication & Authorization
Authentication adalah proses dimana seorang user (melalui berbagai macam akses fisik berupa komputer dll) mendapatkan hak akses kepada suatu entity. Misalnya seperti
Seorang user melakukan login kedalam suatu infrastruktur jaringan dan sistem mengenali user ID dan menerimanya untuk kemudian diberikan akses, sesuai dengan 
authorisasi yang dia terima (masuk pada tahap authorization). Sedangkan authorization adalah proses penentuan apakah user tersebut diizinkan / ditolak untuk
melakukan satu atau beberapa action akses terhadap resources tertentu dalam sistem. Misalnya seperti setelah user login terhadap sistem dengan menggunakan user-ID dan 
password, kemudian sistem mengenalinya dan user mendapatkan akses atau ditolak terhadap suatu resource sistem tertentu.

### 2. JSON Web Token
JSON Web Token, yang berarti token ini menggunakan JSON (Javascript Object Notation) berbentuk string panjang yang sangat random, lalu token ini memungkinkan kita 
untuk mengirimkan data yang dapat diverifikasi oleh dua pihak atau lebih. Cara kerjanya yaitu seperti password jadi ketika users berhasil melakukan Login maka server 
akan memberikan sebuah Token. Nanti Token tersebut akan disimpan oleh users pada Local Storage atau Cookies Browser dan bila users ingin mengakses halaman halaman 
tertentu maka harus menyertakan token tersebut. Untuk itu users akan mengirim balik token yang dikasih diawal tadi sebagai bukti bila user ini, sudah melakukan login.
Token ini terdiri dari Header, Content, dan Signature.

### 3. Penerapan Pada Project Express

## Day -9
### Sequelize
### 1. Pengertian Sequelize
Sequelize adalah ORM (Object Relational Mapping) Node JS yang berbasis promise. Sequelize mendukung sebagian besar relational Database seperti MySQL, PostgresQL, 
MariaDB, SQLite dan Miscrosoft SQL Server. Dengan fitur fitur di Sequelize, kita bisa mengelola dan mengatur data di database kita dengan cepat, dan efisien.

### 2. Instalasi Sequelize
### 3. Generate Sequelize
### Membuat CRUD Dengan Sequelize dan Express










  


