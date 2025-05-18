# lnt-final-project
Made an ecommerce website for Back End LNT Final Project

## 📁 Struktur Project

- `app/`, `routes/`, `resources/`: Tempat menyimpan kode utama.
- `public/`: Tempat file yang bisa diakses user (seperti gambar, CSS, JS).
- `node_modules/` dan `vendor/`: Folder ini **tidak disimpan di GitHub**, tapi akan otomatis dibuat ulang nanti.

---

## ✅ Langkah-langkah Menjalankan Project

### 1. Install Tools Wajib

install:
- [XAMPP](https://www.apachefriends.org/index.html)
- [Composer](https://getcomposer.org/download/)
- [Node.js & npm](https://nodejs.org/) (minimal versi 16+)

---

### 2. Clone Project dari GitHub

Buka terminal (Git Bash atau CMD), lalu jalankan:
```bash
git clone https://github.com/NAMA-KAMU/final_project.git
cd final_project

1. **Install Dependency PHP**

   ```bash
   composer install
   ```

2. **Install Dependency Frontend**

   ```bash
   npm install
   ```

3. **Copy dan atur file .env**

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **(Opsional) Set database di .env**
   Pandu dia untuk ganti `DB_DATABASE`, `DB_USERNAME`, dll di file `.env`.

5. **Jalankan server lokal**

   ```bash
   php artisan serve
   ```

---
