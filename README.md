#  Text Mining on Bank Customer Feedback (Banka Müşteri Geri Bildirimleri Üzerine Metin Madenciliği)

## 📊 About the Project (Proje Hakkında)

This project focuses on analyzing textual feedback from bank customers using text mining techniques. NLP methods such as cleaning, visualization, classification, and topic modeling are applied using Python and various libraries.

Bu proje, banka müşterilerinden alınan metinsel geri bildirimlerin analiz edilmesini amaçlamaktadır. Metinler üzerinde temizlik, görselleştirme, sınıflandırma ve konu modelleme gibi doğal dil işleme (NLP) teknikleri uygulanmıştır.

---

## 🎯 Project Objective (Proje Amacı)

- To analyze textual feedback from bank customers  
- Banka müşterilerinin metinsel geri bildirimlerini analiz etmek  

- To derive insights using text mining methods  
- Metin madenciliği yöntemleri ile anlamlı sonuçlar çıkarmak  

- To classify texts and perform topic modeling  
- Metinleri sınıflandırmak ve konu modelleme yapmak  

---

## 📁 Dataset Used (Kullanılan Veri)

- `banka.csv`: Contains customer feedback texts and categorical labels.  
- Banka müşterilerine ait metin verisi ve kategorik etiketler içermektedir.

---

## 🔧 Technologies Used (Kullanılan Teknolojiler)

- Python  
- Pandas, NumPy  
- NLTK, TextBlob  
- Scikit-learn  
- Matplotlib, WordCloud  
- KMeans, LDA

---

## 📈 Steps & Visualizations (İşlemler ve Görselleştirmeler)

### 🔹 1. Word Cloud (Kelime Bulutu)
- **Purpose:** Visualize the most frequently used words.  
- **Amaç:** Veri setindeki en sık kullanılan kelimeleri görselleştirmek.  
- **How:** Combined all cleaned texts using `WordCloud`.  
- **Nasıl:** Temizlenmiş metinler birleştirilerek kelime bulutu oluşturuldu.  
- **Comment:** Identifies dominant terms visually.  
- **Yorum:** En çok geçen kelimeler grafiksel olarak gösterildi.

### 🔹 2. Text Classification (Metin Sınıflandırma)
- **Purpose:** Categorize feedback into labeled classes.  
- **Amaç:** Geri bildirimleri etiketlerine göre sınıflandırmak.  
- **How:** Used TF-IDF vectorization and Naive Bayes algorithm.  
- **Nasıl:** TF-IDF ile sayısallaştırma ve Naive Bayes sınıflandırıcı uygulandı.  
- **Comment:** Evaluated with classification metrics.  
- **Yorum:** Başarım, precision/recall/F1-score ile ölçüldü.

### 🔹 3. Clustering (Kümeleme)
- **Purpose:** Automatically group similar texts.  
- **Amaç:** Benzer içerikleri otomatik olarak gruplamak.  
- **How:** KMeans algorithm was used on text features.  
- **Nasıl:** TF-IDF özellikleri üzerinden KMeans algoritması uygulandı.  
- **Comment:** Helped discover semantic similarity.  
- **Yorum:** Anlamca benzer metinler aynı gruplarda toplandı.

### 🔹 4. Topic Modeling (Konu Modelleme)
- **Purpose:** Extract key topics from texts.  
- **Amaç:** Metinlerdeki temel konuları keşfetmek.  
- **How:** Used Latent Dirichlet Allocation (LDA).  
- **Nasıl:** LDA algoritmasıyla her kümenin öne çıkan kelimeleri çıkarıldı.  
- **Comment:** Provided topic-wise word distributions.  
- **Yorum:** Her konu için baskın anahtar kelimeler belirlendi.

---
