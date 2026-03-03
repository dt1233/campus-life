<div align="center">
  <img src="https://via.placeholder.com/150/2c3e50/fbb81a?text=CL" alt="Campus Life Logo" width="120" />
  <h1>🎓 Campus Life</h1>
  <p><b>İnönü Üniversitesi için Geliştirilmiş Modern Kampüs Yaşam Platformu</b></p>
  
  <p>
    <img alt="Java" src="https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
    <img alt="React" src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
    <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-18-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  </p>
</div>

---

## 📖 Proje Özeti
**Campus Life**, üniversite öğrencileri ve personeli için geliştirilmiş yenilikçi ve kapsamlı bir kampüs yönetim sistemidir. İhbar yönetimi, kayıp eşya takibi, ikinci el pazar yeri ve proje fikri sunumu gibi kampüsü canlandıran özellikleri tek çatı altında toplar. Full-stack yapısı, güvenliği, gerçek zamanlı altyapısı ve rollere dayalı admin paneli ile uçtan uca eksiksiz bir deneyim sunar.

---

## ✨ Öne Çıkan Özellikler

### 📢 İhbar ve Bildirim Sistemi
* **Çoklu Kategori:** Gıda, Çevre ve Güvenlik alanlarında olay yeri fotoğraflı ihbar oluşturabilme.
* **Akıllı İş Akışı:** Bekleyen → İnceleniyor → Çözüldü/Reddedildi şeklinde detaylı loglama ve anlık durum takibi.
* **Dinamik Atama:** Admin paneli üzerinden ilgili birim personellerine anlık ihbar yönlendirmesi.

### 🛒 2. El Pazar Yeri
* **Gerçek Zamanlı Sohbet:** Alıcı ve satıcı arasında ilan bazlı hızlı iletişim ve anlık bildirimler.
* **Akıllı Filtreleme:** Kategori, durum, fiyat parametreleri ve *Haversine Algoritması* ile "yakınımdakileri göster" özelliği.
* **Moderatör Onayı:** Tüm ilanların güvenliği ve içeriği yayından önce detaylı bir admin iş akışından geçer.

### 🔍 AI Destekli Kayıp Eşya Sistemi
* **Akıllı Eşleştirme:** Sisteme girilen *Kayıp* ve *Bulundu* ilanlarını birbirleriyle analiz ederek yapay zeka ile eşleştirme önerileri sunar.

### 💡 Proje Fikri Paylaşım Modülü
* Öğrencilerin PDF/Sunum ekleriyle yenilikçi projelerini üniversite yönetimine iletebileceği ve puanlanabileceği özel yönetim sekmesi.

### 🔐 Gelişmiş Güvenlik ve RBAC (Role-Based Access Control)
* **Hibrit Auth:** Google OAuth2 ile üniversite maili entegrasyonu + JWT (Access/Refresh Token) mekanizması.
* **9+ Rol Katmanı:** Super Admin, Gıda Admini, Personeller, Moderatörler ve Standart kullanıcılar için `@PreAuthorize` ile en uç noktalarda korunan metotlar.

---

## 🛠️ Teknik Altyapı ve Mimari

### 💻 Backend
* **Dil & Framework:** Java 21, Spring Boot 3
* **Güvenlik:** Spring Security, OAuth2, JWT
* **Veritabanı & ORM:** PostgreSQL 18, Hibernate, Spring Data JPA
* **Versiyonlama:** Flyway Migration (8 farklı şema göçü)
* **Tasarım Kalıpları:** N-Tier Architecture, DTO Pattern, Entity Graph

### 🎨 Frontend
* **Kütüphane:** React.js
* **Arayüz Tasarımı:** Material UI (MUI), Özelleştirilmiş Temalar (Dark Blue & Gold)
* **Durum (State) Yönetimi:** Redux Toolkit
* **Route & İletişim:** React Router Dom, Axios

---

## 📸 Ekran Görüntüleri
*İstenilmesi durumunda iletilecektir.*

---

## 📋 Kurulum Adımları
Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin:

### Gereksinimler
- Java 21
- Node.js 18+
- PostgreSQL 18
- Maven

### Veritabanı Ayarları
PostgreSQL üzerinde `campus_life` adında bir veritabanı oluşturun ve `src/main/resources/application.yml` (veya `application.properties`) içerisindeki veritabanı url, kullanıcı adı ve şifre kısımlarını kendi sisteminize göre güncelleyin. *(Not: Tablolar Flyway sayesinde uygulama çalışınca otomatik oluşturulacaktır.)*

### Backend Çalıştırma
```bash
# Proje dizinine girin
cd campus_life
# Maven wrapper ile Spring Boot uygulamasını başlatın
./mvnw spring-boot:run
```

### Frontend Çalıştırma
```bash
# Frontend dizinine girin
cd frontend
# Bağımlılıkları yükleyin
npm install
# React geliştirme sunucusunu başlatın
npm start
```

---

<div align="center">
  <p><i>Bu proje, İnönü Üniversitesi kampüs yaşantısını iyileştirmek amacıyla Betsan Teknoloji tarafından geliştirilmiştir.</i></p>
</div>


