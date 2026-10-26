# 📊 Hierarchical-Agglomerative Clustering Web App

Upload a CSV file, preprocess the data (missing values, encoding, scaling), and generate a **dendrogram** using hierarchical clustering — all in your browser.

---

## 🚀 Features

- ✅ Upload any structured CSV file.
- ✅ Automatic data cleaning:
  - Handles missing values
  - One-hot encodes categorical columns
  - Scales numeric features
- ✅ Custom implementation of Hierarchical (Agglomerative) Clustering
- ✅ Shows:
  - Step-by-step merging process
  - A clean dendrogram image
- ✅ Built with **Python**, **Flask**, **scikit-learn**, **Matplotlib**, **Pandas**, and **Numpy**

---

## 🛠 Setup Instructions

### 1. Clone the Repo

```bash
git clone [https://github.com/uday-gandhi/smart-clustering.git](https://github.com/uday-gandhi04/Hierarchical-Agglomerative)
cd smart-clustering
```

### 2. Install Dependencies

Make sure you’re using Python 3.7 or above.

```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
python app.py
```

Then open: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📂 Folder Structure

```
smart_clustering/
├── app.py                # Flask app
├── clustering.py         # Clustering & preprocessing logic
├── requirements.txt
├── templates/
│   ├── index.html        # File upload form
│   └── result.html       # Result page with steps & dendrogram
├── static/
│   ├── style.css         # Optional CSS styling
│   └── dendrogram.png    # Saved plot
├── uploads/              # Auto-created for uploaded files
```

---

## 🧠 Clustering Algorithm

- Implements **Agglomerative Hierarchical Clustering** from scratch.
- Uses **Euclidean distance** for cluster proximity.
- Visual output via **Matplotlib dendrogram**.
- Records and displays every **merging step**.

---

