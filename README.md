# 🌿 Ogani - Organik Gıda Satış ve Yönetim Sistemi

![Project Status](https://img.shields.io/badge/Durum-Tamamland%C4%B1-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

Bu proje, **Kocaeli Üniversitesi Bilişim Sistemleri Mühendisliği** Web Tasarımı (TBL303) dersi kapsamında geliştirilmiştir. Hazır bir Bootstrap şablonu (Ogani) temel alınarak, sektör gereksinimlerine göre özelleştirilmiş, responsive (duyarlı) ve modern bir e-ticaret arayüzü oluşturulmuştur.

🔗 **Canlı Önizleme:** [https://taha907.github.io/OrganicMarket/](https://taha907.github.io/OrganicMarket/)

---

## 📖 Hakkında

Proje, kullanıcıların organik sebze, meyve ve şarküteri ürünlerine ulaşabileceği, ürünlerin besin değerlerini karşılaştırabileceği ve yönetim paneli simülasyonu ile site içeriğinin nasıl yönetilebileceğinin modellendiği kapsamlı bir Frontend çalışmasıdır. 

**Önemli Not:** Projede Backend kullanılmamış olup, tüm veritabanı işlemleri (ürün ekleme, güncelleme vb.) ve yönetim paneli fonksiyonları JavaScript ile **Front-end tarafında simüle edilmiştir**.

### 🎯 Kurumsal Kimlik

**Misyonumuz**
> Modern tarımın getirdiği kimyasal yükten arınmış, doğal, taze ve güvenilir gıdaları doğrudan üreticisinden alarak sofralarınıza ulaştırmaktır. Amacımız; kahvaltılıktan et ürünlerine, sebzeden meyveye kadar tüm ürün yelpazemizde, şeffaflığı ve kaliteyi esas alarak, sağlıklı beslenme hakkını her aileye sağlamaktır.

**Vizyonumuz**
> Türkiye'de organik ve güvenilir gıda denildiğinde akla gelen ilk, en şeffaf ve en güvenilir online pazar yeri olmaktır. Gelecekte, sürdürülebilir tarım uygulamalarını destekleyerek, hem üreticiyi hem de doğayı koruyan bir ticaret ağı kurmak ve sağlıklı gıda hareketinin öncüsü olmaktır.

---

## ✨ Özellikler

Proje, standart bir e-ticaret temasının ötesine geçerek şu özellikleri barındırır:

* **Responsive Tasarım:** Mobil, tablet ve masaüstü cihazlarla %100 uyumlu optimize edilmiş grid yapısı.
* **Ürün Kategorileri:** Sebzeler, Meyveler ve Şarküteri ürünleri için özel listeleme sayfaları ve detay görünümleri.
* **Besin Değeri Karşılaştırma Modülü:** Kullanıcıların seçtiği iki farklı ürünün kalori, protein ve diğer besin değerlerini grafiksel olarak (Chart.js vb.) karşılaştırmasını sağlayan dinamik analiz aracı.
* **Admin Paneli Simülasyonu:** Ürün ekleme, slider güncelleme, duyuru yayınlama ve istatistik girişi gibi işlemlerin arayüz tasarımını ve mantığını içeren yönetim paneli.
* **Duyuru Sistemi:** Modal yapısı ile çalışan, kullanıcılara kampanya ve duyuruları listeleyen özel alan.
* **İletişim & Lokasyon:** Firma konumunu gösteren Google Maps entegrasyonu ve geliştirilmiş şikayet/öneri formu tasarımı.

---

## 🛠️ Kullanılan Teknolojiler

* **HTML5 & CSS3:** Semantik yapı, sayfa düzeni ve stil özelleştirmeleri.
* **JavaScript:** DOM manipülasyonu, slider kontrolü, grafik çizimleri ve admin paneli simülasyonu.
* **Bootstrap:** Grid sistemi ve responsive bileşenler (Ogani Template tabanlı).
* **Chart Libraries:** Veri görselleştirme ve besin değeri grafikleri için kullanılmıştır.

---

## 🚀 Kurulum ve Kullanım

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1.  **Repoyu Klonlayın:**
    ```bash
    git clone [https://github.com/taha907/OrganicMarket.git](https://github.com/taha907/OrganicMarket.git)
    ```
2.  **Klasöre Gidin:**
    ```bash
    cd OrganicMarket
    ```
3.  **Çalıştırın:**
    `index.html` dosyasını tarayıcınızda açmanız yeterlidir. Proje sadece Front-end dosyalarından oluştuğu için sunucu kurulumu gerektirmez.

### Admin Paneli Hakkında
Yönetim paneli (`admin` klasörü veya ilgili bağlantı), içerik yönetiminin nasıl yapılacağını göstermek amacıyla tasarlanmıştır. Veritabanı bağlantısı olmadığı için yaptığınız değişiklikler (yeni ürün ekleme vb.) kalıcı olmaz, ancak sistemin işleyiş mantığını deneyimleyebilirsiniz.

---

## 👤 Geliştirici
* Bilişim Sistemleri Mühendisliği, Kocaeli Üniversitesi
* GitHub: [@taha907](https://github.com/taha907)

## 📂 Dosya Yapısı ve Açıklamalar

Proje klasörleri ve dosyaların işlevleri aşağıda detaylandırılmıştır:

```text
OrganicMarket/
├── Source/              # Şablonun orijinal kaynak dosyaları
├── admin/               # Yönetim Paneli Simülasyonu (Ürün/Duyuru ekleme arayüzleri)
├── css/                 # Bootstrap ve özel stil (style.css) dosyaları
├── fonts/               # İkon setleri ve web fontları
├── img/                 # Ürün görselleri, bannerlar ve site logoları
├── js/                  # Slider, Chart.js grafikleri ve etkileşim scriptleri
├── sass/                # SCSS stil derleme dosyaları
│
├── index.html           # 🏠 Ana Sayfa (Slider, öne çıkan ürünler)
├── shop-grid.html       # 🥦 Ürün Listeleme (Sebze, meyve, şarküteri kategorileri)
├── shop-details.html    # 📊 Ürün Detay (Besin değeri karşılaştırma grafiği burada bulunur)
├── campaigns.html       # 📢 Duyurular ve Kampanyalar (Modal ile detay gösterimi)
├── about.html           # ℹ️ Kurumsal (Misyon, Vizyon ve Hakkımızda)
├── contact.html         # 📍 İletişim (Google Maps ve şikayet formu)
├── shopping-cart.html   # 🛒 Sepet Sayfası (Front-end tasarımı)
├── checkout.html        # 💳 Ödeme Adımları (Arayüz tasarımı)
└── login-page.html      # 🔐 Giriş Sayfası (Admin paneli veya üye girişi simülasyonu)
