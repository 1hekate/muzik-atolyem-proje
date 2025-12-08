# 🎵 Müzik Atölyem - Web Tasarımı Projesi

Bu proje, **Kocaeli Üniversitesi Bilişim Sistemleri Mühendisliği** Bölümü Web Tasarımı dersi kapsamında geliştirilmiş, modern ve responsive (mobil uyumlu) bir müzik platformu web sitesidir.

Canlı Önizleme: **(https://muzikatolyem.netlify.app)**

## 🚀 Proje Hakkında
"Müzik Atölyem", kurgusal bir müzik yapım ve organizasyon şirketidir. Bu web sitesi, şirketin sanatçılarını tanıttığı, albüm satışlarını listelediği, etkinlik duyurularını yaptığı ve kurumsal kimliğini yansıtığı bir arayüz olarak tasarlanmıştır.

Kullanıcı deneyimi (UX) ön planda tutularak **"Mobile First"** yaklaşımıyla geliştirilmiştir.

## ✨ Öne Çıkan Özellikler
* **Responsive Tasarım:** Bootstrap 4 Grid sistemi ile tüm cihazlarda (Mobil, Tablet, Masaüstü) kusursuz görünüm.
* **Dinamik Slider:** Owl Carousel kütüphanesi ile hazırlanan tam ekran manşet alanı.
* **Yönetim Paneli (Admin Dashboard):** `Chart.js` kullanılarak ziyaretçi istatistiklerini ve içerik dağılımını gösteren grafikler (Simülasyon).
* **Etkileşimli Bileşenler:**
    * Albüm detay sayfalarında ses oynatıcı (Audio Player).
    * Haberler için sayfa yenilenmeden açılan **Modal (Popup)** pencereler.
    * İletişim sayfasında **Sıkça Sorulan Sorular (Accordion)** yapısı.
* **Harita Entegrasyonu:** Google Maps API (Embed) ile konum gösterimi.
* **Gelişmiş Navigasyon:** "Kurumsal" ve "Albümler" altında açılır menü (Dropdown) ve sabit üst menü (Sticky Navbar).

## 🛠️ Kullanılan Teknolojiler
Bu proje, endüstri standardı web teknolojileri kullanılarak geliştirilmiştir:

* **HTML5** (Semantik Yapı)
* **CSS3** (Flexbox, Transitions, Custom Styling)
* **JavaScript & jQuery** (DOM Manipülasyonu)
* **Bootstrap 4.6** (CSS Framework)
* **Chart.js** (Veri Görselleştirme)
* **Owl Carousel 2** (Slider Eklentisi)
* **FontAwesome** (İkon Seti)

## 📂 Kurulum ve Çalıştırma
Projeyi yerel bilgisayarınızda çalıştırmak için:

1.  Bu depoyu (repository) klonlayın:
    ```bash
    git clone [https://github.com/1hekate/muzik-atolyem-proje.git](https://github.com/1hekate/muzik-atolyem-proje.git)
    ```
2.  Klasörün içine girin ve `index.html` dosyasını tarayıcınızda açın.

## 📄 Sayfa Yapısı
* `index.html`: Ana Sayfa (Slider, Öne Çıkanlar, Duyurular)
* `albums-store.html`: Albüm Listesi ve Filtreleme
* `album-*.html`: Sanatçı ve Albüm Detay Sayfaları (Örn: Sagopa, Motive, Şebnem Ferah)
* `event.html`: Etkinlik Takvimi
* `blog.html`: Haberler ve Blog Yazıları
* `kurumsal.html`: Hakkımızda, Misyon & Vizyon, Birimler
* `contact.html`: İletişim Formu, Harita ve SSS
* `admin.html`: Yönetici Paneli ve Grafikler
* `login.html`: Üye Giriş Ekranı

## 👤 Yazar
**Eren Dağlı** *Kocaeli Üniversitesi - Teknoloji Fakültesi* *Bilişim Sistemleri Mühendisliği*

---
*Bu proje eğitim amacıyla geliştirilmiştir.*
