# Diabetes Prediction Model 

This repository contains a machine learning-based diabetes prediction model using scikit-learn's built-in `load_diabetes` dataset. The model utilizes ensemble techniques such as Random Forest, Decision Tree, and Gradient Boosting to predict diabetes progression. Key evaluation metrics, including accuracy and error, are calculated and cross-validated using RandomizedSearchCV.

---

## Features
- Implementation of multiple ensemble techniques:
  - **Random Forest**
  - **Decision Tree**
  - **Gradient Boosting**
- Cross-validation using **RandomizedSearchCV**.
- Performance metrics such as:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

## Dataset
The model uses the `load_diabetes` dataset from scikit-learn, which contains:
- Features: Age, Sex, BMI, Blood Pressure, and 6 blood serum measurements.
- Target: A quantitative measure of disease progression one year after baseline.

---

## Requirements
Install the required libraries using:
```bash
pip install -r requirements.txt
```
### Libraries Used:
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## Model Development Workflow
1. **Data Loading and Preprocessing**:
   - Load the `load_diabetes` dataset using scikit-learn.
   - Feature scaling and splitting the dataset into training and test sets.

2. **Model Training**:
   - Train individual models (Random Forest, Decision Tree, Gradient Boosting).
   - Tune hyperparameters using RandomizedSearchCV.

3. **Evaluation**:
   - Compute metrics for each model (MAE, MSE, RMSE, R² Score).
   - Perform cross-validation to ensure generalization.

4. **Comparison**:
   - Analyze and compare the performance of models.

---

## Results
| Model               | RMSE   | MAE    | R² Score |
|---------------------|--------|--------|----------|
| Random Forest       | 42.5877| 36.0873| XX.XX    |
| Decision Tree       | XX.XX  | XX.XX  | XX.XX    |
| Gradient Boosting   | XX.XX  | XX.XX  | XX.XX    |

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd diabetes-prediction
   ```
3. Run the main script:
   ```bash
   python main.py
   ```

---

## Future Work
- Expand the model to handle additional datasets.
- Integrate a web-based interface using React.js for the frontend and Django/Flask for the backend.
- Deploy the model as a REST API.

---

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to get started.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- The `load_diabetes` dataset from scikit-learn.
- Inspiration from various ensemble techniques and machine learning resources.

---




