# 🏥 Mediva – Hastane Randevu ve Sonuç Takip Sistemi

**Mediva**, hastalar için geliştirilen, randevu alma ve tıbbi sonuçları tek bir platformdan takip etmeyi sağlayan **Full-Stack mobil hastane yönetim uygulamasıdır**.  
Bu proje, **modern mobil ve backend teknolojileri**, **Clean Architecture** yaklaşımı ve **gerçek hayata yakın senaryolar** esas alınarak geliştirilmiştir.

> 🎯 **Amaç:**  
> Sağlık sektöründe ölçeklenebilir, güvenli ve kullanıcı odaklı bir mobil uygulama mimarisi ortaya koymak.

---

## 🔍 Proje Özeti

- **Platform:** Mobile (Flutter) + RESTful API
- **Mimari:** Clean Architecture (Data / Domain / Presentation)
- **Yetkinlik Alanları:**  
  - Mobil Uygulama Geliştirme (Flutter)  
  - Backend API Geliştirme (ASP.NET Core)  
  - Kimlik Doğrulama & Güvenlik  
  - Veritabanı Tasarımı  
  - Push Notification & Localization  

---

## 🚀 Öne Çıkan Özellikler

### 🔐 Authentication & Security
- JWT tabanlı kullanıcı kimlik doğrulama
- HMACSHA512 ile güvenli parola hashleme
- E-posta doğrulama kodu ile şifre sıfırlama
- Token saklama ve otomatik oturum yenileme

### 📅 Akıllı Randevu Yönetimi
- Şube ➜ Poliklinik ➜ Doktor ➜ Tarih ➜ Saat hiyerarşisi
- Backend üzerinden anlık dolu saat kontrolü
- Aktif / geçmiş randevu ayrımı
- İptal edilen randevularda saatlerin otomatik açılması

### 🧪 Tıbbi Sonuç Takibi
- Laboratuvar sonuçlarının referans aralıklarıyla gösterimi
- Normal / Anormal durum analizi
- Radyoloji raporlarının PDF formatında uygulama içinden görüntülenmesi
- Arama ve filtreleme yetenekleri

### 🔔 Push Notification Sistemi
- Firebase Cloud Messaging (FCM) entegrasyonu
- Randevu alındığında ve iptal edildiğinde anlık bildirim
- Bildirim geçmişi ve okundu bilgisi
- UI üzerinde badge (kırmızı nokta) gösterimi

### ⚙️ Kullanıcı Deneyimi & Ayarlar
- Türkçe 🇹🇷 / İngilizce 🇺🇸 çoklu dil desteği
- Dinamik tema sistemi (Mavi, Kırmızı, Yeşil, Siyah)
- Admin taraflı TXT dosyasıyla toplu veri yükleme simülasyonu

---

## 🛠️ Kullanılan Teknolojiler

### 📱 Mobile – Flutter
- **State Management:** BLoC / Cubit
- **Networking:** Dio
- **Architecture:** Clean Architecture
- **Localization:** intl, flutter_localizations
- **Notifications:** firebase_messaging
- **Local Storage:** shared_preferences

### 🖥️ Backend – ASP.NET Core 8.0
- **API Type:** RESTful Web API
- **Authentication:** JWT
- **Security:** HMACSHA512 Password Hashing
- **Database:** PostgreSQL (Entity Framework Core)
- **Services:** SMTP Mail Service, Firebase Admin SDK
- **Extras:** Data Seeding, Role-based yapı

---

## 🧠 Kazanılan Yetkinlikler

- Full-Stack mobil uygulama geliştirme deneyimi
- Clean Architecture prensiplerinin pratikte uygulanması
- Gerçek hayat senaryolarına uygun API tasarımı
- Güvenli authentication & authorization süreçleri
- Flutter + ASP.NET Core entegrasyonu
- Bildirim, localization ve tema yönetimi

---

## 👩‍💻 Geliştirici

**Mervenur Altunkaya**  

📧 **E-posta:** mervenuraltunkaya1@gmail.com  
🔗 🔗 **LinkedIn:** [Profilim](https://www.linkedin.com/in/mervenur-altunkaya-/) 


