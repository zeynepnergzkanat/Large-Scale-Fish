# A Large Scale Fish Classification Project

## Proje Özeti
Bu proje, "A Large Scale Fish Dataset" kullanarak çeşitli balık türlerini sınıflandırmak için bir Yapay Sinir Ağı (ANN) modeli geliştirmeyi amaçlamaktadır. Model, 150x150 piksel boyutundaki görüntüleri işleyerek, balık türlerini yüksek doğrulukla tanımlamaktadır. Eğitim verileri %80 oranında, doğrulama verileri ise %20 oranında ayrılarak modelin performansı değerlendirilmiştir.

## Kullanılan Kütüphaneler
- **TensorFlow ve Keras**: Derin öğrenme modelini oluşturmak ve eğitmek için.
- **NumPy**: Sayısal işlemler için.
- **Matplotlib**: Eğitim sürecine ait grafiklerin görselleştirilmesi için.

## Model Mimarisi
- **Giriş Katmanı**: 150x150 boyutunda görüntüler.
- **Flatten Katmanı**: Görüntü verisini düzleştirir.
- **Dense Katmanı**: 128 nöron ve ReLU aktivasyonu.
- **Dropout Katmanı**: %50 dropout ile aşırı öğrenmeyi önler.
- **Çıkış Katmanı**: 9 sınıf için softmax aktivasyonu.

## Kaggle Notebook
Projenin Kaggle notebook linkine buradan ulaşabilirsiniz: [Kaggle Notebook](https://www.kaggle.com/code/zeynepnergizkanat/large-scale-fish)
