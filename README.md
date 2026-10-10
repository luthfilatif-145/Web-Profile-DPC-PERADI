# Web Profile - DPC PERADI Pontianak

A website for DPC PERADI Pontianak (Indonesian Advocates Association, Pontianak chapter) with an admin panel to manage advocate data, regulations, and the content shown on the public site. Built with PHP.

## Features

**Public Website**
- Home page (`index.php`)
- Services (`layanan.php`)
- Organizational structure (`struktur.php`)
- Regulations with downloadable documents (`peraturan.php`)
- Advocate education program - PKPA (`pkpa.php`)
- Advocate profession exam - UPA (`upa.php`)
- Advocate oath information (`sumpah.php`)
- Photo gallery (`galeri.php`)

**Admin Panel**
- Admin login and logout
- [Admin registration with verification by an existing admin]
- Dashboard
- Advocate data management: list, detail, add, edit, delete, and [import]
- Regulation management with PDF upload
- Gallery management
- Services management
- Organization structure management
- Running text management

## Tech Stack

- PHP
- [MySQL]
- [HTML / CSS / JavaScript]
- [XAMPP for local development]

## Project Structure

```
├── admin/
│   ├── assets/ image/ partials/   # Admin resources and layout
│   ├── dashboard.php
│   ├── data_advokat.php           # Advocate data
│   ├── peraturan.php              # Regulations
│   ├── galeri.php                 # Gallery
│   ├── layanan.php                # Services
│   ├── struktur_pengurus.php      # Organization structure
│   ├── koneksi.php                # Database connection
│   └── proses_*.php               # Form handlers
├── uploads/peraturan/             # Uploaded regulation documents
├── index.php
├── layanan.php
├── peraturan.php
├── pkpa.php
├── upa.php
├── sumpah.php
├── struktur.php
├── galeri.php
├── header.php
└── footer.php
```

## Installation

1. Clone this repository
```
   git clone https://github.com/luthfilatif-145/Web-Profile-DPC-PERADI.git
```
2. Move the project folder into your `htdocs` directory (XAMPP)
3. Create a MySQL database named `[database_name]` [and import the SQL file if available]
4. Edit `admin/koneksi.php` with your own database credentials
5. Start Apache and MySQL, then open `http://localhost/Web-Profile-DPC-PERADI`
6. Admin panel: `http://localhost/Web-Profile-DPC-PERADI/admin`


## Contributors

- Luthfi Latif - [GitHub](https://github.com/luthfilatif-145)
- [Alvonda47](https://github.com/Alvonda47)
