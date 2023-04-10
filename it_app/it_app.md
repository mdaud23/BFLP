# Pengenalan Divisi App

# Database Awareness
Index pada database adalah pengelompokkan dan penataan column yg sering digunakan untuk pencarian dan pengelompokkan data
- Data disimpan secara berurutan
- Disimpan sesuai kategori
- Memiliki informasi lokasi data sehingga pencarian data lebih cepat

Aplikasi adalah motor, database adalah bahan bakar

<?> index setauku ngaruh ke query time aja, apa ngaruhnya ke aplikasi?'

kelambatan ga hanya terjadi di bagian infra, namun bisa dari sisi index database

<?> apakah ada bagian khusus yang mengurus optimasi query, misal bagusnya dikasih statement LIMIT ROW

strategi indexing: tanggal, no. rekening, nama, halaman

index mengecek pointer dulu, ga langsung ke table

Query explain untuk analisis query, ngasih ingpo dah ada indeks atau belum juga

tipe index: clustered dan non-clustered

ada checking unused index, index juga bisa dibuat berdasarkan rekomendasi

Hal yang perlu diperhatikan agar query where clause menggunakan index bukan melakukan table scan, antra lain:
- membuatkan index pada column2 yg digunakan untuk pencarian
- tidak melakukan transformasi pada column-column yg digunakan untuk pencarian
- tidak melakukan konversi tipe data pada column2 yg digunakan untuk pencarian
- tidak menggunakan like %% pada metode pencarian
- dipastikan tipe data parameter yg dimasukkan pada column pencarian sesuai dengan tipe data pada column yang ada pada table fisik pencarian

index terasa banget saat inner join, buat index di 2 tabel yang dijoin

Reorganized index und Rebuild index... indeks ga cuma dibiarin setelah dibuat, tapi juga harus dirawat agar tidak ada performance drop database. Parameter
yg digunakan adalah avg_fragmentation_in_percent

unused index, slow query, reorganized / rebuild

<?> berapa lama maintenance nya?

<!> using data to optimize maintenance timing

proses maintenance tetap dimonitoring

# How to Improve an Organization's Performance

GREAT SPIRIT

Resiliency, Open Banking, AI/ML

open banking is layanan finansial open agar bisa kerjasama dengan 3rd party

IT is enabler dari bisnis, dulu hanya support

Our impact, my lesson (share & learn culture), GoJira

## Performance Management
Terbiasa untuk menyampaikan pencapaian

## Change Management
Setiap perubahan itu tercatat

Collaborative more, bureaucratic less 

buatlah sederhana, simplicity enables speed

<?> maksud agile 10x?

## Application Integration dengan Middleware

Everything is moving & innovating digitally; pada aspek: digital platform, financial service, and business operation

Emergence of Bank 4.0

What's yg mendorong? consumerization of UX, OMNI-Channel Expenctation, Mobile, Generasi Milenial

Orkestrasi anak perusahaan (create ecosystem)

salah satu open banking is via BRIapi

Combining physical presence & Digital Capabilities

Digital Mindset: Delivering Continuous Product Innovation

Product oriented, not project oriented

Create great product not a perfect one

Adopt Agile Development Practice Reinforced by Modern Application Architecture

**Continuous** iteration which needs **dedicated team and people** to focus on **product** so we can deliver **faster and better**

ada praktek code review

Omni-Channel: mengintegrasikan aplikasi2

Next gen legacy modernization

Kitab suci orang IT di BRI (khususnya APP)

<!> ESB masih monolith, harusnya bisa microservice agar supaya composable

