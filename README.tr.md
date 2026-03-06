---

### 2. Türkçe Versiyon (`README.tr.md` dosyası)

```markdown
<div align="right">
  <a href="README.md"><img src="https://img.shields.io/badge/English-Read-blue?style=for-the-badge&logo=googletranslate&logoColor=white" alt="English"></a>
</div>

# 📊 EDA, Özellik Mühendisliği (Feature Engineering) & Yeniden Örnekleme (Resampling) Portföyü

<div align="center">

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)]()
[![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)]()
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)]()
[![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)]()
[![Seaborn](https://img.shields.io/badge/Seaborn-3182CE?style=for-the-badge)]()

</div>

**Veri Bilimi Portföyüme** hoş geldiniz! Bu depo, veri ön işleme, **Keşifçi Veri Analizi (EDA)**, **Özellik Mühendisliği (Feature Engineering)** ve **Yeniden Örnekleme (Resampling)** tekniklerinin temel konseptleri üzerindeki çalışmalarımı sergilemektedir. Çeşitli veri seti türleriyle (sayısal, kategorik, zaman serisi vb.) çalışarak ham veriyi eyleme dönüştürülebilir içgörülere çevirmeyi ve makine öğrenmesi süreçleri için sağlam temeller oluşturmayı amaçlıyorum.

---

## 📑 İçindekiler
- [Repo Hakkında](#-repo-hakkında)
- [Teknoloji Yığını ve Araçlar](#-teknoloji-yığını-ve-araçlar)
- [Temel Modüller](#-temel-modüller)
- [Uygulamalı Projeler](#-uygulamalı-projeler)
- [Nasıl Kullanılır](#-nasıl-kullanılır)

---

## 🎯 Repo Hakkında
Bu depodaki temel amacım şunları nasıl uyguladığımı göstermektir:
- Karmaşık veri setlerini işlemek, temizlemek ve anlamak.
- İstatistiksel yöntemler ve görselleştirmeler kullanarak gizli örüntüleri ortaya çıkarmak.
- Doğru kodlama (encoding) ve özellik mühendisliği ile model performansını artırmak.
- Gelişmiş yeniden örnekleme teknikleri kullanarak dengesiz veri setleriyle başa çıkmak.

## 🛠️ Teknoloji Yığını ve Araçlar
- **Dil:** Python 🐍
- **Veri Manipülasyonu:** Pandas, NumPy
- **Veri Görselleştirme:** Matplotlib, Seaborn
- **Ortam:** Jupyter Notebook, VS Code

---

## 📚 Temel Modüller

Veri ön işlemenin teorik ve pratik temellerine derinlemesine bir bakış:

* **[Veri Bilimi Teorisi](./Data%20Science%20Teorical):** Veri biliminin teorik arka planı ve temel kavramları.
* **[Özellik Mühendisliği](./Feature%20Engineering):** Yeni özellikler oluşturma ve mevcut veriden maksimum bilgiyi çıkarma teknikleri.
* **[Kodlama (Encoding)](./Encoding):** Kategorik değişkenleri işleme stratejileri (One-Hot, Label Encoding, Target Encoding vb.).
* **[Yeniden Örnekleme (Resampling)](./Resampling%20):** Dengesiz veri setlerini işleme teknikleri (ör. SMOTE, Rastgele Alt/Üst Örnekleme).

---

## 🚀 Uygulamalı Projeler

Her projenin detaylı analizleri ve veri setlerini barındıran kendi klasörü bulunmaktadır.

### 🍷 1. [Şarap Kalitesi Analizi](./Wine%20%F0%9F%8D%B7%20Quality)
* **Veri Türü:** Sürekli ve sayısal veri.
* **Odak:** Kimyasal bileşenlerin (alkol, asidite, sülfür vb.) genel şarap kalitesi üzerindeki etkisinin araştırılması.
* **Öne Çıkan Öğrenimler:** Korelasyon analizi (Isı Haritaları), aykırı değer tespiti (Kutu Grafikleri) ve tahminleyici modelleme için çok değişkenli ilişkilerin hazırlanması.

### 🛒 2. [Süpermarket Satış Performansı](./Supermarket%20%F0%9F%9B%92%20%20Sales)
* **Veri Türü:** Zaman serisi, tarih/saat ve finansal veri.
* **Odak:** Farklı şubelerdeki müşteri davranışlarının (üye ve normal), gün/saat bazlı satış trendlerinin ve ürün gruplarının karlılığının incelenmesi.
* **Öne Çıkan Öğrenimler:** İş Zekası (BI) odaklı analiz, zaman serisi grafikleri (Çizgi Grafikleri) ve müşteri segmentasyonu.

### 🎵 3. [Spotify Parça Özellikleri](./Spotify%20%F0%9F%8E%B5%20Tracks%20)
* **Veri Türü:** Çok boyutlu, karmaşık ve eğlenceli veri.
* **Odak:** Bir şarkıyı "hit" yapan işitsel özelliklerin (enerji, dans edilebilirlik, tempo) ve bunların popülerlik skorlarıyla bağlantısının analiz edilmesi.
* **Öne Çıkan Öğrenimler:** Çok boyutlu görselleştirmeler (Renk ve boyut parametrelerine sahip Dağılım Grafikleri) ve yaratıcı veri hikayeciliği.

---

## ⚙️ Nasıl Kullanılır

1. **Repoyu bilgisayarınıza klonlayın:**
   ```bash
   git clone [https://github.com/byt23/EDA-FeatureEngineering-Resampling_Encoding.git](https://github.com/byt23/EDA-FeatureEngineering-Resampling_Encoding.git)

---

Proje içindeki Wine, Supermarket veya Spotify gibi alt klasörler için de benzer şekilde detaylı alt `README` dosyaları hazırlamamı ister misin?