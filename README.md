# 🛍️ Customer Behavior Clustering App

Group customers into behavioral categories using KMeans clustering. This unsupervised learning project helps segment mall shoppers for targeted marketing.

## 📌 Highlights
- Segments customers based on age, income, and spending
- Uses KMeans for group detection and PCA for visual plots
- Gender encoded and data standardized before modeling
- Predicts segment label for new entries via Streamlit interface

## 🔍 Contents
- `streamlit.py`: Web interface for input and prediction
- `main.py`: Clustering trainer
- `models/`: KMeans model and scaler saved
- `src/`: Scripts for cleaning data, feature prep, model training, and PCA-based visualization

## ▶️ Launch the App
```bash
streamlit run streamlit.py
```

## ⚙️ Dependencies
- streamlit
- pandas
- scikit-learn
- matplotlib
- seaborn