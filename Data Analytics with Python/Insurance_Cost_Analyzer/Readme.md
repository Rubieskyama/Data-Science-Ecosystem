# Medical Charge Prediction Model

## 🎯 Overview
This project focuses on predicting medical insurance charges using historical patient data. By employing data preprocessing techniques and comparative regression analysis, I developed a predictive model that achieves an R² score of 0.85, providing insights into the primary attributes affecting healthcare costs.

## 🛠 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Techniques:** Exploratory Data Analysis (EDA), Data Cleaning, Linear Regression, Ridge Regression (Regularization)

## 📊 Key Achievements
* **Data Engineering:** Cleaned and preprocessed raw datasets to handle missing values and inconsistent entries, ensuring high-quality model input.
* **Insights:** Conducted thorough EDA to identify significant correlations between patient attributes (e.g., BMI, smoking status, age) and insurance charges.
* **Modeling:** Built and compared multiple regression architectures.
* **Optimization:** Implemented Ridge Regression to address multicollinearity and improve model generalization, resulting in a final R² score of 0.85.

## 📂 Project Structure
* `data/`: Contains the raw and cleaned datasets.
* `notebooks/`: Jupyter Notebooks detailing the step-by-step analysis and model development.
* `src/`: Cleaned Python scripts for data processing and model inference.

## 🚀 How to Run
1. Clone this repository: `git clone [your-repo-link]`
2. Install dependencies: `pip install -r requirements.txt`
3. Execute the model pipeline: `python src/model_pipeline.py`

## 💡 Key Learnings
This project strengthened my ability to handle real-world, "messy" data and demonstrated the importance of regularization (Ridge) in preventing overfitting when working with multi-variable linear models.
