# melbourne-parking-prediction
Advanced ML project predicting Melbourne parking patterns using Random Forest and live API data.
# Melbourne Urban Mobility: Predictive Parking Analytics 🚗📊

## 📌 Project Overview
This project leverages open data and machine learning to analyze and predict urban parking constraints within the City of Melbourne. As a Data Science student at **Monash University**, I developed this end-to-end pipeline to transition from basic descriptive analytics to advanced predictive modeling.

The project explores how temporal factors (time of day/week) and environmental conditions (live weather) influence parking restrictions across the CBD.

## 🚀 Advanced Features
- **Live API Integration:** Connects to real-time meteorological data (Open-Meteo API) to simulate environmental impacts on parking demand.
- **Predictive Modeling:** Implemented a **Random Forest Classifier** to predict weekend restriction patterns with high accuracy.
- **Statistical Inference:** Conducted **Chi-Squared Hypothesis Testing** to validate the statistical significance of temporal parking trends (p-value < 0.05).
- **Model Persistence:** The trained model is serialized as a `.pkl` file, making it deployment-ready for web or mobile applications.

## 🛠️ Tech Stack
- **Languages:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-Learn, SciPy, Seaborn, Matplotlib
- **APIs:** Open-Meteo REST API
- **Tools:** Google Colab, GitHub, Git

## 📈 Key Insights
- **Temporal Patterns:** Identified that 1P (1-hour) and 2P (2-hour) restrictions are the dominant modes, suggesting a city-wide policy favoring high turnover.
- **Peak Enforcement:** Data revealed that 8:00 AM is the primary "trigger" hour for the majority of city-wide parking restrictions.
- **Weekend Shift:** Statistical testing confirmed a significant disparity between weekday and weekend enforcement density, allowing for better mobility planning.

## 📂 Repository Structure
- `Melbourne_Parking_Analysis.ipynb`: Full source code with detailed documentation.
- `melbourne_parking_ai_v1.pkl`: The trained and serialized Random Forest model.
- `data/`: (Optional) Folder containing the raw CSV dataset.

## 🔧 How to Run
1. Clone this repository: `git clone https://github.com`
2. Open the `.ipynb` file in **Google Colab** or **Jupyter Notebook**.
3. Ensure you have the required libraries installed: `pip install pandas scikit-learn requests seaborn`

---
**Author:** Pratiksha - Data Science Student at Monash University
