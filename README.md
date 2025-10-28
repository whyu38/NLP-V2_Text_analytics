# Analisis Sentimen Review Film IMDB

Repositori ini berisi Jupyter Notebook (`V2_Text_analytics.ipynb`) yang mendemonstrasikan *pipeline* lengkap untuk analisis sentimen pada dataset review film IMDB.

Tujuan dari notebook ini adalah untuk membersihkan data teks review dan membangun model machine learning yang dapat mengklasifikasikan sebuah review sebagai **positif** atau **negatif**.

## 🚀 Langkah-langkah Utama

Notebook ini mencakup proses-proses berikut:

1.  **Pemuatan Data**: Membaca file `IMDB Dataset.csv`.
2.  **Exploratory Data Analysis (EDA)**: Menganalisis distribusi sentimen dan panjang review.
3.  **Preprocessing Teks**:
    * Membersihkan tag HTML dan tanda baca.
    * Tokenisasi (memecah teks menjadi kata).
    * Lemmatization (mengubah kata ke bentuk dasar).
    * Menghapus *Stopwords* (kata-kata umum).
4.  **Visualisasi Data**: Membuat *Word Clouds* dan plot N-gram (Bigram/Trigram) untuk menemukan kata/frasa kunci.
5.  **Feature Engineering**: Mengubah teks bersih menjadi fitur numerik menggunakan **TF-IDF**.
6.  **Modeling**: Membangun dan mengevaluasi model klasifikasi (`Multinomial Naive Bayes`) untuk memprediksi sentimen.

## 🛠️ Teknologi

* Python
* Pandas
* NLTK
* Scikit-learn (sklearn)
* Matplotlib / Seaborn
* WordCloud
