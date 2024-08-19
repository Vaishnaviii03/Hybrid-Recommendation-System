# 🎬 Movie Recommendation System

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square) ![Python](https://img.shields.io/badge/Python-3.8-blue?style=flat-square&logo=python) ![Pandas](https://img.shields.io/badge/Pandas-1.3.3-blue?style=flat-square&logo=pandas) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24.2-yellowgreen?style=flat-square&logo=scikit-learn) ![Flask](https://img.shields.io/badge/Flask-2.0.1-red?style=flat-square&logo=flask)

## 📑 Project Overview

This project implements a movie recommendation system using collaborative filtering and content-based filtering techniques. The recommendation system is built using the [Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) from Kaggle. The project includes a Jupyter Notebook for model development and a Flask-based web application to serve recommendations.

## 🗂️ File Structure

- **FinalRecommendationSystem.ipynb**: The main Jupyter Notebook containing the code for data processing, model training, and evaluation.
- **app.py**: The Flask application script that serves the recommendation system via a web interface.
- **README.md**: Project documentation.

## 🛠️ Tools Used

- ![Python](https://img.shields.io/badge/Python-3.8-blue?style=flat-square&logo=python)
- ![Pandas](https://img.shields.io/badge/Pandas-1.3.3-blue?style=flat-square&logo=pandas)
- ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24.2-yellowgreen?style=flat-square&logo=scikit-learn)
- ![Flask](https://img.shields.io/badge/Flask-2.0.1-red?style=flat-square&logo=flask)

## 🔧 Installation

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
2. **Install the required dependencies**:
```bash
    pip install -r requirements.txt
```
3. **Launch the Flask Application**:
```bash
    python app.py
```
4. **Launch the Flask Application**:
```bash
    python app.py
```

## 🔍 Key Analysis Steps

### Data Preprocessing:
- Loaded and cleaned the dataset.
- Prepared features for collaborative filtering and content-based filtering.

### Model Development:
- Implemented collaborative filtering using matrix factorization techniques.
- Developed content-based filtering to recommend movies based on content similarity.

### Evaluation:
- Evaluated the models using metrics like RMSE and precision at k.

### Visualization:
- Visualized recommendation results and performance metrics.

## 📝 License
This project is licensed under the MIT License. See the LICENSE file for more details.

## 🤝 Acknowledgements
- **Kaggle**: For providing the dataset.
- **Scikit-Learn**: For machine learning tools and algorithms.
- **Flask**: For enabling the development of the web application.


