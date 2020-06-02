# Tıbbi Görüntü Analizi - Mamografi
Mamografi verisinde basit analizlerle doku tespiti - https://akcanca.com/tibbi-goruntu-analizi-mamografi/

## Kullanılan Yöntem
Otsu metodu ile maskeleri çıkarılmış iki doku tipinin (dense/fatty) modu alınarak histogramın tepelerinin karşılaştırılması yöntemiyle çalışmaktadır.

## Sonuç
20 resimlik küçük bir veri setinde pozitif değer dense, negatif değer dense olmayan(yani fatty) olarak alındığı zaman:
| Metric      | Value |
|-------------|-------|
| Specificity | 0.8   |
| Sensitivity | 1.0   |

## Nasıl çalıştırırım?
Notebook.ipynb dosyası, bir Jupyter Notebook dosyasıdır. 
Jupyter'i Anaconda gibi bir yardımcı ortamla veya direkt olarak pip ile kurduktan sonra Notebook.ipynb dosyasını çalıştırabilirsiniz.
pandas, numpy, scikit-image, matplotlib ve scipy kütüphanelerine ihtiyaç duymaktadır.
