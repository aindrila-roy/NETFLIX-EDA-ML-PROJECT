# Netflix EDA and ML Project 
# Netflix Content Library Segmentation

## Project Overview
This project performs Exploratory Data Analysis (EDA) and unsupervised machine learning clustering on a dataset of over 7,700 Netflix movies and TV shows. The goal is to segment the content library into meaningful groups to support strategic business decisions.

## Key Features
- Extensive EDA revealing content distribution by type, country, and release year  
- Text preprocessing pipeline transforming metadata into numerical features using TF-IDF  
- Comparison of clustering algorithms: K-Means, Agglomerative, and DBSCAN  
- Identification and interpretation of 5 content clusters with visualization tools  
- Production-ready K-Means model saved for real-world deployment  

## Project Structure
- `Sample_EDA_Submission_Template.ipynb` — Exploratory Data Analysis notebook  
- `Sample_ML_Submission_Template.ipynb` — Machine Learning pipeline notebook  
- `NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv` — Dataset file  
- `kmeans_model.joblib` — Saved K-Means clustering model  
- `tfidf_vectorizer.joblib` — Saved TF-IDF vectorizer object  
- `.gitignore` — Git ignore file to exclude unnecessary files  
- `README.md` — This file  

## Getting Started

### Prerequisites
- Python 3.x  
- Virtual environment tool (optional but recommended)  

### Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/aindrila-roy/NETFLIX-EDA-ML-PROJECT.git
   cd NETFLIX-EDA-ML-PROJECT
