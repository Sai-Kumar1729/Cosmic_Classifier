# 🚀 Plannet Classification using Target Encoding & XGBoost Optimization

## 📌 Overview
This repository contains a complete pipeline for Plannet Classification using machine learning. The workflow includes data preprocessing, target encoding, hyperparameter tuning with GridSearchCV, and model evaluation.

## 📂 Project Structure
```
📁 Plannet Classification
│-- 📄 code.ipynb          # Jupyter Notebook with full pipeline
│-- 📄 README.md           # Project documentation
│-- 📄 Documentation.ipynb #documentation of the project
│-- 📄 target_encoding.pkl # Stored encoding maps for test data
│-- 📁 data/               # Folder for dataset files
```

## 🛠️ Techniques
- **Target Encoding**: Uses K-Fold Target Encoding for categorical variables.
- **XGBoost Optimization**: Fine-tuned using Optuna for better accuracy.
- **Cross-validation**: Ensures robust model performance.
- **Exported Encoding Maps**: Enables consistent transformation for test data.

## 🔧 Installation
1. Clone the repository:
   ```sh
   [git clone //https://github.com/Sai-Kumar1729/Cosmic_Classifier.git)
   cd Disaster_Prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## 📊 Dataset
- The dataset consists of various planetory-related parameters.

-1. Atmospheric Density: Measure of the thickness of the planet's atmosphere (in kg/m³).
     
-2. Surface Temperature: Average surface temperature of the planet (in Kelvin).

-3. Gravity: Surface gravity of the planet (in m/s²).

-4. Water Content: Percentage of the planet's surface covered by water (0-100%).

-5. Mineral Abundance: Index representing the availability of valuable minerals (scale 0-1).

-6. Orbital Period: Time the planet takes to orbit its star (in Earth days).

-7. Proximity to Star: Distance from the planet to its star (in AU).

-8. Magnetic Field Strength: Measure of the planet's magnetic field (in Tesla).

-9. Radiation Levels: Average radiation levels on the planet's surface (in Sieverts/year).

-10. Atmospheric Composition Index: Index measuring the suitability of the atmosphere for human life (scale 0-1).


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

