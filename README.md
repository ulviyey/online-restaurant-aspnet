#  English Version

# 🍽️ Lezzet Pikseli | Next-Gen Restaurant Automation & Management System

**Lezzet Pikseli** is a comprehensive, full-stack restaurant management solution built on modern backend principles. [cite_start]It digitizes traditional restaurant operations to maximize efficiency and user experience[cite: 20].

> **⚠️ Project Status:** This repository serves as a **Technical Showcase**. As the project is being prepared for commercial use, the source code remains private. Technical depth is demonstrated through the documentation and video walkthroughs below.

## 👥 Contributors & Roles
* **Ulviye Gülnihal Yüksel:** Backend Architecture, Relational Database Design (MS SQL), Security Protocols, Business Logic, and Deployment.
* **Emine Kömürcü:** Frontend UI/UX Design, Responsive Layout Implementation, and Visual Assets.

## 🛠️ Tech Stack
* [cite_start]**Framework:** .NET 9.0 (ASP.NET Core MVC)[cite: 43, 863].
* [cite_start]**Data & ORM:** Entity Framework Core (Code-First), MS SQL Server[cite: 76, 881].
* [cite_start]**Frontend:** Bootstrap 5, JavaScript (ES6+), jQuery, Ajax[cite: 59].
* [cite_start]**Architecture:** Dependency Injection (DI), Area-Based Routing (Admin/Default), N-Tier logic[cite: 43, 67, 72].
* [cite_start]**Security:** Cookie-Based Authentication, Role-Based Authorization, Anti-Forgery Tokens (CSRF protection)[cite: 123, 135].

## ✨ Core Features & Video Walkthroughs

