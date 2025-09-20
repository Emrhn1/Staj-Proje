# Staj-Proje

# Talep Yönetim Sistemi

Modern bir talep yönetim uygulaması. Admin ve kullanıcı rolleri ile farklı işlevsellikler sunan, React.js, Next.js, Typescript Redux Toolkit ile geliştirilmiş bir web uygulaması.
(Gizlilik sebebi ile projenin kodları paylaşılmamaktadır.)

## 🚀 Özellikler

### 🔐 Kimlik Doğrulama
- Role-based authentication (Admin/User)
- LocalStorage ile oturum persistance
- Otomatik role-based yönlendirme

### 📋 Talep Yönetimi
- Talep oluşturma ve düzenleme
- Durum takibi (Bekliyor, Onaylandı, Tamamlandı)
- Admin onay sistemi
- Toplu işlemler (Seç/Onayla/Reddet)

### 📦 Ürün Yönetimi
- **Admin**: Ürün oluşturma ve yönetimi
- **User**: Ürün önerisi gönderme
- Kategori bazlı filtreleme

### 👥 Kullanıcı Yönetimi
- Kullanıcı oluşturma (Admin)
- Kullanıcı arama ve filtreleme
- Rol bazlı erişim kontrolü

---

## 🛠 Teknoloji Stack

- **Framework**: React.js 18, Next.js 14  
- **State Management**: Redux Toolkit  
- **UI Framework**: Material-UI + Custom Components  
- **Type Safety**: TypeScript  
- **Styling**: Custom CSS + Material-UI theming  

---

## 📸 Ekran Görüntüleri ve Açıklamalar

### 1. Dashboard (Ana Sayfa)
![Dashboard](image![dashboard](https://github.com/user-attachments/assets/574168a8-aeb9-41db-b3a6-e05d924dde8c)
-1)

**Admin Dashboard** - Sistem geneline dair özet bilgiler:
- İstatistik Kartları: Dinamik olarak Gelen, Onaylanan ve Reddedilen talep sayıları
- Öncelikli Talepler: Son taleplerin önizlemesi
- Hızlı Erişim Menüleri: Talepler ve Ürünler bölümlerine hızlı erişim
- Alt Navigasyon: Role-based menü sistemi

---

### 2. Talep Oluşturma
![Talep Oluşturma](im![talepolustur](https://github.com/user-attachments/assets/c37492aa-fea7-43ea-8930-e8d776979d03)
age-2)

**Talep Oluşturma Formu**:
- Kategori Seçimi (Dropdown)
- Ürün Seçimi
- Öncelik Belirleme (Az/Orta/Yüksek)
- Not Alanı (Detaylı açıklama girişi)
- Başarı Bildirimi (İşlem sonrası kullanıcıya uyarı)

---

### 3. Talepler Listesi
![Talepler](im![talepler-secmeaksiyonu](https://github.com/user-attachments/assets/daabc73c-7e8b-4354-8814-69d53043cf5e)
age-3)

**Talep Yönetim Ekranı**:
- Durum Filtreleri: Tümü, Bekliyor, Onaylandı, Tamamlandı, Reddedildi
- Talep Kartları: Detaylı görünüm
- Seçim Sistemi: Toplu işlemler için
- Alt Eylem Çubuğu: Onayla, Tamamla, Reddet butonları
- Dinamik Durum: Real-time status güncellemeleri

---


### 4. Ürün Yönetimi
![Ürünler](ima![urunler](https://github.com/user-attachments/assets/17f052a1-c6ff-4ffd-82d5-cb1ca61bf3d7)
ge-5)

**Ürün Yönetim Paneli**:
- Kategori Filtreleri: Tümü, İçecek, Yiyecek, Ofis Malzemeleri
- Ürün Kartları: İsim, açıklama ve kategori
- Düzenleme Seçenekleri
- Tarih Bilgileri: Eklenme/güncellenme
- Admin Kontrolleri: Ürün ekleme ve yönetimi

---

### 5. Kullanıcı Yönetimi
![Kullanıcılar](ima![kullanicilar](https://github.com/user-attachments/assets/b925487a-ee46-4072-925b-b8bdd97b2b01)
ge-6)

**Kullanıcı Yönetim Sistemi**:
- Arama Çubuğu
- Kullanıcı Kartları: İsim, email, rol, durum
- Rol Rozetleri: Yönetici/Personel
- Aktif Durumu
- Düzenleme Seçenekleri

---

### 6. Filtreleme Sistemi
![Filtreler](ima![filtreleme](https://github.com/user-attachments/assets/49943ea8-3c25-4c46-8ef7-4aae6f757d01)
ge-7)

**Gelişmiş Filtreleme**:
- Durum Filtresi
- Kullanıcı Filtresi
- Ürün Filtresi
- Akıllı Dropdown'lar
- Temizle/Ara butonları

---

### 7. Talep Düzenleme
![Düzenleme](image![duzenlecomponenti](https://github.com/user-attachments/assets/9284d77f-276c-43b1-b52d-03fbf797aeac)
-8)

**Talep Düzenleme Modal'ı**:
- Durum Güncelleme (Dropdown)
- Talep Sahibi (Readonly bilgi)
- Ürün Bilgileri
- Not Düzenleme
- Karakter Limiti (99 karakter göstergesi)

---

