# Install nodejs
Pastikan nodejs sudah terinstall di pc/laptop, jika belum maka bisa unduh [nodejs](https://nodejs.org/en/download/)

# Install express generator
Buat direktori baru, kemudian buka cmd lalu arahkan path ke direktori yang telah dibuat, jalankan command berikut
```
npm install express-generator -g
```
* **-g** membuat express generator sebagai global package 

![express-generator](https://user-images.githubusercontent.com/32213421/94996229-7be56d80-05cd-11eb-825b-6b79e341ceb5.PNG)

# Inisialisasi project express
Buat project express dengan command **express nama-project** , maka akan dibuat direktori baru sesuai dengan nama project yang akan digunakan sebagai **working directory**
```
express myApp
```

![myApp](https://user-images.githubusercontent.com/32213421/94996232-7f78f480-05cd-11eb-930c-994249c8a307.PNG)

![myApp](https://user-images.githubusercontent.com/32213421/94996237-84d63f00-05cd-11eb-8212-1050c11c321a.PNG)

# Install dependencies
Pindah ke **working directory**, lalu jalankan command **npm install** untuk menginstal semua dependency yang diperlukan pada project
```
cd myApp
npm install
```

![myApp](https://user-images.githubusercontent.com/32213421/94996234-83a51200-05cd-11eb-90b4-20fff14f4419.PNG)

# Run app
untuk menjalankan aplikasi ketikan command **npm start**
```
npm start
```

![runApp](https://user-images.githubusercontent.com/32213421/94996235-843da880-05cd-11eb-8d44-e6ce97590fa8.PNG)


# Test akses web browser
aplikasi berjalan di port 3000 maka untuk melihat hasilnya buka web browser lalu akses URL http://localhost:3000/ , maka akan ditampilkan halaman express project

![testApp](https://user-images.githubusercontent.com/32213421/94996236-843da880-05cd-11eb-9892-b2b5c4d38964.PNG)
