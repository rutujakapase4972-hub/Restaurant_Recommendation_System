# 🍽 Restaurant Recommendation System

A full-stack AI-powered restaurant recommendation system using **Content-Based Filtering** 
with TF-IDF Vectorization and Cosine Similarity. Built with Flask, scikit-learn, and the 
Zomato Bangalore Restaurants dataset.

---

## 📁 Project Structure

```
restaurant_recommendation/
├── Dataset/
│   └── zomato.csv                          # Zomato Bangalore dataset (download from Kaggle)
├── Flask/
│   ├── app1.py                             # Main Flask application
│   ├── train_model.py                      # Model training script
│   ├── restaurant.pkl                      # Trained model (generated)
│   ├── restaurant1.csv                     # Processed data (generated)
│   ├── templates/
│   │   ├── index.html                      # Home page
│   │   ├── web.html                        # Recommendation input page
│   │   └── result.html                     # Results page
│   └── static/
│       ├── css/
│       │   └── main.css                    # All styles
│       ├── js/
│       │   └── main.js                     # Frontend JS
│       └── images/                         # Static images
├── Model/
│   └── Restaurant_Recommendation_System.ipynb   # Jupyter notebook with full analysis
├── requirements.txt
└── README.md
```

---

## 🚀 Setup & Installation

### Step 1: Install Dependencies
```bash
pip install -r requirements.txt
```
Or install individually:
```bash
pip install pandas matplotlib seaborn plotly numpy scikit-learn Flask nltk
```

### Step 2: Train the Model
```bash
cd Flask
python train_model.py
```


### Step 3: Run the Flask App
```bash
cd Flask
python app1.py
```
Open your browser at: **http://127.0.0.1:5000**

---

## Dataset

The dataset used for this project is available at the link below:

https://drive.google.com/drive/folders/1JciSEUE87frDawF-mNm40uRn5dIcIyZ9?usp=sharing

restaurant.csv file link below:

https://drive.google.com/file/d/1bMhDjB6P0AiyfSsSLchi1u7EDgjNnrr7/view?usp=sharing


## Project Demo

Demo Video Link:

https://drive.google.com/file/d/15AGAENM_1TN86fKbddYsu2FwsHlqH6S7/view?usp=sharing
