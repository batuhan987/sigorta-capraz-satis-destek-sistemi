# 🛡️ Sigorta Çapraz Satış Destek Sistemi (İnsurtech KDS)

> **"Doğru müşteriye, doğru zamanda, doğru poliçeyi sunun."**

Bu proje, sigorta acentelerinin satış potansiyelini maksimize etmek için geliştirilmiş, **istemci tabanlı (client-side)** çalışan akıllı bir **Karar Destek Sistemidir (KDS)**. Müşterinin mesleği, varlıkları ve demografik bilgilerini analiz ederek, nokta atışı ürün önerileri sunar.

---

## 🚀 Özellikler

### 🧠 1. Akıllı Kural Motoru (Rule-Based Engine)
* **170+ Meslek & 200+ Varlık:** Sistemin veritabanında tanımlı yüzlerce veri noktası.
* **Etiket Eşleştirme:** Örneğin; *"Yazılımcı"* seçildiğinde sistem arka planda `OFIS`, `ELEKTRONIK`, `SEDANTER` etiketlerini analiz eder ve buna uygun riskleri belirler.
* **Demografik Zeka:** Yaş ve cinsiyet verisine göre otomatik risk puanlaması (Örn: 60+ yaş için Sağlık Sigortası önceliği).

### 🎯 2. Gap (Boşluk) Analizi
* Müşterinin hali hazırda sahip olduğu poliçeleri (Örn: Kasko) analizden çıkarır.
* Sadece müşterinin **ihtiyacı olan ve eksik kalan** ürünleri (Örn: Tamamlayıcı Sağlık) önerir.

### 🔒 3. Güvenli Lisanslama Sistemi
* **SHA-256 Şifreleme:** Lisans anahtarları sunucu gerektirmeden, tarayıcı üzerinde güvenli hashleme yöntemiyle doğrulanır.
* **Demo Modu:** Kullanıcılar için 30 analizlik deneme sürümü mevcuttur. Sayaç dolduğunda sistem kilitlenir.

### 💼 4. Satış Otomasyonu
* **PDF Teklif Oluşturma:** Seçilen ürünleri profesyonel, müşteri dostu (arka plan verilerini gizleyen) bir PDF formatına dönüştürür.
* **E-Posta Entegrasyonu:** Tek tıkla müşteriye özel hazırlanmış e-posta taslağı oluşturur.

## 🛠️ Kurulum ve Kullanım

Bu proje tamamen **Statik Web Teknolojileri** ile geliştirilmiştir. Herhangi bir sunucu kurulumu (Node.js, PHP, Python vb.) gerektirmez.

1.  Projeyi bilgisayarınıza indirin veya `git clone` yapın.
2.  `index.html` dosyasını tarayıcınızda açın.
3.  **Lisans Girişi:**
    * Elinizde PRO anahtar varsa girin.
    * Yoksa **"Demo Sürümü Dene"** butonuna tıklayın.
4.  **Veritabanı Yükleme:** Açılan ekranda `sigorta_db.xlsx` dosyasını sisteme yükleyin.
5.  Analize başlayın!

---

## 📂 Dosya Yapısı

* `index.html`: Güvenlik ve giriş kapısı (Login Gate).
* `dashboard.html`: Ana analiz ekranı ve yönetim paneli.
* `sigorta_db.xlsx`: Sistemin beyni. Meslek, Varlık ve Ürün kurallarının bulunduğu veritabanı.

---

## 👨‍💻 Geliştirici

**Batuhan Bayatlı**
*Senior Insurtech Developer*

Proje hakkında geri bildirim veya lisans talepleri için:
* [LinkedIn Profilim](https://www.linkedin.com/in/batuhanbayatlı/)
* 📧 E-Posta: bayatlibatuhan@gmail.com](mailto:bayatlibatuhan@gmail.com)

---

> *Bu proje GitHub Pages üzerinde canlı demo olarak çalışabilir.*
