### Türkçe Sosyal Medya Üzerinden Siber Zorbalık Tespiti

Bu projede, Türkçe sosyal medya paylaşımlarını kullanarak siber zorbalık tespiti üzerine veri analizi ve makine öğrenmesi teknikleri uygulanmıştır. Proje, [Kaggle'dan alınan](https://www.kaggle.com/datasets) bir veri seti ile gerçekleştirilmiştir.

## 📊 Kullanılan Veri Seti

- **Veri Kaynağı:** Türkçe Sosyal Medya Paylaşım Veri Seti
- **Boyut:** 11.119 satır, 2 sütun (`Tip`, `Paylaşım`)
- `Tip` sütunu: Paylaşımın olumlu mu olumsuz mu olduğunu belirtir.
- `Paylaşım` sütunu: Sosyal medya metinlerini içerir.

## 🧠 Kullanılan Yöntemler

- **Veri Temizleme ve Ön İşleme**
- **Veri Görselleştirme**
- **Makine Öğrenmesi Modelleri:**
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
- **İstatistiksel Testler:**
  - Friedman Testi
  - T-testi
  - Wilcoxon Testi
- **Tema Kümelendirme (Clustering)**
- **Word Diversity & Cümle Uzunluğu Karşılaştırması**

## 📌 Amaç

Bu projenin amacı, sosyal medya ortamında geçen paylaşımlar üzerinden siber zorbalık türlerini analiz etmek ve sınıflandırma performanslarını karşılaştırarak en etkili modeli belirlemektir.

## 📈 Sonuçlar

- En yüksek doğruluk oranı Logistic Regression modeli ile elde edilmiştir.
- Negatif paylaşımlar cinsiyet temelli, dini/ulusal değerlere saldırı, kişisel hakaret gibi alt temalara ayrılmıştır.

## 🔮 Gelecek Çalışmalar

- Derin öğrenme tabanlı modellerin (örneğin LSTM, BERT) entegrasyonu
- Açıklanabilir yapay zeka yöntemlerinin kullanımı
- Gerçek zamanlı sistemlere adaptasyon

## 🛠️ Gereksinimler

- Python 3.x
- pandas, scikit-learn, matplotlib, seaborn, nltk vb.
(Notebook içerisinde gerekli tüm kütüphaneler listelenmiştir.)

## 📄 Proje Posteri

[![PDF İndir](https://img.shields.io/badge/Poster%20PDF-Download-red?logo=adobeacrobatreader&logoColor=white)](./POSTER.pdf)

Bu projeye ait poster dosyasını yukarıdaki bağlantıdan görüntüleyebilirsiniz.



### Cyberbullying Detection on Turkish Social Media

In this project, data analysis and machine learning techniques were applied to detect cyberbullying using Turkish social media posts. The study was conducted using a dataset obtained from [Kaggle](https://www.kaggle.com/datasets).

## 📊 Dataset Used

- **Source:** Turkish Social Media Post Dataset  
- **Size:** 11,119 rows, 2 columns (`Tip`, `Paylaşım`)
- `Tip` column: Indicates whether the post is positive or negative  
- `Paylaşım` column: Contains the social media post text

## 🧠 Methods Applied

- **Data Cleaning and Preprocessing**
- **Data Visualization**
- **Machine Learning Models:**
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
- **Statistical Tests:**
  - Friedman Test
  - T-test
  - Wilcoxon Test
- **Thematic Clustering**
- **Word Diversity & Sentence Length Comparison**

## 📌 Objective

The aim of this project is to analyze the types of cyberbullying present in social media content and to compare classification model performances in order to determine the most effective one.

## 📈 Results

- The highest classification accuracy was achieved with the Logistic Regression model.
- Negative posts were grouped into sub-themes such as gender-based abuse, attacks on religious/national values, and personal insults.

## 🔮 Future Work

- Integration of deep learning models (e.g., LSTM, BERT)
- Use of explainable AI methods
- Adaptation into real-time analysis systems

## 🛠️ Requirements

- Python 3.x
- Libraries: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `nltk`, etc.  
  (All required packages are listed within the notebook.)

## 📄 Project Poster

[![Download PDF](https://img.shields.io/badge/Poster%20PDF-Download-red?logo=adobeacrobatreader&logoColor=white)](./POSTER.pdf)

You can view or download the poster file of this project by clicking the button above.

---

## 📚 Kaynakça / References

1. **Kaggle - Türkçe Sosyal Medya Paylaşım Veri Seti**  
   [https://www.kaggle.com/datasets/atilladedeoglu/turkce-sosyal-medya-paylasim-veri-seti](https://www.kaggle.com/datasets/atilladedeoglu/turkce-sosyal-medya-paylasim-veri-seti)  
   Bu veri seti, Türkçe sosyal medya paylaşımlarını içermektedir ve siber zorbalık analizi için kullanılmıştır.  
   *This dataset contains Turkish social media posts and was used for cyberbullying analysis.*

2. **Pedregosa et al., Scikit-learn: Machine Learning in Python, JMLR 12, 2011**  
   [https://scikit-learn.org](https://scikit-learn.org)  
   Bu proje kapsamında sınıflandırma algoritmalarının çoğu scikit-learn kütüphanesi ile uygulanmıştır.  
   *Most classification algorithms in this project were implemented using the scikit-learn library.*

3. **NLTK: Natural Language Toolkit**  
   [https://www.nltk.org/](https://www.nltk.org/)  
   Türkçe metin ön işleme adımlarında (noktalama temizliği, tokenizasyon vb.) kullanılmıştır.  
   *Used for preprocessing tasks like punctuation cleaning and tokenization.*

4. **Seaborn & Matplotlib**  
   [https://seaborn.pydata.org/](https://seaborn.pydata.org/)  
   [https://matplotlib.org/](https://matplotlib.org/)  
   Görselleştirme işlemleri bu iki kütüphane ile yapılmıştır.  
   *Data visualization was performed using these two libraries.*

---


