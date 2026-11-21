# Technical Test – Integration Analyst

**Nama:** Welly Wibowo  
**Posisi:** Integration Analyst

---

## Soal 1 – Deskripsi Diagram

### 1. Gambaran Umum

Diagram tersebut menggambarkan ekosistem teknologi untuk mendukung pengembangan aplikasi mobile fintech, khususnya aplikasi pinjaman online yang terintegrasi dengan Core Banking System.

Terdapat beberapa komponen teknologi yang memiliki fungsi masing-masing dalam mendukung proses pengembangan aplikasi, integrasi layanan, dokumentasi API, serta monitoring dan deployment.

### 2. Penjelasan Komponen

**A. Mobile Application**

Mobile Application merupakan aplikasi yang digunakan oleh pengguna untuk mengakses layanan pinjaman online. Aplikasi ini menjadi antarmuka utama bagi pengguna untuk melakukan aktivitas seperti pengajuan pinjaman dan melihat informasi terkait layanan.

**B. Service Worker**

Service Worker merupakan teknologi yang berjalan di sisi aplikasi dan dapat menangani proses tertentu di background. Contoh penggunaannya adalah caching, mendukung notifikasi, dan menyediakan kemampuan offline pada aplikasi.

**C. SOA (Service-Oriented Architecture)**

SOA merupakan pendekatan arsitektur yang memungkinkan berbagai layanan atau service berkomunikasi dan saling terintegrasi.

Pada diagram, SOA memiliki empat prinsip utama:

- **Reuse:** Layanan dapat digunakan kembali oleh sistem atau aplikasi lain.
- **Process:** Layanan mendukung kebutuhan dan proses bisnis.
- **Platform:** Memungkinkan integrasi dengan berbagai platform dan sistem.
- **Practice:** Menerapkan standar, praktik, serta tata kelola integrasi.

**D. Core Banking System**

Core Banking System merupakan sistem utama perbankan yang menangani operasional perbankan, seperti informasi rekening, saldo, dan transaksi keuangan.

Dalam konteks aplikasi pinjaman online, Core Banking System dapat diintegrasikan untuk mendukung proses bisnis yang berkaitan dengan layanan perbankan, seperti validasi informasi rekening dan pemrosesan transaksi sesuai kebutuhan.

**E. OpenAPI 3.1**

OpenAPI 3.1 merupakan spesifikasi standar untuk mendokumentasikan REST API. Dokumentasi ini mencakup endpoint, HTTP method, parameter, struktur request dan response, serta schema data.

Dengan adanya OpenAPI, developer dapat memahami kontrak API yang digunakan sehingga proses pengembangan dan integrasi antar-sistem menjadi lebih konsisten.

**F. Jenkins**

Jenkins merupakan automation server yang digunakan untuk mendukung proses Continuous Integration dan Continuous Delivery (CI/CD).

Jenkins dapat membantu mengotomatisasi proses build, automated testing, dan deployment aplikasi sehingga proses pengembangan serta rilis aplikasi menjadi lebih efisien.

**G. Kibana**

Kibana merupakan tools visualisasi dan analisis data yang dapat digunakan untuk memantau log aplikasi dan sistem.

Dalam proses integrasi, Kibana membantu tim melakukan monitoring, menelusuri error, menganalisis aktivitas sistem, serta melakukan troubleshooting ketika terjadi permasalahan.

### 3. Gambaran Alur Integrasi

Berdasarkan komponen yang ditampilkan, gambaran alur integrasi dapat dijelaskan sebagai berikut:

1. Pengguna mengakses layanan pinjaman online melalui Mobile Application.
2. Mobile Application berkomunikasi dengan layanan yang disediakan melalui API.
3. SOA berperan dalam mengatur komunikasi dan integrasi antar-layanan.
4. SOA melakukan integrasi dengan Core Banking System untuk mendukung kebutuhan proses bisnis perbankan.
5. OpenAPI 3.1 digunakan sebagai dokumentasi dan standar kontrak API.
6. Jenkins mendukung proses build, testing, dan deployment, sedangkan Kibana digunakan untuk monitoring serta analisis log.

### 4. Kesimpulan

Secara keseluruhan, diagram tersebut menggambarkan ekosistem teknologi yang mendukung pengembangan aplikasi fintech dan integrasinya dengan Core Banking System.

SOA berperan sebagai pendekatan arsitektur integrasi, OpenAPI 3.1 mendukung standardisasi dokumentasi API, Jenkins membantu otomatisasi proses deployment, dan Kibana mendukung monitoring serta troubleshooting.

Dengan penerapan komponen tersebut, proses integrasi antar-sistem diharapkan dapat berjalan secara lebih terstruktur, terukur, dan mudah dipelihara.

### 5. Diagram Arsitektur

Berikut merupakan visualisasi hubungan antar-komponen berdasarkan interpretasi terhadap diagram yang diberikan.

![Diagram Arsitektur Integrasi](diagrams/diagram-arsitektur-integrasi.png)
