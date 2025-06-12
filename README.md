# Fetal Health Classification

Bu proje, fetal_health.csv veri seti kullanılarak anne karnındaki fetüslerin sağlık durumunu sınıflandırmayı amaçlamaktadır. Model, çeşitli makine öğrenmesi algoritmaları ile eğitilerek "Normal", "Şüpheli" ve "Patolojik" kategorileri tahmin etmektedir.

## İçerik
- `fetal_health.csv`: Veri seti
- `fetal_health_classification.ipynb`: Modelleme ve analiz
- `fetal_health_report_final.pdf`: Proje raporu
- `figures/`: Grafik ve görseller

## Özellikler
- Verinin ön işlenmesi ve görselleştirilmesi
- Farklı algoritmalarla model karşılaştırması (Random Forest, Logistic Regression, SVM vs.)
- Model başarım metrikleriyle detaylı değerlendirme (Accuracy, F1-score)
- Eğitilmiş modelin .pkl dosyası olarak kaydedilmesi


## Kullanılan Kütüphaneler
- pandas
- numpy
- matplotlib
- scikit-learn

## Nasıl Çalıştırılır?
Gerekli kütüphaneleri yükleyin:


```bash
pip install -r requirements.txt
Jupyter Notebook'u açın ve çalıştırın:

```

```bash
jupyter notebook fetal_health_classification.ipynb

```

## Sonuç
Random Forest modeli %91 doğruluk oranı ile en başarılı model olarak seçilmiştir.

