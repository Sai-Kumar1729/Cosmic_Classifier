# 🚀 Disaster Prediction using Target Encoding & XGBoost Optimization

## 📌 Overview
This repository contains a complete pipeline for disaster prediction using machine learning. The workflow includes data preprocessing, target encoding, hyperparameter tuning with Optuna, and model evaluation.

## 📂 Project Structure
```
📁 Disaster_Prediction
│-- 📄 code.ipynb          # Jupyter Notebook with full pipeline
│-- 📄 README.md           # Project documentation
│-- 📄 requirements.txt    # Dependencies for the project
│-- 📄 target_encoding.pkl # Stored encoding maps for test data
│-- 📁 data/               # Folder for dataset files
```

## 🛠️ Features
- **Target Encoding**: Uses K-Fold Target Encoding for categorical variables.
- **XGBoost Optimization**: Fine-tuned using Optuna for better accuracy.
- **Cross-validation**: Ensures robust model performance.
- **Exported Encoding Maps**: Enables consistent transformation for test data.

## 🔧 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Disaster_Prediction.git
   cd Disaster_Prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## 📊 Dataset
- The dataset consists of various disaster-related parameters.
- Ensure that the required dataset files are placed inside the `data/` folder before running the notebook.

## 🚀 Usage
1. **Preprocessing & Encoding**:
   - Encodes categorical features using K-Fold target encoding.
   - Saves encoding mappings (`target_encoding.pkl`) for consistency in test data.
2. **Hyperparameter Optimization**:
   - Uses Optuna to find the best XGBoost parameters.
   - Runs multiple trials to maximize model accuracy.
3. **Model Training & Evaluation**:
   - Trains the model with optimized parameters.
   - Evaluates on test data and provides predictions.

## 📌 Running the Notebook
Open `code.ipynb` in Jupyter Notebook and execute the cells in order.

## 🏆 Results
- The model achieves high accuracy using optimized parameters.
- Predictions are consistent across train and test datasets.

## 📌 Contributing
Pull requests are welcome. For major changes, open an issue first to discuss.

## 📄 License
This project is open-source and available under the MIT License.

---
🔥 If you find this useful, don’t forget to ⭐ the repository!

