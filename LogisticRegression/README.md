# Logistic Regression - İkili Sınıflandırma

## Problem Tanımı
Bu projede, Logistic Regression kullanarak ikili sınıflandırma problemi çözmeyi amaçladım. İkili sınıflandırma, bir veri setindeki örneklerin iki sınıftan birine ait olup olmadığını tahmin etmek için kullanılan bir yöntem. Ben de Scikit-learn kütüphanesini kullanarak hızlı bir model oluşturduğum gibi, aynı zamanda sıfırdan bir logistic regression modeli yazıp gradient descent ile eğitim yaptım.

## Kullanılan Yöntemler

### 1. **Scikit-learn Logistic Regression**
   - Scikit-learn kütüphanesindeki `LogisticRegression` sınıfını kullanarak bir model eğittim. Bu yöntem hızlı ve kullanışlı olduğu için eğitim süresi çok kısa oldu.
   - Model, eğitim verisi ile eğitildikten sonra test verisi üzerinde doğruluk oranını ölçtüm.

### 2. **Manuel Logistic Regression (Gradient Descent)**
   - Scikit-learn kullanmadan, sıfırdan bir logistic regression modeli yazdım. Bu modelde maksimum likelihood estimation (MLE) tabanlı cost function ve gradient descent algoritması kullanarak model eğittim.
   - Bu sayede, modelin iç işleyişine daha fazla hakim oldum ve algoritmanın her adımını daha derinlemesine inceledim.

## Model Performansı

### Karmaşıklık Matrisi
Her iki modelin doğruluğunu karmaşıklık matrisi (confusion matrix) kullanarak değerlendirdim. Bu matris, modelin doğru ve yanlış tahminlerini görsel olarak gösteriyor.

### Zaman Testi
Eğitim ve test sürelerini, Python’un `time` modülünü kullanarak ölçtüm. Böylece, Scikit-learn ile manuel modelin ne kadar farklı sürelerde çalıştığını gözlemleyebildim.

## Sonuçlar

- **Scikit-learn Modeli:** Eğitim süresi oldukça hızlı oldu ve doğru sonuçlar verdi. Çünkü Scikit-learn her şeyin hazır fonksiyonlarını sağlıyor.
- **Manuel Model:** Eğitim süresi biraz daha uzun sürdü çünkü her adımı kendim yazdım ve gradient descent gibi optimizasyon tekniklerini manuel olarak uyguladım. Ama bu yöntem, modelin nasıl çalıştığını çok daha iyi anlamamı sağladı.
