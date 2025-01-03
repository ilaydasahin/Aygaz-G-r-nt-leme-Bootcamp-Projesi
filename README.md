# Aygaz Görüntü İşleme Bootcamp Projesi

## Proje Özeti

Bu proje, CNN (Convolutional Neural Networks) modellerinin temellerini pekiştirmeyi amaçlamaktadır. Proje kapsamında, bir CNN modeli tasarlanarak çeşitli hayvan türlerini sınıflandırma yapılacaktır. Örneğin, "panda" ve "köpek" gibi iki sınıfı CNN ile ayırt etmek hedeflenmektedir. Modelin derinliği ve başarı oranı hakkında farkındalık kazanılacak ve çeşitli manipülasyon teknikleri ile modelin başarısı test edilecektir.

## Veri Seti

Bu projede, Kaggle üzerindeki "Animals with Attributes 2" veri seti kullanılmaktadır. Veri seti, 50 farklı hayvan sınıfından oluşmaktadır ve her sınıfta farklı sayıda görüntü bulunmaktadır. Projede kullanılacak sınıflar şunlardır:

- Collie
- Dolphin
- Elephant
- Fox
- Moose
- Rabbit
- Sheep
- Squirrel
- Giant Panda
- Polar Bear

Her bir sınıftan yalnızca 650 resim kullanılacaktır. Bu sınıflar, denge sağlanarak seçilmiştir.

## Proje Adımları

1. **Veri Setinin Hazırlanması**: 
    - Veri setinden 10 sınıf seçilmiş ve her sınıftan 650 resim alınmıştır.
    - Resimler 128x128 boyutuna getirilmiş ve normalize edilmiştir.

2. **CNN Modelinin Tasarımı**:
    - 10 hayvan sınıfını ayırt edebilecek bir CNN modeli tasarlanmıştır.
    - Model, çeşitli konvolüsyonel katmanlar, aktivasyon fonksiyonları, havuzlama ve tam bağlı katmanlar içermektedir.
    - Kayıp fonksiyonu olarak `categorical_crossentropy` seçilmiştir.

3. **Modelin Test Edilmesi**:
    - Model, eğitim verisiyle eğitildikten sonra test verisiyle değerlendirilmiştir.

4. **Resim Manipülasyonu**:
    - Test resimleri farklı ışık koşulları altında manipüle edilmiştir ve modelle test edilmiştir.
    - Görüntülere renk sabitliği algoritması uygulanmıştır ve sonuçlar karşılaştırılmıştır.


## Kütüphaneler ve Araçlar

- `TensorFlow` ve `Keras` (Model oluşturma ve eğitim)
- `OpenCV` (Resim işleme ve manipülasyon)
- `scikit-learn` (Veri seti bölme ve etiketleme)
- `Matplotlib` (Sonuçların görselleştirilmesi)

## Kullanım

Proje, Colab veya Kaggle notebook ortamlarında çalışacak şekilde tasarlanmıştır. Projeyi çalıştırmak için aşağıdaki adımları izleyebilirsiniz:


. Veri setini https://www.kaggle.com/code/klaydaahin/aygaz-bootcamp-goruntu-isleme üzerinden indirip uygun bir klasöre yerleştirin.
- Notebook üzerinde adımları takip ederek projeyi çalıştırın.


***********************
https://www.kaggle.com/code/klaydaahin/aygaz-bootcamp-goruntu-isleme
