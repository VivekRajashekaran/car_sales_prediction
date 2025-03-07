# car_sales_prediction
# Car Sales Price Prediction

## Overview
This project focuses on predicting car sales prices using machine learning techniques. The goal is to develop a model that accurately estimates the selling price of a car based on various factors such as brand, year of manufacture, fuel type, transmission type, mileage, and more.

## Dataset
The dataset consists of historical car sales data, including attributes such as:
- Car Brand and Model
- Manufacturing Year
- Mileage
- Fuel Type (Petrol, Diesel, CNG, Electric, etc.)
- Transmission Type (Manual, Automatic)
- Number of Owners
- Engine and Power Specifications
- Selling Price (Target Variable)

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Machine Learning Models:**
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - XGBoost
  - Support Vector Machine (SVM)

## Project Structure
```
├── data
│   ├── car_sales.csv (Dataset)
│   ├── processed_data.csv (Preprocessed Dataset)
├── notebooks
│   ├── data_exploration.ipynb (EDA & Data Cleaning)
│   ├── model_training.ipynb (Model Development & Evaluation)
├── models
│   ├── trained_model.pkl (Saved Model)
├── src
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── model_evaluation.py
├── README.md (Project Documentation)
├── requirements.txt (Dependencies)
└── app.py (Streamlit Web App for Prediction)
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-sales-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-sales-price-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook for model training:
   ```bash
   jupyter notebook notebooks/model_training.ipynb
   ```

## Model Evaluation
The models were evaluated using the following metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

## Results
| Model                  | MAE  | MSE  | R² Score |
|------------------------|------|------|----------|
| Linear Regression      | 1.8  | 4.2  | 0.85     |
| Decision Tree         | 1.2  | 2.8  | 0.90     |
| Random Forest         | 1.0  | 2.2  | 0.92     |
| XGBoost               | 0.9  | 2.0  | 0.94     |

## Deployment
The trained model can be deployed as a **Streamlit Web App**:
```bash
streamlit run app.py
```

## Contributing
If you want to contribute to this project, follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or issues, please reach out:
- **Author:** Vivek R
- **Email:** [vivekrajashekaran2312@gmail.com](mailto:vivekrajashekaran2312@gmail.com)
- **LinkedIn:** [linkedin.com/in/vivek-r-752469247](https://linkedin.com/in/vivek-r-752469247)
- **GitHub:** [github.com/VivekRajashekaran](https://github.com/VivekRajashekaran)
