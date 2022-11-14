## Rangkuman Minggu Ke 3 Back-End
## Day -10
### Sequelize
### 1. Pengertian Sequelize
Sequelize adalah ORM (Object Relational Mapping) Node JS yang berbasis promise. Sequelize mendukung sebagian besar relational Database seperti MySQL, PostgresQL, 
MariaDB, SQLite dan Miscrosoft SQL Server. Dengan fitur fitur di Sequelize, kita bisa mengelola dan mengatur data di database kita dengan cepat, dan efisien.

### 2. Instalasi Sequelize
- install sequelize & driver sql

![ins-sequelize](https://user-images.githubusercontent.com/114325558/200263258-7f83cf6d-ffcd-434d-83fb-2edd0b1f4f5d.JPG)

- install sequelize cli

![sequelize-cli](https://user-images.githubusercontent.com/114325558/200261478-e586186d-1a04-4fc4-9dad-a83b9ba4b069.JPG)

### 3. Generate Sequelize
- Sequelize init

![sequelize-init](https://user-images.githubusercontent.com/114325558/200261983-b29b8132-b288-40e0-a54c-820fea6ea15c.JPG)

- Setting database

![setting-db](https://user-images.githubusercontent.com/114325558/200262384-936476cb-dbcf-4ca3-8154-f4ee08f513b5.JPG)

- Generate model

![generate-model](https://user-images.githubusercontent.com/114325558/200262752-67a4e37a-c554-4635-b74f-af917f7e6550.JPG)

- Generate seed

![generate-seed](https://user-images.githubusercontent.com/114325558/200263043-fefcbde7-b11c-430d-97a9-1e203d5c8ab7.JPG)

### 4. Membuat Crud Dengan Sequelize dan Express
- Get all todo

![get-all-todo](https://user-images.githubusercontent.com/114325558/200263548-d2cc7592-0956-43e8-9642-d6879d793a71.JPG)

- Get to do detail by-id

![get-todo-detail-byId](https://user-images.githubusercontent.com/114325558/200263845-cc07dcfd-928e-46e0-8e1c-bd457f8185e8.JPG)

- Create new todo

![create-new-todo](https://user-images.githubusercontent.com/114325558/200264391-ef21215b-13b7-4c9e-a59b-7d4d19d06314.JPG)

- Update todo by id

![update-todo-by-id](https://user-images.githubusercontent.com/114325558/200264587-f9b2e24e-aeea-4f11-a1d0-1f5bee09bb14.JPG)

## Day -11
## MongoDB
## 1. pengenalan MongoDB
MongoDB adalah salah satu jenis database NoSQL yang cukup populer digunakan dalam pengembangan website. NoSQL sendiri adalah singkatan dari Not Only SQL. Artinya kita bisa mengolah database dengan fleksibel dan tidak membutuhkan Query. Berbeda dengan database jenis SQL yang menyimpan data menggunakan relasi tabel, MongoDB menggunakan dokumen dengan format JSON. 

![ilustrasi mongodb](https://user-images.githubusercontent.com/114325558/201625530-017d3a54-1dfb-452b-82ba-f3f6a1284a58.JPG)

Sistem database ini menggunakan beberapa komponen penting, yaitu: 
- Database – merupakan wadah dengan struktur penyimpanan yang disebut collection. 
- Collection – merupakan tempat kumpulan informasi data yang berbentuk dokumen. Collection dipadankan seperti tabel-tabel yang berisi data pada database SQL.  
- Document – merupakan satuan unit terkecil dalam MongoDB.

Keunggulan menggunakan MongoDB  yaitu :
- Performa lebih cepat.
- Sistem tidak membutuhkan tabel.
- Pengelolaan database lebih mudah.
- Mampu menampung banyak data yang bervariasi.
- Bisa mengelola query lebih baik.
- Memiliki kemampuan skalabilitas sesuai kebutuhan.
- Dapat memperbarui skema data tanpa downtime.

Sedangkan kekurangan menggunakan MongoDB yaitu :
- Tidak mendukung transaksi.
- Masalah konsistensi data.
- Menggunakan banyak memory.
- Hanya bisa menampung maksimal 16MB disetiap document.

2. Instalasi MongoDB
- Perintah instalasi 

![instalasi mongodb](https://user-images.githubusercontent.com/114325558/201628813-cb40501f-ddcb-4e2a-a4ea-3aeee721bf58.JPG)

- Mengaktifkan MongoDB

![use mongodb](https://user-images.githubusercontent.com/114325558/201629052-091ac0c3-ae4f-43a1-86d5-3e102ebd191b.JPG)

setelah aktif jalankan perintah berikut :

![start mongodb](https://user-images.githubusercontent.com/114325558/201629319-ddb8b9c5-f28d-4916-91a4-8e9087874cd1.JPG)

- Cek status

![cek status mongodb](https://user-images.githubusercontent.com/114325558/201629586-3e2d36cb-66cf-4fac-8a0b-481c0562ee3b.JPG)

Jika hasil tampilannya seperti berikut, berarti database MongoDB sudah aktif dan berjalan.

![tampilan status mongodb](https://user-images.githubusercontent.com/114325558/201630024-14c2a49f-bc7f-439e-a5ce-3f55a5408750.JPG)

3. Perintah Dasar Pada MongoDB
- Masuk ke database MongoDB

![masuk ke mongodb](https://user-images.githubusercontent.com/114325558/201631332-388e8343-be24-46b1-80fe-6c41789df517.JPG)

- Membuat database

![buat db mongo](https://user-images.githubusercontent.com/114325558/201631780-c7419895-a0c6-4e2a-aa13-d58c49efff8d.JPG)

- Melihat database

![lihat db](https://user-images.githubusercontent.com/114325558/201632065-6ad7cc49-bcd6-405e-9bc4-5e75771984fd.JPG)

- Menghapus database

![drop db](https://user-images.githubusercontent.com/114325558/201632244-789898fa-0967-42a9-8f13-4cb130ad3ee4.JPG)

- Insert data

![insert data](https://user-images.githubusercontent.com/114325558/201632471-98c4db23-fca8-4f86-9ada-ecdbe5b26689.JPG)

- Melihat daftar collection dalam database

![show collection](https://user-images.githubusercontent.com/114325558/201632929-8e565494-da2e-4739-8d08-e16b1c3e155e.JPG)

- Melihat isi collection

![melihat isi collection](https://user-images.githubusercontent.com/114325558/201633207-384de3f0-a2eb-4b6c-abf8-e9ef323a3d65.JPG)

- Melihat isi collection dalam bentuk JSON

![melihat collection json](https://user-images.githubusercontent.com/114325558/201633626-890b8e5c-5531-4f0d-9b75-2112d76b256a.JPG)

- Melihat isi collection hanya 1 result

![lht collection 1 result](https://user-images.githubusercontent.com/114325558/201641760-44eb6a78-77d0-42e5-afc8-ec2e81809541.JPG)

- Menghapus data

![hapus data](https://user-images.githubusercontent.com/114325558/201642010-d1bb3189-720a-4714-a8dc-1ed8dedd4f55.JPG)

- Mengubah data

![update data](https://user-images.githubusercontent.com/114325558/201642179-07a1f148-c39c-43e2-ace9-19eb4c4df0de.JPG)

- Menghapus Collection

![hapus collection](https://user-images.githubusercontent.com/114325558/201642349-c5fdab4d-5302-460a-8f75-f30dfb731c92.JPG)

## Mongoose
## Pengenalan 



