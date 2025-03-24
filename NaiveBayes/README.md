# naiveBayes
# Naive Bayes ile Ikili Siniflandirma

Bu proje, **Customer Behaviour** veri seti kullanılarak ikili sınıflandırma problemi üzerine yoğunlaşmaktadır.

## 1. Veri Seti
**Kaynak:** [Kaggle - Customer Behaviour](https://www.kaggle.com/datasets/denisadutca/customer-behaviour)

**Özellikler:**
- Veri seti müşteri davranışlarını analiz etmeye yöneliktir.
- Özellikler arasında **sürekli ve kategorik** değişkenler bulunmaktadır.

Veri seti üzerinde yapılan işlemler:
- Kategorik değişkenler sayısal hale getirilmiştir.

## 2. Kullanılan Modeller
1. **Manuel Naive Bayes Modeli**: Scikit-learn kütüphanesi kullanılmadan Python ile Naive Bayes algoritması sıfırdan kodlanmıştır.

## 3. Değerlendirme Metrikleri
Model performansı aşağıdaki metrikler ile değerlendirilmiştir:
- **Karmaşıklık Matrisi (Confusion Matrix)**
- **Doğruluk (Accuracy)**

## 4. Eğitim ve Test Süreleri Karşılaştırması
Model performanslarını karşılaştırırken, **eğitim süresi (fit)** ve **test süresi (predict)** ölçülmüştür.

## 5. Sonuç
- Model seçiminde, **veri setinin dengesi ve performans gereksinimleri** göz önünde bulundurulmalıdır.

Bu çalışma, **NumPy, Pandas, Matplotlib, Scikit-learn ve Python'un temel kütüphaneleri** kullanılarak gerçekleştirilmiştir.
