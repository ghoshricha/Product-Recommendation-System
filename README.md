# Product-Recommendation-System

# Amazon Product Recommendation System 🔍🛒

## 📌 Overview

This project is a **content-based Amazon Product Recommendation System** built using **Natural Language Processing (NLP)** and **Machine Learning** techniques.
It allows users to search for a product and get **relevant product recommendations** based on similarity between product titles and descriptions.

The system is deployed as an **interactive web application using Streamlit**.

---

## 🚀 Features

* Product search using **text similarity**
* NLP-based preprocessing (tokenization & stemming)
* **TF-IDF Vectorization** for text representation
* **Cosine Similarity** to rank relevant products
* Simple and interactive **Streamlit UI**
* Displays top 10 most relevant products

---

## 🧠 Tech Stack

* **Python**
* **Pandas & NumPy** – data handling
* **NLTK** – text preprocessing
* **Scikit-learn** – TF-IDF & cosine similarity
* **Streamlit** – web application
* **PIL (Pillow)** – image handling

---

## 📂 Dataset

* File name: `amazon_product.csv`
* Columns used:

  * `Title`
  * `Description`
  * `Category`
* Column removed:

  * `id`

---

## ⚙️ How It Works

1. Product **Title** and **Description** are combined.
2. Text is:

   * Converted to lowercase
   * Tokenized using NLTK
   * Stemmed using **Snowball Stemmer**
3. Text is converted into vectors using **TF-IDF Vectorizer**.
4. **Cosine Similarity** is computed between user query and product data.
5. Top 10 most similar products are displayed.

---

## 🖥️ Web Application Flow

1. User enters a product name in the search box.
2. Clicks the **Search** button.
3. The system calculates similarity scores.
4. Top matching products are displayed with:

   * Title
   * Description
   * Category

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/amazon-recommendation-system.git
cd amazon-recommendation-system
```

### 2️⃣ Install Required Libraries

```bash
pip install pandas numpy nltk scikit-learn streamlit pillow
```

### 3️⃣ Download NLTK Tokenizer

```python
import nltk
nltk.download('punkt')
```

### 4️⃣ Run the Streamlit App

```bash
streamlit run app.py
```

---

## 📸 Project UI

The application includes a banner image (`img.png`) displayed at the top of the web interface for better user experience.

---

## 📈 Future Enhancements

* Add **collaborative filtering**
* Improve search speed using precomputed TF-IDF matrix
* Add product images and pricing
* Deploy the app on cloud platforms (Heroku / AWS)

---

## 👩‍💻👨‍💻 Author

**Developed by:** *[Your Name]*
**Course:** B.Tech CSE (AI & ML)
**Use Case:** Academic Project / Placement Portfolio

---

## 📄 License

This project is for **educational purposes only**.

---

If you want, I can also:

* Rewrite this for **resume/project report**
* Add **architecture diagram explanation**
* Make it **more placement-oriented**
* Convert it into a **research-style README**

Just tell me 👍