### **1. Menu, Authentication & UX**
Comprehensive user flow including dynamic menu browsing and secure account management.
* [cite_start]**Features:** Dynamic category listing, secure login/register, and responsive UI[cite: 26, 27].
* 📺 **[Watch Demo: Menu & Authentication](https://drive.google.com/file/d/15sxMy7t05v60wVaBRRVNJZWnf4N5K-mK/view?usp=sharing)**

### **2. Ordering Flow & Progress Tracking**
A seamless end-to-end ordering experience with real-time feedback.
* [cite_start]**Features:** LocalStorage-based cart management, automated order creation, and a dynamic progress bar tracking ("Received" to "Delivered")[cite: 32, 119, 152].
* 📺 **[Watch Demo: Ordering & Real-time Tracking](https://drive.google.com/file/d/1-IW0vB3BMR6JXzl-6BNmYUYSFlwMEIkK/view?usp=sharing)**

### **3. Admin Management & CMS**
Powerful back-office tools for restaurant owners to control every aspect of their digital presence.
* [cite_start]**Features:** Full CRUD for categories/products, reservation management (Approve/Edit/Delete), automated folder hierarchy for assets, and GUID-based file naming[cite: 38, 112, 115].
* 📺 **[Watch Demo: Admin Operations & CMS](https://drive.google.com/file/d/1doAUqWCZnez9zd5TVa2MtjPzasfMywJX/view?usp=sharing)**

## 🏗️ Engineering Highlights
* [cite_start]**Automated Asset Management:** Custom logic to sanitize file names and use GUIDs to prevent server-side naming conflicts[cite: 110, 112].
* [cite_start]**Relational Integrity:** Implemented 1:N relationships between Categories, Products, and Orders using Fluent API[cite: 93, 94].
* [cite_start]**Server-Side Paging:** Optimized Admin Dashboard performance using `.Skip()` and `.Take()` methods for handling large datasets[cite: 714].

## 🌐 Live Demo
Explore the application at: [thegardenry.com.tr](https://thegardenry.com.tr/)

---

# 🇹🇷 Türkçe Versiyon

# 🍽️ Lezzet Pikseli | Yeni Nesil Restoran Otomasyon & Yönetim Sistemi

**Lezzet Pikseli**, modern backend prensipleri üzerine inşa edilmiş, uçtan uca bir restoran yönetim çözümüdür. [cite_start]Geleneksel restoran operasyonlarını dijitalleştirerek verimliliği ve kullanıcı memnuniyetini en üst düzeye çıkarmayı hedefler[cite: 20].

> **⚠️ Proje Durumu:** Bu depo teknik bir **Vitrin (Showcase)** niteliğindedir. Proje ticari satışa hazırlandığı için kaynak kodları kapalı tutulmaktadır. Teknik yetkinlikler aşağıdaki dokümantasyon ve videolar aracılığıyla sergilenmektedir.

## 👥 Ekip ve Rol Dağılımı
* **Ulviye Gülnihal Yüksel:** Backend Mimarisi, İlişkisel Veri Tabanı Tasarımı (MS SQL), Güvenlik Protokolleri, İş Mantığı ve Yayınlama (Deployment).
* **Emine Kömürcü:** Frontend UI/UX Tasarımı, Responsive Arayüz Uygulaması ve Görsel Varlık Yönetimi.

## 🛠️ Teknoloji Yığını
* [cite_start]**Framework:** .NET 9.0 (ASP.NET Core MVC)[cite: 43, 863].
* [cite_start]**Veri & ORM:** Entity Framework Core (Code-First), MS SQL Server[cite: 76, 881].
* [cite_start]**Frontend:** Bootstrap 5, JavaScript (ES6+), jQuery, Ajax[cite: 59].
* [cite_start]**Mimari:** Bağımlılık Enjeksiyonu (DI), Alan Bazlı Yönlendirme (Area-Based Routing), Katmanlı Yapı[cite: 43, 67, 72].
* [cite_start]**Güvenlik:** Çerez Tabanlı Kimlik Doğrulama, Rol Tabanlı Yetkilendirme, Anti-Forgery Token (CSRF Koruması)[cite: 123, 135].

## ✨ Temel Özellikler ve Video Tanıtımları

### **1. Menü, Kimlik Doğrulama ve Kullanıcı Deneyimi**
Dinamik menü inceleme ve güvenli hesap yönetimini kapsayan kullanıcı akışı.
* [cite_start]**Özellikler:** Dinamik kategori listeleme, güvenli kayıt/giriş ve duyarlı (responsive) arayüz[cite: 26, 27].
* 📺 **[Demoyu İzle: Menü ve Kayıt Süreçleri](https://drive.google.com/file/d/15sxMy7t05v60wVaBRRVNJZWnf4N5K-mK/view?usp=sharing)**

### **2. Sipariş Akışı ve Takip Sistemi**
Anlık geri bildirimlerle desteklenen kesintisiz bir uçtan uca sipariş deneyimi.
* [cite_start]**Özellikler:** LocalStorage tabanlı sepet yönetimi ve siparişin her aşamasını ("Alındı"dan "Teslim Edildi"ye) gösteren canlı ilerleme çubuğu[cite: 32, 119, 152].
* 📺 **[Demoyu İzle: Sipariş Verme ve Canlı Takip](https://drive.google.com/file/d/1-IW0vB3BMR6JXzl-6BNmYUYSFlwMEIkK/view?usp=sharing)**

### **3. Yönetim Paneli (Admin) ve CMS**
İşletme sahipleri için dijital varlıklarını kontrol edebilecekleri güçlü yönetim araçları.
* [cite_start]**Özellikler:** Ürün ve kategoriler için tam CRUD desteği, rezervasyon yönetimi (Onayla/Düzenle/Sil) ve GUID tabanlı benzersiz dosya isimlendirme otomasyonu[cite: 38, 112, 115].
* 📺 **[Demoyu İzle: Yönetici Paneli İşlemleri](https://drive.google.com/file/d/1doAUqWCZnez9zd5TVa2MtjPzasfMywJX/view?usp=sharing)**

## 🏗️ Öne Çıkan Mühendislik Çözümleri
* [cite_start]**Dosya Yönetim Otomasyonu:** Sunucu tarafında isim çakışmalarını önlemek için GUID kullanımı ve dinamik klasör hiyerarşisi[cite: 110, 112].
* [cite_start]**Veri Bütünlüğü:** Kategoriler, Ürünler ve Siparişler arasında Fluent API kullanılarak kurgulanan sağlam ilişkisel yapı[cite: 93, 94].
* [cite_start]**Performans Optimizasyonu:** Büyük veri setlerinde hızlı yükleme sağlamak amacıyla uygulanan Sunucu Taraflı Sayfalama (Server-Side Paging)[cite: 714].

## 🌐 Canlı Demo
Uygulamayı canlı ortamda inceleyebilirsiniz: [thegardenry.com.tr](https://thegardenry.com.tr/)

---
