# Climate-Risk-And-Disaster-Management

# 🌊 Leveraging Machine Learning for Flood Event Forecasting

This project aims to develop a robust machine learning-based system for forecasting flood events using historical rainfall data and other hydrological indicators. By leveraging predictive analytics, it helps improve early warning systems and disaster preparedness.

## 📌 Table of Contents
- [Features](#features)
- [Data Sources](#data-sources)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🚀 Features
- Predicts flood likelihood based on rainfall and environmental data
- Supports multiple machine learning models (Random Forest, XGBoost, LSTM)
- Visualizes rainfall trends and flood risk zones
- Modular pipeline for data preprocessing, training, and evaluation

## 🌧️ Data Sources
- Historical rainfall data (e.g., IMD, NOAA)
- River discharge and water level data
- Satellite imagery (optional)
- Ground truth flood event records

## 💻 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/flood-forecasting-ml.git
cd flood-forecasting-ml
pip install -r requirements.txt

🛠️ Usage
Run the pipeline with your dataset:
python main.py --data ./data/rainfall.csv --model random_forest

Or train a deep learning model:
python train_lstm.py --epochs 50 --data ./data/rainfall.csv


# 🌊 Leveraging Machine Learning for Flood Event Forecasting

This project aims to develop a robust machine learning-based system for forecasting flood events using historical rainfall data and other hydrological indicators. By leveraging predictive analytics, it helps improve early warning systems and disaster preparedness.


🛠️ Usage
Run the pipeline with your dataset:
python main.py --data ./data/rainfall.csv --model random_forest


Or train a deep learning model:
python train_lstm.py --epochs 50 --data ./data/rainfall.csv

🧠 Model Architecture

|Model          |Description                |Use Case                 |
_______________________________________________________________________
|Random Forest  |Ensemble tree-based model  |Fast, interpretable      | 
|XGBoost        |Gradient boosting          |High accuracy            | 
|LSTM           |Recurrent neural network   |Time-series forecasting  | 


📊 Results
- Accuracy: 92% (Random Forest)
- Precision: 89%
- Recall: 94%
- ROC-AUC: 0.96
Visualizations and confusion matrices are available in the results/ folder.

🤝 Contributing
We welcome contributions! Please fork the repo and submit a pull request. For major changes, open an issue first to discuss what you'd like to change.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🙋‍♀️ Contact
Created by Anahita
📧 Email: anahita.singh.31@gmail.com
🌐 LinkedIn: https://www.linkedin.com/in/anahita31/

-----



