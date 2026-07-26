# Docker & Portaine Management Setup

Selamat datang di panduan Docker & Portainer *Deployment*! Proyek ini mendemonstrasikan instalasi dan konfigurasi Docker engine yang dikelola menggunakan Portainer sebagai *interface* berbasis web untuk mempermudah manajemen *container*, *images*, *networks*, dan *volumes*.

---

## 💡 Ringkasan Proyek

!!! abstract "Tujuan & Ruang Lingkup"
    Proyek ini bertujuan untuk membangun infrastruktur berbasis *container* yang efisien dan mudah dikelola. Fokus utama mencakup instalasi Docker di lingkungan Linux, setup Portainer sebagai dasbor kontrol terpusat, serta manajemen siklus hidup kontainer (deploy, monitoring, dan scaling). Anda akan belajar cara mengelola layanan aplikasi secara terisolasi tanpa perlu konfigurasi manual yang kompleks di tingkat sistem operasi host.

---

## ⚙️ Teknologi yang Digunakan

*   :material-linux: **Sistem Operasi:** Debian 13 (Bookworm)
*   :material-microsoft-windows: **Sistem Pengetesan:** Windows 11
*   :material-firefox: **Aplikasi Akses** Firefox
*   :material-docker: **Container Engine:** Docker Community Edition (CE)
*   :material-view-dashboard: **Management UI:** Portainer CE

---

## 🚀 Langkah-langkah Implementasi

### 1. :material-download: Install ISO Debian 13

- Pertama - tama, Kalian bisa download debian 13 server untuk di implementasikan ke laptop bekas  atau VMWare di link bawah:

[Download Debian 13](https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/debian-13.4.0-amd64-netinst.iso){ .md-button .md-button--primary }

### 2. 