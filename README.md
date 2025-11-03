# P5-CRUD-REST
## Membangun RESTful CRUD API dengan Express.js  

##  Tujuan Praktikum
1. Mampu membangun RESTful API sederhana menggunakan Express.js.  
2. Menerapkan operasi dasar **CRUD (Create, Read, Update, Delete)**.  
3. Menggunakan **HTTP Method** dan **Status Code** secara benar.  
4. Mengetahui struktur dasar server API modular dengan Node.js.  

---

## Lingkungan & Tools
- Node.js 18+ & npm  
- Express.js  
- VS Code  
- Nodemon *(dev dependency)*  
- Postman / Thunder Client  
- Git & GitHub *(opsional)*  

---

##  Arsitektur Singkat
```text
Client (Postman / Thunder Client)
        ↓
API Server (Express.js)
        ↓
Router (products.routes.js)
        ↓
Data (products.data.js)
        ↓
Response JSON → Dikirim kembali ke client

## Struktur Proyek
```src/
├── app.js
├── data/
│   └── products.data.js
├── routes/
│   └── products.routes.js

```

---

## Endpoint CRUD
| Method | Endpoint | Deskripsi |
|:------:|:----------|:-----------|
| GET | `/api/products` | Tampilkan semua produk |
| GET | `/api/products/:id` | Tampilkan produk berdasarkan ID |
| POST | `/api/products` | Tambah produk baru |
| PUT | `/api/products/:id` | Perbarui data produk |
| DELETE | `/api/products/:id` | Hapus produk |

---

## Hasil Uji
✅ Semua endpoint CRUD berfungsi dan mengembalikan status code yang sesuai.  
✅ Response JSON terstruktur rapi.  

---

## Kesimpulan
RESTful API sederhana berhasil dibuat dan diuji dengan Express.js.  
Seluruh operasi **Create, Read, Update, Delete** berjalan sesuai fungsinya.