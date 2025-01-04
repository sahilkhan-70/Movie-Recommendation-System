# 🎬 Movie Recommendation System
[Movie Recommendation System](https://github.com/user-attachments/assets/bb2d016c-b28b-4824-b2de-17d00b74a1ca)

A personalized movie recommendation system using **content-based filtering** and **collaborative filtering** to help users discover movies they'll love.  

## 🚀 Features  
- **Content-Based Filtering**: Recommends movies similar to a given movie using genres.  
- **Collaborative Filtering**: Suggests movies based on user ratings and preferences using **Singular Value Decomposition (SVD)**.  
- **Hybrid Recommendations**: Combines both methods for a more robust recommendation system.  
- **Interactive Web App**: Built with **Streamlit**, allowing users to search for recommendations interactively.  
- **Poster Integration**: Displays movie posters fetched using the **TMDB API**.  

## 📂 Dataset  
This project uses the **MovieLens Small Dataset** ([download here](https://grouplens.org/datasets/movielens/)).  


## 📜 How It Works  
1. **Content-Based Filtering**  
   - Uses **TF-IDF Vectorizer** to compute similarity based on genres.  
   - Recommends movies similar to the selected one.  

2. **Collaborative Filtering**  
   - Implements **SVD** from the Surprise library to predict user ratings.  
   - Works well for recommending movies to specific users.  

3. **Interactive Interface**  
   - Enter a movie name in the app and get recommendations along with posters.  

## 🔑 Key Libraries Used  
- **Pandas**: Data manipulation  
- **Scikit-Learn**: Content-based filtering  
- **Surprise**: Collaborative filtering  
- **Streamlit**: Web app deployment  
- **TMDB API**: Fetching movie posters  

## 📖 Learnings  
- Data preprocessing and feature engineering  
- Implementing recommendation systems with real-world datasets  
- API integration and working with external libraries  
- Deploying Python projects with Streamlit  

## 🤝 Contributing  
Feel free to contribute by:  
- Reporting bugs  
- Suggesting features  
- Submitting pull requests  

## 🛠️ Installation  

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/sahilkhan-7/Movie-Recommendation-System.git  
   cd Movie-recommendation-System
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the app:  
   ```bash  
   streamlit run main.py  
   ```  
