# CaGi Consulting – Web Platform

Professional web platform developed for the accounting and tax consulting firm *CaGi Consulting*.

The project is built with **Laravel** and designed with a strong focus on performance, security and maintainability.  
What started as a corporate website has evolved into a digital platform that supports both the firm's internal operations and client interactions.

---

## 🛠 Tech Stack

- **Backend**: Laravel
- **Frontend**: Blade Templates + Alpine.js
- **Styling**: Tailwind CSS (custom design system)
- **Infrastructure**: Linux VPS
- **Deployment**: Automated deployment via Laravel Forge

---

## 🚀 Key Features

### Platform Architecture
- **Component-based UI** using reusable Blade components for better maintainability.
- **Responsive design** with a mobile-first approach.
- **Optimized performance and clean layout** tailored for professional services.

### Security & Reliability
- Protection against automated scraping of contact information.
- Secure authentication system for client access.
- Security headers and best practices applied at application level.

### SEO & Visibility
- Structured data implementation using **schema.org** for local business and services.
- Dynamic meta tags and social preview support.
- Automatic sitemap generation.

### Client Area & Support System
- **Authenticated client portal** for accessing services and shared documents.
- **Document management** system for secure exchange of files between firm and clients.
- **Ticketing system** for structured client support requests.
- **Automated notifications** for important events such as document uploads or ticket updates.

### Administration
- **Admin dashboard** built with Filament for managing users, documents and support tickets.

---

## 🔒 Repository Notice

This repository is published as a **technical showcase** of the project.

Due to the nature of the platform and the presence of client-specific features, the complete production codebase remains private.

Source code can be shared for technical review upon request.

---

## 💻 Development Setup

```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm run dev
