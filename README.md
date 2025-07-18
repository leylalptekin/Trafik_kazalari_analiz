<img width="1080" height="1350" alt="Image" src="https://github.com/user-attachments/assets/4a467fb9-a623-433f-bb42-255a2cebf1e0" />

# 🚗 UK Traffic Flow Analysis (2000–2016)

Bu proje, İngiltere, İskoçya ve Galler'deki 2000–2016 yılları arasındaki trafik akışı verilerinin analizini içermektedir. Veri seti [Kaggle](https://www.kaggle.com/datasets/daveianhickey/2000-16-traffic-flow-england-scotland-wales) üzerinden temin edilmiştir.

Amaç; zamana, konuma ve taşıt türüne göre trafik yoğunluğunu inceleyerek karayolu kullanımındaki değişimleri analiz etmektir.

---

## 📦 Veri Kümesi

- **Kaynak:** [Kaggle - UK Traffic Flow Dataset](https://www.kaggle.com/datasets/daveianhickey/2000-16-traffic-flow-england-scotland-wales)
- **Kapsam:** 2000–2016 yılları arası
- **Bölgeler:** İngiltere, İskoçya ve Galler
- **Değişkenler:**
  - Yıl
  - Bölge adı
  - Yol tipi (A-road, Motorway, vb.)
  - Taşıt tipi (bisiklet, motosiklet, araba, otobüs, HGV vb.)
  - Trafik hacmi (yıllık toplam sayımlar)

---

## 🧰 Kullanılan Kütüphaneler

- `pandas` – veri işleme
- `matplotlib`, `seaborn`, `plotly` – veri görselleştirme
- `numpy` – sayısal işlemler
- `datetime` – zaman verisi işlemleri
- `statsmodels` veya `prophet` – zaman serisi analizleri için

---

## 📊 Yapılan Analizler

- 📈 **Yıllara göre toplam trafik hacmi değişimi**
- 🚗 **Taşıt türlerine göre trafik akışı karşılaştırması**
- 🛣️ **Yol türlerine göre yoğunluk analizi (Motorway vs. A-Road)**
- 🗺️ **Bölgesel trafik karşılaştırmaları (İngiltere, İskoçya, Galler)**
- 🕒 **Zaman içindeki eğilimler (trend analizi)**
  

---


---

## ✅ Elde Edilen Bulgular

- **2008 ekonomik krizi** sonrasında trafik hacminde düşüş gözlemlenmiştir.
- **Motorlu taşıt kullanımı** genel olarak yıllar içinde artış göstermektedir, özellikle özel araçlar.
- **Bisiklet ve motosiklet** gibi taşıt türlerinde yıl bazlı dalgalanmalar dikkat çekicidir.
- **Motorway'lerde** trafik hacmi genellikle **A-Road'lara göre daha yüksektir**, ancak bazı bölgelerde istisnalar mevcuttur.
- **İngiltere**, açık ara en yoğun trafiğe sahip ülkedir, onu Galler ve İskoçya izler.

---

📝 Sonuçlar
Bu proje, 2000–2016 yılları arasında Birleşik Krallık'taki trafik eğilimlerini anlamaya yönelik kapsamlı bir bakış sunmaktadır. Farklı taşıt türlerinin ve yol tiplerinin yıllara göre nasıl değiştiği görselleştirilerek, şehir planlaması, ulaşım politikaları ve çevresel etkiler gibi konularda kullanılabilecek değerli içgörüler elde edilmiştir.

Zaman serisi analizleriyle birlikte trafik hacmindeki dönemsel dalgalanmalar ve uzun vadeli eğilimler belirlenmiş, potansiyel gelecek tahminleri için temel oluşturulmuştur.

