# Veteriner Yönetim Sistemi - Full Stack Proje

## Genel Bilgiler

Bu proje, bir veteriner yönetim sistemidir ve hem frontend hem de backend bileşenlerinden oluşmaktadır. 

### Backend

Backend kısmı, Spring Boot ile geliştirilmiş bir REST API projesidir. API, hayvan sahipleri, doktorlar, randevular, aşılar ve raporlar gibi temel veri kayıtlarını yönetmek için kullanılabilir. Ayrıca, PostgreSQL veritabanı kullanılarak verilerin depolanması sağlanmıştır. Backend projesi, aşağıdaki teknolojileri kullanmaktadır:

- **Java 17**
- **Spring Boot**
- **Spring Web**
- **Spring Data JPA**
- **PostgreSQL**
- **Lombok**
- **Mapstruct**
- **Postman**
- **Swagger**

### Frontend

Frontend kısmı, React.js kullanılarak geliştirilmiştir. Kullanıcı arayüzü, veteriner yönetim sisteminin temel işlevlerini sunar. Sayfalar arası gezinme için React Router kullanılmıştır. Frontend projesi, aşağıdaki teknolojileri içermektedir:

- **JavaScript**
- **React**
- **Vite**
- **React Router**
- **Tailwind CSS**
- **Axios**



## Modüller

- **Customer**: Müşteri (hayvan sahibi) bilgilerini görüntüleme, ekleme, güncelleme ve silme.
- **Animal**: Hayvan bilgilerini görüntüleme, ekleme, güncelleme ve silme.
- **Doctor**: Veteriner bilgilerini görüntüleme, ekleme, güncelleme ve silme.
- **Available Date**: Veterinerler için uygun günleri görüntüleme, kaydetme, güncelleme ve silme.
- **Appointment**: Randevu görüntüleme, ekleme, güncelleme ve silme.
- **Vaccine**: Aşı bilgilerini görüntüleme, ekleme, güncelleme ve silme.
- **Report**: Rapor görüntüleme, ekleme, güncelleme ve silme.

## Deploy

Canlı siteye gitmek için -->[Tıklayın](https://vet-app-react-drab.vercel.app)
