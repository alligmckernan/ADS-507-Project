# 🎥 Movie Recommendation System  

**Team Members**:  
- **Niat Kahsay**  
- **Allison McKernan**  
- **Gabriel Duffy**  

---

## 🚀 Overview  
This project builds an **ETL pipeline** to process and analyze movie ratings and metadata, ultimately generating personalized movie recommendations. The pipeline leverages collaborative filtering techniques to provide insightful suggestions, which are visualized through an interactive Tableau dashboard.

🔗 **Deployed Dashboard:** [View the Tableau Dashboard](https://public.tableau.com/newWorkbook/d4cf5cf9-4c28-4332-9b2c-ae48c241157f#1)  

---

## 📦 Contents of the Repository  
```
Movie-Recommendation-System/
├── data/              # Raw and processed datasets
├── notebooks/         # Exploratory data analysis and modeling notebooks
├── scripts/           # ETL pipeline and model training scripts
├── models/            # Saved models and evaluation metrics
├── dashboard/         # Tableau workbook and visualization files
├── requirements.txt   # Project dependencies
└── README.md          # Project documentation
```

- **data/**: Contains original and cleaned datasets used for model training.
- **notebooks/**: Jupyter notebooks for data exploration, feature engineering, and model selection.
- **scripts/**: Python scripts for data extraction, transformation, loading, and recommendation model development.
- **models/**: Stores trained models and performance metrics.
- **dashboard/**: Includes Tableau files and related resources for visualizations.

---

## 🚀 How to Deploy the Pipeline  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-username/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
   ```
2. **Install dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the ETL pipeline:**  
   Execute the ETL script to clean and prepare the data:  
   ```bash
   python scripts/etl_pipeline.py
   ```
4. **Train the recommendation model:**  
   Run the model training script:  
   ```bash
   python scripts/train_model.py
   ```
5. **Deploy the visualization:**  
   - Export the model predictions to a CSV file.
   - Open Tableau, import the CSV, and publish the dashboard.
   - Access the deployed dashboard via [Tableau Public](https://public.tableau.com/newWorkbook/d4cf5cf9-4c28-4332-9b2c-ae48c241157f#1).

---

## 📊 How to Monitor the Pipeline  
Monitoring ensures data freshness, model performance, and dashboard accuracy. Here’s how to manage it:

- **Data Updates:**  
  Schedule regular data pulls by automating `etl_pipeline.py` using cron jobs or Airflow.

- **Model Performance:**  
  - Retrain models periodically to account for new data trends.
  - Review evaluation metrics stored in the `models/` directory.

- **Dashboard Monitoring:**  
  - Tableau refreshes the visualizations whenever the source CSV is updated.
  - Ensure data is consistently exported to the same file path to avoid breaking links.
  - Use Tableau Public’s built-in features to monitor dashboard views and interactions.

---

## 🛠️ Tools & Technologies  
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, SciKit-Learn, Surprise  
- **Visualization:** Tableau  
- **Pipeline Orchestration:** Manual scripts (extendable to Apache Airflow)  

---

## 📈 Results & Insights  
- **Top Movie Recommendations:** Users can select their `userId` in the Tableau dashboard to view personalized movie recommendations.
- **Rating Trends:** Visualizations display predicted ratings distributions and user rating behaviors.
- **User-Movie Heatmaps:** Highlight clusters of high and low predicted ratings across user-movie pairs.

Explore the live dashboard: [Tableau Deployment](https://public.tableau.com/newWorkbook/d4cf5cf9-4c28-4332-9b2c-ae48c241157f#1) 🚀

