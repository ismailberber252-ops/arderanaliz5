# 🦚 Akademik Renkler Derneği (ARD) - CRM Yönetim Paneli

Akademik Renkler Derneği için geliştirilmiş; bulut tabanlı, şifreli ve tamamen tarayıcı üzerinde çalışan modern bir etkinlik ve katılımcı yönetim (CRM) sistemidir.

## 🚀 Özellikler

- **Bulut Senkronizasyonu:** Veriler güvenli bir NoSQL bulut havuzunda (`kvdb.io`) şifreli olarak tutulur.
- **Dinamik Veri Analizi:** Eğitim ve Fen Edebiyat gibi fakülteler bazında filtreleme, bölüm bazlı istatistik ve katılım oranları.
- **PWA Uyumluluğu:** Mobil cihazlara indirilebilir, tam ekran "Native App" hissiyatı sunar.
- **Yedekleme Sistemi:** Verileri saniyeler içinde `.json` olarak dışa aktarma veya içeri yükleme (İçe/Dışa aktarım).
- **Excel Çıktısı:** Katılımcı listelerini iletişim bilgileriyle birlikte `.csv` formatında otomatik tabloya dökme.
- **Glassmorphism Arayüz:** Tailwind CSS ile geliştirilmiş modern, şık ve karanlık/aydınlık mod destekli kurumsal tasarım.

## 🛠 Kullanılan Teknolojiler

- **HTML5 & CSS3**
- **JavaScript (ES6+)** (Framework olmadan, Vanilla JS)
- **Tailwind CSS** (CDN üzerinden)
- **KVDB** (Serverless Veritabanı)

## 🌐 GitHub Pages ile Yayına Alma (Deploy)

Bu uygulama herhangi bir arka uç (Backend) kurulumu gerektirmez. Doğrudan GitHub Pages üzerinde çalıştırabilirsiniz.

1. Projenin bulunduğu GitHub deponuza gidin.
2. Sağ üstten **Settings (Ayarlar)** sekmesine tıklayın.
3. Sol menüden **Pages** seçeneğine girin.
4. "Build and deployment" altındaki **Source** kısmını `Deploy from a branch` yapın.
5. **Branch** kısmını `main` (veya `master`) olarak seçip `/(root)` klasörünü işaretleyerek **Save** butonuna basın.
6. Birkaç dakika içinde uygulamanız `https://kullaniciadiniz.github.io/depo_adi` adresinde canlıya çıkacaktır!

## 🔐 Güvenlik Notu

İlk kurulumda kendi belirlediğiniz yönetici şifreniz cihazınızda şifrelenerek (`base64`) saklanır. Farklı bir cihaza geçtiğinizde veya veritabanı ID'nizi değiştirdiğinizde verilerinizi kaybetmemek adına düzenli olarak uygulamanın içindeki **"💾 Yedekle (JSON)"** butonunu kullanmanız tavsiye edilir.

---
*Geliştirme: Akademik Renkler Derneği Teknoloji & Yazılım Ekibi*