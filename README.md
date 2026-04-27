# 🗺️ Türkiye Gezi Haritam (Interactive Travel Map)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Kullanıcıların Türkiye üzerinde ziyaret ettikleri şehirleri interaktif olarak işaretleyebildikleri, ilerlemelerini istatistiksel olarak takip edebildikleri modern ve dinamik bir web uygulamasıdır.

## ✨ Öne Çıkan Özellikler

* **📍 İnteraktif SVG Harita:** Türkiye haritası tamamen vektörel (SVG) formatta hazırlanmış olup, her bir il üzerine gelindiğinde (hover) tooltipler ile isim gösterir ve tıklama ile "gezildi" olarak işaretlenir.
* **💾 Tarayıcı Hafızası (Local Storage):** İşaretlenen şehirler tarayıcının yerel hafızasına kaydedilir. Sayfa yenilendiğinde veya daha sonra tekrar girildiğinde veriler kaybolmaz.
* **📊 Canlı İstatistik ve İlerleme:** Gezilen il sayısı, kalan il sayısı ve Türkiye'nin yüzde kaçının gezildiği anlık olarak hesaplanır. Göz alıcı animasyonlara sahip bir ilerleme çubuğu (progress bar) ile desteklenir.
* **🌗 Gelişmiş Tema Motoru (Dark/Light Mode):** Basit bir renk değişiminin ötesinde; özel tasarlanmış yerçekimi (gravity fall) animasyonu ve ekranı kaplayan dairesel dalga (ripple) efekti ile pürüzsüz bir tema geçişi sunar.
* **🕸️ Dinamik Arkaplan (Plexus Effect):** HTML5 `<canvas>` kullanılarak, fare hareketlerine duyarlı ve parçacıkların birbirine bağlandığı "Plexus" ağ efekti kodlanmıştır. Tema rengine göre parçacık renkleri de otomatik güncellenir.

## 🛠️ Kullanılan Teknolojiler

Bu proje herhangi bir harici framework veya kütüphane kullanılmadan, saf (vanilla) web teknolojileri ile geliştirilmiştir:

* **Frontend:** HTML5, CSS3 (Modern Flexbox, Custom Properties/Değişkenler, Keyframe Animasyonları)
* **Grafik & Arkaplan:** Vektörel SVG Manipülasyonu, HTML5 Canvas API (Object-Oriented JavaScript ile parçacık fiziği)
* **Mantık & Etkileşim:** Vanilla JavaScript (ES6+), DOM Manipülasyonu, LocalStorage API
* **İkonlar ve Tipografi:** FontAwesome (Tema butonu için), Google Fonts (Playfair Display, Nunito)

## 📂 Dosya Yapısı

Proje kolay taşınabilirlik açısından tek bir dosya içerisine modüler bir şekilde inşa edilmiştir:

```text
├── index.html        # HTML yapısı, CSS stilleri (animasyonlar dahil) ve Canvas/SVG JS mantığı
└── README.md         # Proje dokümantasyonu
