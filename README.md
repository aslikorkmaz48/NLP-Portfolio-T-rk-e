# 🇹🇷 Türkçe NLP Portfolyosu (Turkish Natural Language Processing)

Bu depo, Türkçenin morfolojik yapısına ve eklemeli dil özelliklerine odaklanan, uçtan uca (end-to-end) NLP çözümlerini içermektedir. Projeler; klasik metin madenciliğinden modern **Transformer** tabanlı üretken yapay zeka mimarilerine kadar geniş bir teknik yelpazeyi kapsamaktadır.

---

## 🚀 Proje Katalogu

### 🔍 1. Akıllı Anahtar Kelime Çıkarıcı
* **Dosya:** `Turkce_Anahtar_Kelime_Cikarici_TFIDF.ipynb`
* **Teknoloji:** TF-IDF, Zeyrek (Lemmatizer), Scikit-Learn.
* **Özet:** Metin içerisindeki anlamsal ağırlığı en yüksek kelimeleri istatistiksel yöntemlerle tespit eder. Türkçenin eklemeli yapısını Zeyrek ile çözerek kök bazlı skorlama yapar.

### 🛡️ 2. Spam Dedektörü & Hata Analizi
* **Dosya:** `Spam_Dedektoru_ve_Hata_Analizi.ipynb`
* **Teknoloji:** Naive Bayes/Logistic Regression, Confusion Matrix.
* **Özet:** Metinleri spam veya güvenli olarak sınıflandırır. Sadece başarı skoruna değil, "Hata Analizi" bölümüyle modelin hangi durumlarda yanıldığını (False Positives) teknik olarak inceler.

### 📊 3. Büyük Veri ve Müşteri Analitiği
* **Dosya:** `Buyuk_Veri_ve_Musteri_Analitigi.ipynb`
* **Teknoloji:** Pandas, Matplotlib, WordCloud.
* **Özet:** 3000+ satırlık müşteri yorumu verisi üzerinde frekans analizi ve görselleştirme yaparak, işletme için kritik sorun odaklarını raporlar.

### 🤖 4. Soyut Metin Özetleme (Generative AI)
* **Dosya:** `02_Ozetleme_Projesi.ipynb`
* **Teknoloji:** Hugging Face, **T5 (Text-to-Text Transfer Transformer)**.
* **Özet:** "Abstractive Summarization" kullanarak uzun metinleri anlamını bozmadan, modelin kendi cümleleriyle özetlemesini sağlar.

---

## 🛠️ Teknik Yetkinlikler

| Alan | Kullanılan Araçlar / Teknikler |
| :--- | :--- |
| **Dil & Kütüphane** | Python, Pandas, NumPy, Scikit-Learn |
| **NLP Araçları** | Zeyrek (Turkish Morphological Analyzer), NLTK, Gensim |
| **Derin Öğrenme** | Transformers (Hugging Face), PyTorch |
| **Vektörleştirme** | TF-IDF, Word2Vec (Skip-gram/CBOW) |

---

## 🏗️ Yol Haritası (Gelecek Özellikler)
- [ ] **Semantik Arama Motoru:** Word2Vec ile niyet tabanlı ürün eşleştirme.
- [ ] **API Deployment:** Modellerin FastAPI üzerinden canlıya alınması.
- [ ] **BERT Entegrasyonu:** Türkçe için fine-tune edilmiş BERT modelleri ile duygu analizi.

---

**Geliştirici:** Aslı Korkmaz  
**Durum:** 🛠️ Aktif Geliştirme ve Gelişmiş Proje İnşası
