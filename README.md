# 🚀 SpaceX Falcon 9 Data Science Project

## 📌 Project Overview

This project analyzes SpaceX Falcon 9 rocket launches to uncover the key factors influencing successful landings and reducing launch costs by improving rocket reusability.

## 🎯 Objectives
- Extract SpaceX Falcon 9 launch data using APIs and web scraping
- Perform Exploratory Data Analysis (EDA) to visualize launch trends
- Query the launch data using SQL for insights
- Build a Machine Learning model to predict launch success rates
- Deploy an interactive dashboard using Dash to visualize insights

## 📂 Project Structure

```
DS Space Project/
│
├── README.md                                  # Project documentation
├── spacex_dash_app.py                         # Python Dash web app for visualization
├── edadataviz.ipynb                           # Exploratory Data Analysis & Visualization
├── jupyter-labs-eda-sql-coursera_sqlite.ipynb # SQL queries for SpaceX data
├── jupyter-labs-spacex-data-collection-api.ipynb # API data extraction
├── jupyter-labs-webscraping.ipynb             # Web scraping for SpaceX data
├── lab_jupyter_launch_site_location.ipynb     # Launch site geospatial analysis
├── labs-jupyter-spacex-Data-wrangling.ipynb   # Data cleaning & preprocessing
└── SpaceX_Machine_Learning_Prediction_Part_5.ipynb # ML model for prediction
```

## 🛠️ Tech Stack & Tools
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Jupyter Notebooks** (for data analysis and visualization)
- **SQL (SQLite)** (for querying launch data)
- **BeautifulSoup & Requests** (for web scraping)
- **Dash (Plotly)** (for interactive data visualization)
- **Machine Learning** (Logistic Regression, Decision Trees, SVM)

## 📊 Key Features

### 1. Data Collection:
- Extracted SpaceX Falcon 9 launch data via APIs and web scraping
- Stored data in a structured format using SQL

### 2. Data Analysis & Visualization:
- Analyzed launch success trends, payload impacts, and booster reusability
- Visualized launch site locations using geospatial mapping

### 3. Machine Learning Model:
- Built ML models to predict Falcon 9 landing success
- Evaluated model performance using accuracy, precision, and recall

### 4. Interactive Dashboard:
- Developed a Dash web app (`spacex_dash_app.py`) for data visualization
- Users can filter by launch site, payload mass, and booster type

## 🚀 How to Run the Project

### 1️⃣ Setup Environment
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spacex-falcon9-analysis.git
   cd spacex-falcon9-analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### 2️⃣ Run Jupyter Notebooks

Execute notebooks in order:
- `jupyter-labs-spacex-data-collection-api.ipynb`
- `jupyter-labs-webscraping.ipynb`
- `labs-jupyter-spacex-Data-wrangling.ipynb`
- `jupyter-labs-eda-sql-coursera_sqlite.ipynb`
- `edadataviz.ipynb`
- `SpaceX_Machine_Learning_Prediction_Part_5.ipynb`

### 3️⃣ Run the Dashboard

To launch the Dash visualization app:
```bash
python spacex_dash_app.py
```
Then, open http://127.0.0.1:8050/ in your browser.

## 📈 Results & Insights
- Launch sites significantly impact success rates
- Reusable boosters improve landing success and reduce costs
- Machine Learning models achieved ~80% accuracy in predicting success

## 🤝 Contributions

Feel free to fork, open issues, or submit pull requests to improve this project.

## 📜 License

This project is licensed under the MIT License.