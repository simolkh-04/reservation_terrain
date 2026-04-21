<p align="center">
    <a href="https://laravel.com" target="_blank">
        <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
    </a>
</p>

<p align="center">
    <a href="https://github.com/NIZAR-BENAKKADOU/FIELD-RESERVATIONS/actions">
        <img src="https://img.shields.io/badge/build-passing-brightgreen" alt="Build Status">
    </a>
    <a href="https://packagist.org/packages/laravel/framework">
        <img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads">
    </a>
    <a href="https://packagist.org/packages/laravel/framework">
        <img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version">
    </a>
    <a href="https://opensource.org/licenses/MIT">
        <img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">
    </a>
</p>

# ⚡ KOORA.MA — Midnight Stadium Edition

> A premium web application for field reservations, designed with a deep "Midnight" aesthetic and neon accents.  
> Developed with **Laravel** (Backend), **MySQL** (Database), and **TailwindCSS** (Frontend).

---

## 🚀 Features

- **🎨 Midnight Stadium Theme**  
  A completely custom dark mode featuring deep blue backgrounds (`#0B1120`), vibrant neon green accents (`#10B981`), and glassmorphism effects.

- **⏳ Live Dashboard Widgets**
  - **Kickoff Countdown**: Real-time countdown to your next match.
  - **Weather Widget**: Live weather updates for game day preparation.

- **🏟️ Field Reservations**  
  Interactive booking system with real-time availability and instant confirmation.

- **👤 User Management**  
  Secure authentication, profile management, and booking history tracking.

- **📱 Responsive Design**  
  Fully optimized for all devices using TailwindCSS.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/simolkh-04/reservation_terrain
cd reservation_terrain
```

### 2. Install dependencies

```bash
composer install
npm install
```

### 3. Setup environment

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Configure your database

Edit the `.env` file and set your database credentials:

```env
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

Then run migrations:

```bash
php artisan migrate
```

### 5. Run the application

```bash
php artisan serve
npm run dev
```

The app will be available at [http://localhost:8000](http://localhost:8000).

---

## 📂 Project Structure

| Layer | Technology | Role |
|---|---|---|
| Backend | Laravel | Auth, reservation logic, data management |
| Database | MySQL | Storage & queries |
| Frontend | TailwindCSS | Styling & responsive design |

---

## 📄 License

This project is open-sourced under the [MIT License](https://opensource.org/licenses/MIT).