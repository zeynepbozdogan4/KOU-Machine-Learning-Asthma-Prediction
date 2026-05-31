# KOU-Machine-Learning-Asthma-Prediction
Kocaeli Üniversitesi Makine Öğrenmesinin İlkeleri Dersi Dönem Sonu Projesi.
## Proje Sahibi
* **Ad Soyad:** [Zeynep Bozdoğan]
* **Öğrenci Numarası:** [256040006]

## Projenin Amacı
CDC BRFSS 2024 veri seti kullanılarak, bireylerin sosyo-demografik ve klinik özellikleri üzerinden astım hastalığı yakalanma risklerini makine öğrenmesi algoritmalarıyla tahmin etmek.

## Kullanılan Teknolojiler ve Yöntemler
* **Dil:** Python (Jupyter Notebook)
* **Kütüphaneler:** `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`
* **Veri Ön İşleme:** KNN Imputer (Eksik Veri Tamamlama), StandardScaler
* **Modeller:** Lojistik Regresyon, Karar Ağaçları, Rastgele Orman (Random Forest), Yapay Sinir Ağları (ANN)

##  Öne Çıkan Bulgular
Projede kılavuz kriterlerine uygun olarak seçilen 15 özgül değişken analiz edilmiş olup, en yüksek F1-Skoruna (**0.82**) ve doğruluğa (**%86**) **Rastgele Orman** algoritması ile ulaşılmıştır.

## Depo İçeriği
* `bfss_dataset_2024kod.zip`: Projenin tüm veri ön işleme, modelleme ve grafik çıktılarını içeren asıl kod dosyası.
* `Proje_raporu.docx`: Projenin akademik yazım kurallarına uygun hazırlanan final raporu.
