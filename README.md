

# 🚀 Winning the Space Race with Data Science  
**Capstone Project by Fernando A. | IBM Skills Network | August 2025**

This project analyzes SpaceX Falcon 9 launch data to uncover patterns in mission success, landing outcomes, and payload dynamics. It combines API integration, web scraping, SQL analysis, interactive dashboards, and machine learning to deliver actionable insights into reusable rocket technology.

---

## 📦 Project Structure

| Module | Description |
|--------|-------------|
| `DataCollection.ipynb` | Collects launch data from SpaceX API and enriches it with secondary endpoints |
| `Webscraping.ipynb` | Scrapes Wikipedia for historical launch records and payload details |
| `DataWrangling.ipynb` | Cleans and encodes data, handles missing values, creates binary labels |
| `EDAvisualization.ipynb` | Visualizes trends using Plotly and Folium |
| `EDAsql.ipynb` | Performs SQL-based analysis on launch outcomes and payloads |
| `Folium.ipynb` | Builds interactive maps with launch site proximity analysis |
| `Dashboard.py` | Creates a Plotly Dash dashboard for launch site and payload exploration |
| `MachineLearning.ipynb` | Trains and evaluates classification models to predict launch success |

---

## 🔍 Key Questions

- Which launch sites yield the highest success rates?
- How do payload mass, orbit type, and booster version affect outcomes?
- Can we predict launch success using ML models?
- What geographic and infrastructure factors influence launch reliability?

---

## 🧪 Methodology

- **Data Sources:** SpaceX REST API, Wikipedia
- **Tools:** Python (requests, BeautifulSoup, Pandas), SQL, Plotly, Folium, Scikit-learn
- **Models:** Logistic Regression, SVM, Decision Tree, KNN
- **Tuning:** GridSearchCV for hyperparameter optimization
- **Evaluation:** Accuracy, Precision, Recall, ROC-AUC

---

## 📊 Results

- **Best Launch Site:** CCAFS SLC-40 (42.9% success rate)
- **Landing Trends:** Ground pad landings succeeded from Dec 2015; drone ship landings improved post-2017
- **Model Accuracy:** Logistic Regression achieved 83.3% accuracy
- **Payload Insights:** No strong correlation between mass and success; orbit type matters more
- **Booster Performance:** F9 B5 and B4 outperform earlier versions

---

## 🌍 Interactive Visuals

- **Folium Maps:** Show launch site locations, success/failure markers, and proximity to infrastructure
- **Plotly Dash:** Interactive dashboard with pie charts, scatter plots, dropdowns, and sliders

---

## 📈 SQL Highlights

- Total payload mass for NASA: **107,010 kg**
- First successful ground landing: **Dec 22, 2015**
- Most frequent launch site: **CCAFS LC-40**
- Booster with max payload: **F9 B5 B1048.4**

---

## 🧠 Insights

- Early missions faced reliability challenges, especially in GTO and VLEO orbits
- Reusability matured with Block 5 boosters
- Launch site proximity to infrastructure (coastlines, highways) may influence logistics and frequency


---

Let me know if you'd like a version optimized for academic submission or portfolio presentation!
