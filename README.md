# 🧠 Word Cloud Generator (Streamlit App)

A simple and interactive **Word Cloud Generator** built using **Streamlit**, which allows users to upload text-based files and visualize word frequency in a visually appealing way.

---

## 🚀 Features

* 📂 Upload files in multiple formats:

  * `.txt`
  * `.pdf`
  * `.docx`
* ☁️ Generate a **Word Cloud**
* 🧹 Remove **stopwords** (default + custom)
* 📊 View **word frequency table**
* 🎛️ Customize:

  * Word cloud width & height
  * Output resolution
  * File format (PNG, JPEG, SVG, PDF)
* 📥 Download:

  * Word cloud image
  * Word count table (CSV)

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **Pandas**
* **Matplotlib**
* **WordCloud**
* **PyPDF2**
* **python-docx**
* **Plotly (optional use)**

---

## 📁 Project Structure

```
wordcloud/
│── word_cloud_app.py   # Main Streamlit app
│── requirements.txt    # Dependencies
│── README.md           # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/wordcloud-app.git
cd wordcloud-app
```

### 2️⃣ Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the App

```bash
streamlit run word_cloud_app.py
```

---

## 📌 How It Works

1. Upload a file (`.txt`, `.pdf`, `.docx`)
2. The app extracts text content
3. Words are tokenized and counted
4. Stopwords are removed (optional)
5. A word cloud is generated
6. Users can:

   * Customize dimensions
   * Download the output
   * View word frequency table

---

## 🎯 Example Use Cases

* 📚 Text analysis for documents
* 📰 News or article keyword extraction
* 📊 Data exploration
* 🧠 NLP beginner projects
* 🎓 Academic assignments

---

## ⚠️ Known Issues / Improvements

* PDF text extraction may fail for scanned PDFs
* Case sensitivity not fully normalized
* No punctuation cleaning (can be improved)
* Large files may slow processing

---

## 🔮 Future Improvements

* Add NLP preprocessing (stemming, lemmatization)
* Support for multiple languages
* Interactive Plotly visualizations
* Deploy on Streamlit Cloud
* Add dark mode support

---

## 🤝 Contributing

Feel free to fork the repo and submit pull requests.

---

## 📄 License

This project is open-source and available under the **APACHE LICENSE 2.0**.

---

## 🙌 Author

**Animesh Sandhu**

* Background: Data scientist

