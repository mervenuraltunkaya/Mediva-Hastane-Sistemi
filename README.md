🏥 Mediva – Hastane Randevu ve Sonuç Takip Sistemi

Mediva, hastalar için geliştirilmiş kapsamlı bir Mobil Hastane Yönetim Uygulamasıdır. Kullanıcılar bu uygulama üzerinden hastane randevularını alabilir, laboratuvar ve radyoloji sonuçlarını görüntüleyebilir ve sağlık süreçlerini takip edebilirler.

Proje, modern yazılım mimarileri kullanılarak Full-Stack (Uçtan Uca) bir çözüm olarak geliştirilmiştir.

🚀 Özellikler

🔐 Kimlik Doğrulama (Authentication)

Kayıt Ol: Ad, Soyad, TC Kimlik No, Telefon, Doğum Tarihi ve Uyruk bilgileriyle güvenli kayıt.

Giriş Yap: JWT (JSON Web Token) tabanlı güvenli oturum yönetimi.

Şifremi Unuttum: E-posta doğrulama kodu ile güvenli şifre sıfırlama.

Beni Hatırla: Otomatik oturum yenileme ve token saklama.

📅 Randevu Sistemi

Akıllı Randevu: Şube ➔ Poliklinik ➔ Doktor ➔ Tarih ➔ Saat hiyerarşisiyle kolay seçim.

Canlı Kontrol: Dolu saatlerin backend üzerinden anlık kontrolü (Dolu saatler pasif gelir).

Randevularım: Gelecek ve Geçmiş randevuların ayrı sekmelerde listelenmesi.

İptal Etme: Randevu iptal edildiğinde sistemden silinir ve saat boşa çıkar.

🧪 Sonuç Görüntüleme

Laboratuvar Sonuçları: Tahlil sonuçlarının detaylı listesi, referans aralıkları ve durum (Anormal/Normal) gösterimi.

Radyoloji Raporları: Görüntüleme raporlarının listelenmesi ve PDF olarak uygulama içinde açılması.

Filtreleme: Hastane bazlı, isme göre arama ve duruma göre filtreleme.

🔔 Bildirim Sistemi (Push Notifications)

Firebase (FCM) Entegrasyonu: Randevu alındığında veya iptal edildiğinde telefona anlık bildirim düşer.

Bildirim Geçmişi: Tüm bildirimler veritabanında saklanır ve uygulama içinden görüntülenebilir.

Okundu Takibi: Yeni bildirimler için Dashboard üzerinde kırmızı nokta (Badge) gösterimi.

⚙️ Ayarlar ve Altyapı

Çoklu Dil (Localization): Türkçe 🇹🇷 ve İngilizce 🇺🇸 desteği (Uygulama içinden anlık geçiş).

Dinamik Tema: Renk değiştirme özelliği (Mavi, Kırmızı, Yeşil, Siyah tema seçenekleri).

Veri Yükleme (Admin): TXT dosyası ile toplu laboratuvar sonucu yükleme simülasyonu.

🛠️ Teknolojiler ve Mimari

Bu proje Clean Architecture prensiplerine sadık kalınarak geliştirilmiştir.

📱 Frontend (Mobil) - Flutter

State Management: BLoC / Cubit

Architecture: Clean Architecture (Data, Domain, Presentation Layers)

HTTP Client: Dio

Localization: flutter_localizations, intl

Notifications: firebase_messaging

Storage: shared_preferences

🖥️ Backend (API) - ASP.NET Core 8.0 Web API

Database: PostgreSQL (Entity Framework Core)

Authentication: JWT (JSON Web Token)

Security: Password Hashing (HMACSHA512)

Services: SMTP Email Service, Firebase Admin SDK

Data Seeding: Başlangıç verilerinin otomatik yüklenmesi.

📸 Ekran Görüntüleri

Giriş Ekranı

Dashboard

Randevu Alma







Randevularım

Laboratuvar

Ayarlar







(Not: Ekran görüntülerini screenshots klasörüne eklemeyi unutmayın)

🏗️ Kurulum ve Çalıştırma

Gereksinimler

Flutter SDK (3.x veya üzeri)

.NET 8.0 SDK

PostgreSQL Veritabanı

Bir IDE (VS Code veya Android Studio)

1. Backend Kurulumu

cd Mediva.API
# appsettings.Development.json dosyasındaki DB ve Mail ayarlarını yapın.
dotnet restore
dotnet ef database update
dotnet run


2. Frontend (Mobil) Kurulumu

cd mediva
flutter pub get
# Dil dosyalarını üretmek için:
flutter gen-l10n
flutter run


📞 İletişim

Geliştirici: Mervenur Altunkaya

LinkedIn: Profilim

E-posta: mervenuraltunkaya1@gmail.com
