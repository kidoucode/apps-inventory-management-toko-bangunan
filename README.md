# Aplikasi Desktop Inventory Management - Toko Bangunan (Java Netbeans dan MySQL)

Aplikasi ini merupakan sistem untuk membantu pengelolaan persediaan barang di toko bangunan secara terintegrasi dan efisien. Aplikasi ini dibangun dengan **Java Swing** untuk antarmuka pengguna dan **MySQL** sebagai database.
 
Aplikasi ini mendukung manajemen data barang, transaksi barang masuk dan keluar, hingga penyajian laporan inventori yang lengkap. Cocok digunakan untuk tugas akhir, skripsi, studi kasus bisnis toko bangunan, maupun implementasi sistem inventory skala kecil hingga menengah. 

> **⚠️Disclaimer:** Repository ini hanya menyediakan versi demo.. Jika ingin mendapatkan versi lengkap, dapat dibeli di [LYNK.ID KidouCode](https://lynk.id/kidoucode).

---

#### 📸 **Preview Aplikasi**

<p align="center">
  <img 
    src="https://pcobvoevxdmgjvpiorua.supabase.co/storage/v1/object/public/apps-inventory-management-toko-bangunan/Screenshot%20Form%20Login.png"
    width="600"
    alt="Form Login"
  />
</p>

<p align="center">
  <img 
    src="https://pcobvoevxdmgjvpiorua.supabase.co/storage/v1/object/public/apps-inventory-management-toko-bangunan/Screenshot%20Dashboard.png"
    width="600"
    alt="Dashboard"
  />
</p>

<p align="center">
  <img 
    src="https://pcobvoevxdmgjvpiorua.supabase.co/storage/v1/object/public/apps-inventory-management-toko-bangunan/Screenshot%20Menu%20Barang.png"
    width="600"
    alt="Menu Barang"
  />
</p>

<p align="center">
  <img 
    src="https://pcobvoevxdmgjvpiorua.supabase.co/storage/v1/object/public/apps-inventory-management-toko-bangunan/Screenshot%20Menu%20Input%20Barang%20Masuk.png"
    width="600"
    alt="Input Barang Masuk"
  />
</p>

<p align="center">
  <img 
    src="https://pcobvoevxdmgjvpiorua.supabase.co/storage/v1/object/public/apps-inventory-management-toko-bangunan/Screenshot%20Preview%20Laporan%20Stok%20Barang.png"
    width="600"
    alt="Preview Laporan Stok Barang"
  />
</p>


#### 🖥️ **Teknologi**
- 🗄️[MySQL 8.0.40](https://downloads.mysql.com/archives/get/p/25/file/mysql-installer-community-8.0.40.0.msi)  
- ☕[JDK 11](https://www.oracle.com/id/java/technologies/javase/jdk11-archive-downloads.html)  

> 📌 **Catatan :** Untuk menjalankan versi demo, cukup menggunakan **JDK 11**, karena database sudah di-host secara online.  
Namun, koneksi ke database mungkin mengalami keterlambatan.

---

#### 📚 **Library / Dependensi**

- 📈 **Chart**
    - `jcommon-1.0.23.jar` → Library pendukung JFreeChart yang menyediakan utilitas umum untuk pengolahan data, formatting, dan struktur pendukung grafik.
    - `jfreechart-1.0.19.jar` → Library untuk membuat berbagai jenis grafik (bar, line, pie, area, dll) di Java Swing atau aplikasi desktop lainnya.  

- 📅 **DatePicker**
  - `miglayout-core.jar` → Versi inti MigLayout yang digunakan oleh DatePicker untuk penataan layout.  
  - `miglayout-swing.jar` → Implementasi MigLayout untuk komponen Swing, mempermudah pengaturan tata letak DatePicker.  
  - `swing-datetime-picker-1.2.3.jar` → Komponen Swing untuk memilih tanggal dan waktu (date & time picker).  

- 🎨 **FlatLaf (Java Look and Feel)**  
  - `flatlaf-3.5.2.jar` → Tema modern Java Swing  
  - `flatlaf-3.5.2-sources.jar` → Source code untuk referensi/debug  
  - `flatlaf-extras-3.5.2.jar` → Fitur tambahan seperti custom accent color, font, dan icon  
  - `flatlaf-fonts-roboto-2.137.jar` → Font Roboto bawaan  
  - `flatlaf-intellij-themes-3.2.5.jar` → Tema mirip IntelliJ IDEA  
  - `jsvg-1.4.0.jar` → Render gambar SVG untuk icon  

- 🧩 **MigLayout**  
  - `miglayout-core-5.3.jar` → Layout manager inti  
  - `miglayout-swing-5.3.jar` → Integrasi untuk Swing  

- 💠 **Modal Dialog**  
  - `modal-dialog-2.1.0.jar` → Dialog kustom dengan animasi  
  - `modal-dialog-demo-2.1.0.jar` → Contoh penggunaan  

- 🗄️ **MySQL Driver**  
  - `mysql-connector-j-8.0.31.jar` → JDBC driver MySQL 

- 🔐 **Hashing**  
  - `jbcrypt-0.4.jar` → Hash password dengan BCrypt  

- 📊 **Excel (Apache POI)**  
  - `commons-collections4-4.4.jar` → Koleksi tambahan untuk POI  
  - `commons-compress-1.19.jar` → Kompresi/dekompresi file  
  - `poi-4.1.2.jar` → Apache POI core  
  - `poi-ooxml-4.1.2.jar` → Format Office baru (XLSX, DOCX, PPTX)  
  - `poi-ooxml-schemas-4.1.2.jar` → Skema OOXML  
  - `stax-api-1.0.1.jar` → Parsing XML streaming  
  - `xmlbeans-3.1.0.jar` → Pemrosesan XML untuk POI  

- 🧾 **Jasper Report**
  - `commons-beanutils-1.9.4.jar` → Utility untuk memanipulasi properti JavaBean (digunakan JasperReports).  
  - `commons-collections4-4.4.jar` → Struktur data tambahan untuk koleksi Java (digunakan JasperReports).  
  - `commons-digester-1.7.jar` → Parser XML berbasis aturan (rule-based XML parser) untuk JasperReports.  
  - `commons-logging-1.3.0.jar` → Library logging generik yang digunakan JasperReports.  
  - `groovy-4.0.16.jar` → Bahasa scripting Groovy, digunakan JasperReports untuk ekspresi dinamis.  
  - `jasperreports-6.20.6.jar` → Core JasperReports untuk membuat laporan PDF, XLS, HTML, dll.  
  - `jasperreports-fonts-7.0.1.jar` → Font tambahan untuk laporan JasperReports.  
  - `opendf-1.3.3.0.jar` → Library untuk mengelola OpenDocument Format (ODF) di JasperReports.  
---
> 📌 **Catatan:** Beberapa library seperti `commons-collections4` digunakan oleh lebih dari satu modul (POI & JasperReports).


#### ✨ **Fitur Utama**
- Manajemen Data Barang
- Manajemen Kategori Barang
- Manajemen Merk
- Manajemen Satuan
- Manajemen Rak
- Manajemen Gudang
- Manajemen Data Supplier
- Transaksi Barang Masuk
- Transaksi Barang Keluar
- Stock Opname (Pengecekan Stok Fisik)
- Laporan Stok Barang
- Laporan Barang Masuk
- Laporan Barang Keluar
- Laporan Stock Opname

---

#### 🏗️ **Arsitektur Proyek (Package)**
- **Assets** : Menyimpan ikon, gambar, dan resource visual lain yang digunakan aplikasi.
- **Config** : Menangani konfigurasi koneksi aplikasi dengan database.
- **Controller** : Menangani alur logika aplikasi, menerima aksi dari UI (Form/Form Input), memanggil Service, serta mengatur respon yang dikembalikan ke UI.
- **DAO** : Menangani akses langsung ke database (query CRUD) berdasarkan Model.
- **Form** : Mengatur tampilan dan interaksi data dalam bentuk tabel (UI/View).
- **Form Input** : Mengatur tampilan dan interaksi form untuk input dan edit data (UI/View).
- **Main** : Mengatur inisialisasi aplikasi, tampilan awal, dan menu utama.
- **Model** : Mewakili struktur entitas sesuai tabel database.
- **Service** : Mendefinisikan antarmuka (interface) logika bisnis dan operasi CRUD.
- **Service Impl** : Implementasi logika bisnis, menjembatani Controller dengan DAO.
- **TableModel** : Model tabel khusus untuk JTable sebagai penghubung data Model ke View.
- **Themes** : Mengatur tema warna, gaya, dan layout aplikasi.
- **Util** : Berisi fungsi-fungsi utilitas umum yang digunakan lintas layer.
- **Jasper** : Menyimpan file laporan .jrxml dan .jasper.

---

#### 🚀 **Instalasi & Menjalankan Aplikasi**

**1. Clone Repository**
```sh
git clone https://github.com/kidoucode/apps-inventory-management-toko-bangunan.git
```

**2. Masuk ke Direktori Proyek** :
```sh
cd apps-inventory-management-toko-bangunan
```

**3. Jalankan Aplikasi** :

Ada 2 cara untuk menjalankan aplikasi, tidak wajib melalui terminal/CMD.

**Opsi A — Melalui Terminal / Command Prompt (Disarankan)**

Gunakan cara ini jika ingin memastikan aplikasi berjalan tanpa error.
```sh
java -jar InventoryManagement.jar
```
Pastikan:
- Java (JDK/JRE) sudah terinstall
- Perintah java bisa dijalankan di terminal (java -version)

**Opsi B — Klik Langsung File JAR**

Jika Java sudah terinstall:
- Masuk ke folder proyek
- Double-click file InventoryManagement.jar
- Aplikasi akan berjalan otomatis

📌 **Catatan:**
`Jika double-click tidak bereaksi, berarti Java belum terasosiasi dengan file .jar, gunakan Opsi A.`

**4. Login ke Aplikasi** :
```sh
Username : admin
Password : admin
```
Terima kasih

