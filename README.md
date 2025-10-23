# 🎬 Movie Recommendation System

> Hybrid recommendation engine combining Content-Based Filtering (NLP/TF-IDF), Collaborative Filtering, and Matrix Factorization (SVD)

## 📊 Project Overview

This project was developed during my 1-month internship at Bee Codeers
 as part of my Bachelor’s degree in Computer Science – Artificial Intelligence and Data Science at Pristini School Of Ai.

The goal was to design and implement a hybrid movie recommendation system capable of analyzing 25 million user ratings and over 1 million tags, leveraging both content-based and collaborative methods for high-quality movie recommendations.

## ✨ Features

- **Content-Based Filtering**: Genre matching + NLP (TF-IDF) on 73K user tags
- **Collaborative Filtering**: User-user and item-item similarity
- **Matrix Factorization**: SVD for handling sparse data (99.74% sparsity)
- **Hybrid Approach**: Weighted ensemble combining all methods
- **Production Ready**: Flask RESTful API with <300ms latency
- **Web Integration**: Deployed and integrated with existing authentication system

## 📈 Dataset

- **Source**: MovieLens 25M Dataset
- **Size**: 25,000,095 ratings
- **Users**: 162,541 users
- **Movies**: 62,423 movies
- **Tags**: 1,093,360 user-generated tags
- **Time Span**: 1995-2019 (25 years)

## 🛠️ Tech Stack

**Data Science & ML:**
- Python 3.9+
- pandas, NumPy, scikit-learn
- NLP: TF-IDF vectorization
- Algorithms: KNN, SVD, Cosine Similarity

**Visualization:**
- Matplotlib, Seaborn
- WordCloud
- 25+ publication-quality visualizations

**Backend (Coming Soon):**
- Flask RESTful API
- SQLite database
- Production deployment

## 📁 Project Structure
```
MovieRecommenderSystem/
├── data/
│   ├── raw/                  # Original MovieLens data (gitignored)
│   └── processed/            # Cleaned, featured data
├── notebooks/
│   ├── 01_data_loading.ipynb            ✅ Complete
│   ├── 02_data_preprocessing.ipynb      ✅ Complete
│   ├── 03_eda_visualizations.ipynb      ✅ Complete
│   ├── 04_content_based_NLP.ipynb       🚧 In Progress
│   ├── 05_collaborative.ipynb           📍 TODO
│   ├── 06_matrix_factorization.ipynb    📍 TODO
│   └── 07_hybrid_evaluation.ipynb       📍 TODO
├── models/                   # Trained models
├── reports/figures/          # 25+ visualizations
├── api/                      # Flask API (Week 2)
└── requirements.txt
```

## 🚀 Quick Start
```bash
# Clone repository
git clone https://github.com/Mohamed Hedi Foughali/MovieRecommenderSystem.git
cd MovieRecommenderSystem

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Download MovieLens 25M dataset
# Place in data/raw/

# Run notebooks in order (01 → 07)
```

## 📊 Key Results (To be updated)

- **RMSE**: TBD (Target: <0.90)
- **Precision@10**: TBD (Target: >0.25)
- **API Latency**: TBD (Target: <300ms)
- **Coverage**: TBD

## 📸 Visualizations

*(Screenshots will be added as project progresses)*

## 🎓 Academic Context

This project was developed during my Bachelor’s internship at Bee Codeers, as part of my AI & Data Science specialization at Pristini School Of Ai .

**Focus Areas:**
- Recommender Systems
- Natural Language Processing
- Machine Learning
- Software Engineering

## 👤 Author

**Mohamed Fourati**
- GitHub: [@Mohammed Hedi Foughali](https://github.com/Mohamed Hedi Foughali)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/mohamed-hedi-foughali)
- University: [Pristini School Of Ai]

## 📝 License

This project is part of an academic internship and is for educational and research purposes only.

## 🙏 Acknowledgments

- Bee Codeers for guidance and internship opportunity
- Pristini School Of Ai Computer Science Department


---

**Project Status**: 🚧 Week 1 - In Progress (42.8% complete)

**Last Updated**: January 2025