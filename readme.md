# Duygu Analizi 

Bu proje, büyük veri analitiği kullanarak mizah içeren metinlerin tespit edilmesini amaçlamaktadır. Proje kapsamında kullanılan veri seti üzerinde çeşitli veri madenciliği algoritmaları uygulanarak metinlerin mizah içerip içermediği belirlenmiştir.

## İçindekiler
- [Büyük Veri ve İstatistik](#büyük-veri-ve-İstatistik)
   - [Veri Bilimi ve İstatistik Alanlarının Karşılaştırılması](#Veri-Bilimi-ve-İstatistik-Alanlarının-Karşılaştırılması)
- [Veri Kümesi](#veri-kümesi)
- [Knime Uygulaması](#knime-uygulaması)
- [Sonuç ve Tartışma](#sonuç-ve-tartışma)
- [Kaynaklar](#kaynaklar)

## Proje Hakkında
Bu proje, Kaggle üzerinden temin edilen bir [veri seti](https://www.kaggle.com/datasets/deepcontractor/200k-short-texts-for-humor-detection/data) kullanılarak gerçekleştirilmiştir. Proje kapsamında, veri setine çeşitli ön işleme adımları uygulanmış, ardından veri madenciliği algoritmaları kullanılarak metinlerin mizah içerip içermediği tahmin edilmiştir. Proje raporu, veri seti ve KNIME iş akışı dosyaları bu repository'de yer almaktadır.

## Veri Madenciliği ve Kullanılan Algoritmalar
Veri madenciliği, büyük veri setlerinden anlamlı bilgiler çıkarmak için kullanılan yöntemler bütünüdür. Bu projede, metinlerin mizah içerip içermediğini tespit etmek amacıyla çeşitli makine öğrenimi algoritmaları kullanılmıştır. Kullanılan algoritmalar şunlardır:
- K-NN (K-En Yakın Komşu)
- Naive Bayes
- Karar Ağaçları
- XGBoost
- Lojistik Regresyon

## Modelleme ve Değerlendirme
Proje kapsamında, veri setine çeşitli ön işleme adımları uygulanmış, ardından veri madenciliği algoritmaları kullanılarak modeller oluşturulmuş ve bu modellerin başarı oranları değerlendirilmiştir. Değerlendirme aşamasında doğruluk, hassasiyet ve F1 skoru gibi metrikler kullanılmıştır.


