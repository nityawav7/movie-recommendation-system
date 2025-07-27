# Movie Recommendation System 🎬

A content-based movie recommender built using Python and machine learning. This system suggests similar movies based on a user’s input using cosine similarity on movie metadata.

---

## 🔍 Features

- Recommend similar movies based on selected input
- Uses cosine similarity on vectorized metadata
- Built with pandas, scikit-learn, and pickle
- Interactive Jupyter Notebook interface
- Lightweight and easy to run locally

---

## 📁 Folder Structure

```
movie-recommendation-system/
│
├── mrs final.ipynb             # Jupyter Notebook with full logic
├── movie_dict.pkl              # Dictionary of movie metadata
├── movies.pkl                  # Vectorized movie metadata
├── requirements.txt            # List of dependencies
└── .gitignore                  # Files ignored by Git
```

---

## 🚀 Getting Started

Follow these instructions to get the project up and running on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/nityawav7/movie-recommendation-system.git
cd movie-recommendation-system
```

### 2. (Optional) Create a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate   # On Windows
# OR
source venv/bin/activate   # On Mac/Linux
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🧠 How It Works

1. The movie metadata is preprocessed and vectorized using TF-IDF.
2. Cosine similarity is calculated between movies.
3. Based on the input movie, the top N similar movies are suggested.

---

## 📝 Example Usage

Open the notebook and run:

```python
recommend("Avatar")
```

This will display a list of similar movies based on the metadata.

---

## ✅ Requirements

- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  
- scipy  

Do **not** include `pickle` in `requirements.txt` — it's part of the Python standard library.

---

## 📌 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 👤 Author

**Nitya Nand**  
GitHub: [nityawav7](https://github.com/nityawav7)
