# F1 2025 Champion Prediction

This project is a data-driven machine learning analysis aimed at predicting the potential 2025 Formula 1 World Champion. By leveraging historical race data, we use a combination of data science techniques and classification models to estimate which driver or team is most likely to win the 2025 title.

📌 Key Objectives
- Analyze historical Formula 1 data (driver stats, team performance, circuits, etc.)

- Preprocess and clean the raw dataset for ML readiness

- Engineer meaningful features (e.g., average qualifying position, podium rate, etc.)

- Visualize key insights to understand performance trends

- Train and evaluate classification models to predict the potential champion

🛠️ Tools and Technologies Used
- Python – Core language for data processing and modeling

- Jupyter Notebook – Interactive notebook environment for coding and visualization

- Pandas – For data manipulation and preprocessing

- Matplotlib / Seaborn – For data visualization and trend analysis

- Scikit-learn – For building and evaluating machine learning models

- NumPy – For numerical operations and array handling

🧪 Workflow Breakdown
- Data Collection
Historical race data was gathered (Kaggle datasets).
- Data Preprocessing
Cleaned missing values, unified formats, and filtered relevant seasons and drivers.
- Exploratory Data Analysis (EDA)
Visualized performance metrics like points, podiums, DNF rates, etc.
- Feature Engineering
Created new variables such as "form score", "track win rate", and "consistency index" to capture performance more effectively.
- Model Training and Evaluation
Applied classification models (e.g., Logistic Regression, Random Forest, Naive Bayes, KNN) to predict championship outcomes.
Evaluated using metrics like accuracy, precision, recall, and confusion matrix.
- Prediction for 2025 Season
Using trends and historical data, the model outputs a prediction for who is most likely to be the 2025 F1 Champion.

🎯 Outcome
This project showcases how machine learning can be used in sports analytics, particularly in predicting outcomes based on performance trends. It helps enthusiasts and analysts to quantify success factors and explore what makes a champion in Formula 1.

## 📁 Project Structure
- ├── data/=>Dataset (.csv)
- ├── models/=>Trained models (.pkl)
- ├── Internship_task_Final.ipynb =>Main notebook with full analysis
- ├── requirements.txt => List of required Python packages
- └── README.md =>Project documentation


## 📊 Features Used
- Lap statistics
- Weather and track data
- Pit stop strategy
- Driver behavior scores
- Race position and round information

## 📌 Models Implemented
- Logistic Regression
- Random Forest Classifier
- K-Nearest Neighbors
- Naive Bayes

Each model was evaluated using accuracy, F1-score, and confusion matrix.

## 📦 Requirements

Install all dependencies with:

```bash
pip install -r requirements.txt

💾 Saving and Loading Models
Trained models are saved using pickle in the models/ directory.

🚀 How to Run
1). Clone the repository:
git clone https://github.com/your-username/f1-2025-champion-prediction.git
2). Navigate into the folder:
cd f1-2025-champion-prediction
3). Install dependencies:
pip install -r requirements.txt
4). Open the notebook:
jupyter notebook Internship_task_Final.ipynb
```
📌 Author

Sohail — Artificial Intelligence Student

University: NUTECH, Pakistan
