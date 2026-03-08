# Twitter Sentiment Analysis: Text Preprocessing & EDA

## Deskripsi Project
Project ini merupakan tahap eksplorasi dan persiapan data (*Work in Progress*) untuk pembuatan model klasifikasi sentimen Twitter (deteksi *hate speech* dan rasisme). Saat ini, fokus utama dari project berada pada tahap **Data Cleaning**, **Text Preprocessing**, dan **Exploratory Data Analysis (EDA)**. 

Karena data teks dari Twitter cenderung berantakan dan tidak terstruktur, project ini mendemonstrasikan tahapan iteratif (*workflow* eksploratif) dalam membersihkan *tweet* sebelum nantinya dimasukkan ke dalam algoritma *Machine Learning*.

## Struktur Direktori dan File
* `sentiment_analysis.ipynb`: *Notebook* utama yang bereksperimen dengan pembersihan data dasar (penghapusan *mention* `@user`, tanda baca), tokenisasi NLTK, *Stemming* (menggunakan `PorterStemmer`), dan visualisasi frekuensi kata menggunakan *WordCloud*.
* `Segmentation Analysis.ipynb`: *Notebook* tambahan yang mencoba *workflow* *preprocessing* sedikit berbeda, termasuk *lowercasing*, penanganan kata negasi (seperti *no, not*), dan penggunaan *Lemmatization* (`WordNetLemmatizer`).
* `train_E6oV3lV.csv`: Dataset latih berisi ID, label sentimen, dan teks *tweet*.
* `test_tweets_anuFYb8.csv`: Dataset pengujian (tanpa label).
* `sample_submission_gfvA5FD.csv`: Format referensi untuk *submission* akhir.

## Teknologi & Library yang Digunakan
Walaupun belum menggunakan pemodelan *Machine Learning* tingkat lanjut, project ini banyak memanfaatkan teknik manipulasi string dan *Natural Language Tool Kit* dasar:
* **Bahasa:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn, WordCloud
* **Text Processing:** NLTK (Tokenizer, Stopwords, Stemmer, Lemmatizer), Regular Expressions (`re`)

## Instalasi dan Persiapan (*Setup*)

Project ini menggunakan *virtual environment* terpisah agar *dependencies* terisolasi. Ikuti langkah-langkah berikut untuk menjalankan *notebook*:

1. **Clone repositori ini:**
   ```bash
   git clone <link-repo-kamu>
   cd <nama-folder-repo>
