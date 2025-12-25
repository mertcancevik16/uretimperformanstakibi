# 🏭 Üretim Takip Paneli

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Atölye veya fabrika ortamları için geliştirilmiş; operatörlerin iş sürelerini, duruş sebeplerini ve mola saatlerini takip etmelerini sağlayan modern, web tabanlı bir arayüz.

## ✨ Özellikler

* **⏱ Kronometre ve İlerleme Çubuğu:** İşlem süresini anlık takip eder, görsel grafik ile (30dk/45dk/75dk) durumu gösterir.
* **📋 Duruş Kaydı:** "Bitir" dendiğinde duruş sebebini sorar ve tabloya (Başlangıç/Bitiş saati ile) kaydeder.
* **☕ Otomatik Mola Modu:** Belirlenen mola saatlerinde ekranı kilitler ve operatörü uyarır.
* **🌥 Canlı Hava Durumu:** OpenWeatherMap API entegrasyonu ile anlık sıcaklık ve hava durumu bilgisi sunar (Hata durumunda otomatik test verisine döner).
* **🎨 Modern Tasarım:** Hareketli arka plan ve "Glassmorphism" efekti ile şık görünüm.

## 🚀 Kurulum ve Kullanım

Bu proje herhangi bir kurulum veya sunucu gerektirmez. Doğrudan tarayıcı üzerinde çalışır.

1.  Repoyu klonlayın veya zip olarak indirin.
2.  `index.html` dosyasını çift tıklayarak tarayıcınızda açın.

### ⚙️ Yapılandırma

Kod içerisindeki `script` bölümünden aşağıdaki ayarları değiştirebilirsiniz:

* **Hava Durumu:** `API_KEY` değişkenine kendi [OpenWeatherMap](https://openweathermap.org/) anahtarınızı girebilirsiniz.
* **Mola Saatleri:** `molaAraliklari` dizisi içerisinden mola başlangıç ve bitiş saatlerini (Örn: `15:30 - 15:45`) güncelleyebilirsiniz.

## 🛠 Kullanılan Teknolojiler

* **HTML5 & CSS3**
* **Tailwind CSS** (CDN üzerinden)
* **Vanilla JavaScript** (ES6+)
* **OpenWeatherMap API**
