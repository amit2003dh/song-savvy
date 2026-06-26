# 🎵 SongSavvy

SongSavvy is an intelligent, content-based recommendation system designed to curate personalized Bollywood music recommendations. By analyzing acoustic features and metadata, the system suggests tracks that match the vibe and characteristics of a user's favorite music.

## 🚀 Key Features

- **Content-Based Filtering:** Utilizes advanced machine learning models to analyze track similarities based on genres, artists, and acoustic features.
- **Interactive UI:** Built using Streamlit to offer a clean, responsive, and user-friendly interface for instantaneous recommendation generation.
- **Vectorized Searching:** Employs text vectorization and cosine similarity scoring to accurately match and rank song recommendations.

## 🛠️ Tech Stack

- **Core Language:** Python
- **Machine Learning & Analytics:** Scikit-learn, Pandas, NumPy
- **Frontend/Application Framework:** Streamlit
---


## 📁 Project Structure

```
SongSavvy/
├── app.py                     # Streamlit app
├── recommendation_engine.py  # Core recommendation logic
├── utils.py                  # Preprocessing and helper functions
├── data/
│   └── bollywood_songs.csv   # Dataset
├── .streamlit/
│   └── config.toml           # Streamlit configuration
├── requirements.txt          # Python dependencies
├── pyproject.toml            # Project metadata (optional)
├── .gitignore                # Files to ignore in Git
└── README.md                 # Project documentation
```

---

## 🛠️ Installation & Running

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/SongSavvy.git
   cd SongSavvy
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

4. **Enjoy discovering music!** 🎶

---

## 📊 Dataset

The app uses a curated dataset of Bollywood songs:  
**Path:** `data/bollywood_songs.csv`  
Make sure this file exists before running the application.

---

## ⚙️ How It Works

1. **Data Preprocessing**  
   Song metadata is cleaned and prepared using `utils.py`.

2. **Feature Extraction**  
   - TF-IDF vectorization is applied on song features (lyrics, artist, genre, etc.)

3. **Similarity Measurement**  
   - Cosine similarity is calculated between song vectors.

4. **Recommendations**  
   - Top-N most similar songs are shown with explanation of similarity.

---

## 🧰 Dependencies

- Python 3.11+
- Streamlit
- Pandas
- NumPy
- scikit-learn

---



