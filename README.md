# Applied-Data-Science-Capstone

This project is part of the IBM Data Science Professional Certificate.  
The goal is to predict the success of SpaceX Falcon 9 first-stage landings using real-world data.  
Accurate predictions help reduce launch costs by enabling reusable rockets.

---

## Project Structure

Applied-Data-Science-Capstone/
│
├── 1-Introduction/ # Data collection & wrangling
├── 2-Exploratory-Data-Analysis/ # EDA & SQL analysis
├── 3-Interactive-Visual-Analytics/ # Interactive visualizations & dashboards
├── 4-Predictive-Analysis/ # Machine learning prediction models
├── data/ # Datasets & database files
├── requirements.txt
├── LICENSE
└── README.md

---

## Modules

### 1. Introduction
- **Data Collection:** SpaceX REST API  
- **Web Scraping:** Launch data from Wikipedia  
- **Data Wrangling:** Cleaning and preparing datasets  

Example screenshot:  
![Data Collection](images/data_collection.png)

---

### 2. Exploratory Data Analysis (EDA)
- SQL queries to analyze launches  
- Visualization of launch frequency, success rates  

Example screenshot:  
![EDA](images/eda_visuals.png)

---

### 3. Interactive Visual Analytics
- Launch site maps with **Folium**  
- Interactive dashboards using **Plotly Dash**  

Example screenshot:  
![Interactive Dashboard](images/interactive_dashboard.png)

---

### 4. Predictive Analysis
- Classification models: Logistic Regression, SVM, Decision Tree, KNN  
- Evaluation with accuracy scores and confusion matrices  

**Model Accuracy Table**

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression     | 94.4%    |
| K-Nearest Neighbors      | 94.4%    |
| Support Vector Machine   | 88.8%    |
| Decision Tree            | 88.8%    |

Example screenshot:  
![Model Performance](images/model_performance.png)

---

## Tools & Libraries
- **Python**: Pandas, NumPy, Scikit-learn  
- **Visualization**: Matplotlib, Seaborn, Plotly, Folium  
- **Web**: BeautifulSoup, Requests  
- **Database**: SQLite  
- **Dashboards**: Plotly Dash  

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Applied-Data-Science-Capstone.git
   cd Applied-Data-Science-Capstone

2. Install dependencies:
  pip install -r requirements.txt

3. Open Jupyter Notebook:
  jupyter notebook

4. Run notebooks in each module sequentially.

## Results

- Interactive maps showing launch site locations and outcomes  
- Dashboards for launch success prediction  
- High accuracy achieved with Logistic Regression and KNN models  

## Author

Mahmoud Abdelrahim Attwany  
IBM Data Science Professional Certificate  
  
