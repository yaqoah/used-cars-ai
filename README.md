# 🚗 Car Price Prediction

A full-stack ML pipeline that scrapes car listings from the web, cleans and analyzes the data, then trains predictive models to estimate car prices based on various features.

## 📌 Project Overview
This project aims to predict the price of used cars by building a machine learning model from 80k real-world car listings scraped from Piston Heads UK. It combines web scraping, data preprocessing, EDA, and predictive modeling into a clean, modular, and professional pipeline.

## 🛠️ Tools & Technologies
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, Matplotlib
- **Web Scraping**: Selenium, BeautifulSoup
- **Environments**: Jupyter Notebooks, .py scripts

## 📊 Workflow Pipeline
``` text
[Web Scraping] ➔ [Data Cleaning & EDA] ➔ [Feature Engineering] ➔ [Model Training & Evaluation]
```
## 🚀 How to Run the Project

### ➡ **To explore the notebook** Open the Jupyter notebooks in the `notebooks/` folder to see the data handling logic and ML model pipeline.

#### 1. **Clone the repository** 
``` text
git clone https://github.com/yaqoah/used-cars-ai.git 
cd used-cars-ai
```
#### 2. **Install dependencies** 
``` bash
pip install -r requirements.txt 
``` 
#### 3. **Run scraping script** (optional) 
``` bash
python src/car-scraping.ipynb 
``` 