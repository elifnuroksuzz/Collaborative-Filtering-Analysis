# Collaborative Filtering: User-Based vs. Item-Based Analysis

Bu proje, öneri sistemlerinde kullanılan **İşbirlikçi Filtreleme (Collaborative Filtering)** yöntemlerinin detaylı bir karşılaştırmasını sunar. Hazır kütüphaneler (Surprise vb.) kullanılmadan, algoritmalar temel seviyede Python ile geliştirilmiştir.

## 📌 Proje Özeti
Proje kapsamında aşağıdaki iki temel yaklaşım karşılaştırılmaktadır:
1.  **User-Based Collaborative Filtering:** Kullanıcı benzerlikleri üzerinden tahminleme.
2.  **Item-Based Collaborative Filtering:** Ürün benzerlikleri ve Adjusted Cosine Similarity (ACS) kullanımı.

Analizler; hata metrikleri (MAE), çalışma süreleri ve veri setindeki seyreklik (sparsity) etkileri üzerinden yürütülmüştür.

## 🚀 Öne Çıkan Özellikler
- **Sıfırdan Uygulama:** Algoritmalar matematiksel temelleriyle kodlanmıştır.
- **Parametre Optimizasyonu:** Farklı `k` (komşuluk) değerlerinin (10, 25, 50, 100) model performansı üzerindeki etkisi incelenmiştir.
- **Sparsity Analizi:** Veri seti %20 oranında seyreltilerek modellerin dayanıklılığı ölçülmüştür.
- **Performans Metrikleri:** Global MAE ve işlem süresi karşılaştırmalı olarak tablolanmıştır.

## 🛠️ Kullanılan Teknolojiler
- **Dil:** Python 3.10+
- **Veri İşleme:** NumPy, Pandas
- **Görselleştirme:** Matplotlib
- **Ortam:** Google Colab / T4 GPU

## 📊 Öne Çıkan Bulgular
- **User-Based** yöntemi, düşük seyreklik durumlarında daha yüksek doğruluk (düşük MAE) sergilemektedir.
- **Item-Based (ACS)** yöntemi, veri setindeki seyreklik artışına karşı daha stabil bir performans göstermiştir.
- Komşu sayısı (`k`) arttıkça modellerin hata oranları ve işlem süreleri arasındaki denge analiz edilmiştir.

## ⚙️ Kurulum ve Çalıştırma
Projeyi yerelinizde çalıştırmak için:

1. Depoyu klonlayın:
   ```bash
   https://github.com/elifnuroksuzz/Collaborative-Filtering-Analysis.git
