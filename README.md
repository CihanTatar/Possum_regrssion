# Possum Veri Seti Üzerinde Sınıflandırma Çalışması

Bu çalışma, Kaggle üzerinde yer alan “OpenIntro Possum” veri seti kullanılarak yapılmış bir veri analizi ve sınıflandırma denemesidir. Amacım temel veri ön işleme adımlarını, model kurmayı ve farklı algoritmalar ile performans karşılaştırması yapmayı pratik etmektir.

## Veri Seti

Veri seti, Avustralya’daki possum türlerine ait biyometrik ölçümlerden oluşmaktadır. Toplam 104 gözlem ve çeşitli fiziksel özellikler bulunuyor. Hedef değişken olarak `sex` bilgisi kullanıldı ve LabelEncoder ile sayısal forma dönüştürüldü.

## Uygulanan Adımlar

- Veri yükleme ve ilk incelemeler  
- Eksik değerlerin tespiti ve temizlenmesi  
- Kategorik değişkenlerin encode edilmesi  
- Korelasyon analizleri  
- Özellik ve hedef değişken ayrımı  
- Standart ölçeklendirme  
- Train-test split  
- Logistic Regression modeli  
- GridSearchCV ve RandomizedSearchCV ile hiperparametre aramaları  
- SVC modeli ile karşılaştırma  
- Tüm modellerin accuracy, precision, recall ve f1-score değerlerinin raporlanması

## Model Sonuçları

- Logistic Regression: yaklaşık **0.67 accuracy**
- GridSearchCV en iyi skor: **0.58**
- RandomizedSearchCV en iyi skor: **0.47**
- SVC modeli: yaklaşık **0.78 accuracy**

Bu çalışma, model geliştirmekten çok veri işleme, temel ML akışını uygulama ve farklı algoritmaları deneme amacıyla yapılmıştır.

## Notebook

Tüm analiz ve kodlar `possum-regression.ipynb` dosyasında yer almaktadır.
