# PredictHeartDisease

# Heart Disease Prediction

This project is focused on predicting the risk of developing heart disease within ten years using machine learning techniques. The dataset and the steps in this project are designed to explore and analyze factors contributing to cardiovascular health and provide a predictive model for early diagnosis and prevention.

## Dataset

The dataset used is the **Framingham Heart Study Dataset**, which includes the following features:
- Demographic data (e.g., age, gender)
- Health-related metrics (e.g., blood pressure, BMI, cholesterol levels)
- Behavioral factors (e.g., smoking status, cigarettes per day)
- Clinical history (e.g., diabetes, hypertension, stroke)

### Target Variable
- `TenYearCHD`: Binary indicator of whether the individual developed coronary heart disease within ten years.

## Project Workflow

1. **Data Collection**  
   The dataset is sourced from a publicly available repository.

2. **Data Preprocessing**  
   - Removing unnecessary columns (e.g., `education`).
   - Handling missing values and outliers.
   - Standardizing numeric features using `StandardScaler`.

3. **Exploratory Data Analysis (EDA)**  
   - Analyzing distributions of key features.
   - Exploring correlations between variables and the target.
   - Visualizing patterns using `matplotlib` and `seaborn`.

4. **Model Building**  
   - Models used include Logistic Regression, Random Forest, and Support Vector Machines (SVM).
   - Splitting the dataset into training and testing sets using `train_test_split`.
   - Hyperparameter tuning for optimal performance.

5. **Model Evaluation**  
   - Metrics used: Confusion Matrix, Classification Report, ROC Curve, and AUC score.

6. **Model Deployment**  
   - Saving the trained model using `joblib` for deployment or integration into applications.

## Libraries Used

- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Matplotlib & Seaborn**: Data visualization.
- **scikit-learn**: Machine learning algorithms and utilities.
- **joblib**: Model serialization.

## Usage

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or script:
   ```bash
   jupyter notebook Heart_Disease_Prediction.ipynb
   ```

## Results

The predictive models achieved the following performance (example metrics):
- **Logistic Regression**: AUC = 0.85
- **Random Forest**: AUC = 0.88
- **SVM**: AUC = 0.87

## Acknowledgments

The dataset is derived from the [Framingham Heart Study](https://www.framinghamheartstudy.org/). 

## License

This project is licensed under the MIT License.
