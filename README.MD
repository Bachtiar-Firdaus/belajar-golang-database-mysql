# Materi Golang Database MySQL

## Daftar Isi
- Pendahuluan
- Pengenalan Package Database
- Menambah Database Driver
- Membuka Koneksi ke Database
- Database Pooling
- Eksekusi Perintah SQL
- Query SQL
- Tipe Data Column
- SQL Injection
- SQL dengan Parameter
- Auto Increment
- Prepare Statement
- Database Transaction
- Repository Pattern

---

## Ringkasan Materi

### Pendahuluan
Pengantar tentang penggunaan database MySQL di Golang.

### Pengenalan Package Database
Penjelasan tentang package `database/sql` sebagai standar akses database di Golang.

### Menambah Database Driver
Cara menambahkan driver MySQL (misalnya `github.com/go-sql-driver/mysql`) agar bisa digunakan dengan `database/sql`.

### Membuka Koneksi ke Database
Langkah-langkah membuka koneksi ke MySQL menggunakan `sql.Open` dan konfigurasi DSN.

### Database Pooling
Konsep connection pooling di Golang, pengaturan `SetMaxOpenConns`, `SetMaxIdleConns`, dan `SetConnMaxLifetime`.

### Eksekusi Perintah SQL
Menjalankan perintah SQL seperti `INSERT`, `UPDATE`, `DELETE` dengan `Exec`.

### Query SQL
Mengambil data dari database menggunakan `Query` dan `QueryRow`.

### Tipe Data Column
Mapping tipe data MySQL ke tipe data Golang, serta cara membaca hasil query.

### SQL Injection
Penjelasan tentang bahaya SQL Injection dan cara mencegahnya.

### SQL dengan Parameter
Menggunakan parameterized query untuk keamanan dan efisiensi.

### Auto Increment
Cara menggunakan kolom auto increment dan mengambil nilai ID terakhir dengan `LastInsertId`.

### Prepare Statement
Membuat prepared statement untuk eksekusi query berulang dengan performa lebih baik.

### Database Transaction
Menggunakan transaksi (`Begin`, `Commit`, `Rollback`) untuk operasi database yang kompleks.

### Repository Pattern
Implementasi repository pattern untuk memisahkan logika akses data dari business logic.

---

## Catatan
- Materi ini fokus pada **penggunaan MySQL di Golang** dengan package `database/sql`.  
- Disertai pembahasan **best practice** seperti connection pooling, prepared statement, dan repository pattern.  
- Cocok buat backend development yang butuh integrasi database secara aman dan efisien.
