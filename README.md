# Online Retail Veri Seti Analizi — Dönem Projesi

## Proje Ekibi
- Ayşe Esra Arslan — Öğrenci No: 1306240093

## Proje Açıklaması
Bu proje, UCI "Online Retail" veri seti üzerinde veri temizleme, keşifsel
veri analizi (EDA) ve RFM analizi + K-Means kümeleme yöntemiyle müşteri
segmentasyonu gerçekleştirmektedir. 3 araştırma sorusu tanımlanmış ve
analizle yanıtlanmıştır.

## Veri Kaynağı
- **İsim:** Online Retail
- **Kaynak:** UCI Machine Learning Repository
- **Link:** https://archive.ics.uci.edu/dataset/352/online+retail
- **Atıf:** Chen, D. (2015). Online Retail [Dataset]. UCI Machine Learning
  Repository. https://doi.org/10.24432/C5BW33
- **Lisans:** CC BY 4.0 (Creative Commons Attribution 4.0 International)

## Kullanılan Kütüphaneler
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (StandardScaler, KMeans)
- openpyxl (.xlsx dosyasını okumak için)

## Klasör Yapısı
veri-bilimi-donem-projesi/

├── online_retail_analizi.ipynb   # Ana notebook

├── data/

│   └── online_retail.xlsx        # Ham veri seti

├── report/

│   └── rapor.pdf                 # Kısa rapor

├── prompt-gunlugu.txt             # Prompt günlüğü

└── README.md

## Projeyi Çalıştırma Talimatları
1. Bu repository'yi klonlayın veya ZIP olarak indirip açın.
2. Gerekli kütüphaneleri kurun:
   pip install pandas numpy matplotlib seaborn scikit-learn openpyxl notebook
3. Terminalde proje klasörüne girin ve Jupyter Notebook'u başlatın:
cd veri-bilimi-donem-projesi
jupyter notebook
4. Açılan tarayıcıda `online_retail_analizi.ipynb` dosyasına tıklayın.
5. Üst menüden **Kernel → Restart Kernel and Run All Cells** ile çalıştırın.

## Proje Kapsamı
- Veri temizleme: eksik değer, iptal kayıtları, aykırı değer (percentile
  capping), tip dönüşümü
- EDA: temel istatistikler + 5 farklı görselleştirme (bar chart ×2, line
  chart, histogram, boxplot)
- 3 araştırma sorusu (ülke/ürün geliri, aylık trend, müşteri segmentasyonu)
- Modelleme: RFM analizi + K-Means kümeleme (k=4, Elbow yöntemiyle belirlendi)

