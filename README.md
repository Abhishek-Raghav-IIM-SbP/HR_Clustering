Employee Performance Clustering
📌 Objective

This project applies Hierarchical Clustering to employee performance data to uncover hidden patterns in training, ratings, KPIs, and overall performance. The goal is to help HR teams make data-driven decisions and explore predictive modeling for assessing employee potential before recruitment.

📊 Dataset

The dataset includes attributes such as:

no_of_trainings

age

previous_year_rating

length_of_service

KPIs_met_more_than_80

awards_won

avg_training_score

⚙️ Methodology

Data preprocessing and handling missing values

Hierarchical Clustering using Ward’s method

Visualizing clusters with a dendrogram

Profiling each cluster based on performance features

Exporting and analyzing cluster results for insights

🔍 Insights

Cluster 1: Low KPI scores, fewer trainings — may need development programs

Cluster 2: Moderate performance — potential for upskilling

Cluster 3: High KPI scores and ratings — top performers and potential mentors

🧠 Future Scope

Implement predictive models (e.g., Random Forest, XGBoost) to forecast future employee performance.

Automate cluster labeling and dashboard visualization for HR analytics.

💻 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

📁 Output

Final clustered dataset exported as:
Hierarchical_Clustering_Output.csv
