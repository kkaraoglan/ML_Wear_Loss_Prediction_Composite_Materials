# The Comparative Evaluation of the Wear Behavior of Epoxy Matrix Hybrid Nano-Composites via Experiments and Machine Learning Models

**Authors:**  
Fatih Aydın¹²*, Kürşat Mustafa Karaoğlan³, Hatice Yakut Pektürk⁴, Bilge Demir⁵, Volkan Karakurt⁶, Hayrettin Ahlatçı⁷

**Abstract**
This study evaluated the wear behavior of multiwall carbon nanotube (MWCNT) doped non-crimp fabric carbon fiber reinforced polymer (NCF-CFRP) composites produced through vac-uum infusion. Compared to 0 wt% MWCNT reinforced composite, the wear loss of 1 wt% MWCNT reinforced composite under loads of 10N and 30N decreased by 48.1% and 61.1%, respectively, for sliding distance of 1000 m.  Additionally, the study evaluated various Ma-chine Learning models including Deep Multi-Layer Perceptron (DMLP), Random Forest Re-gression, Gradient Boosting Regression, Linear Regression (LR), and Polynomial Regression for predicting wear loss. The DMLP model exhibited enhanced predictive capabilities in the testing phase (R²=0.9726) compared to its training performance (R²=0.9531), while the LR model maintained stable performance characteristics between training (R²=0.9712) and testing (R²=0.9454) phases.

**Keywords:** Machine learning, Wear loss prediction, Quadriaxial non-crimp fabric, Carbon fiber, MWCNT, Wear behavior.

## Overview

Predicting Wear Behavior of NCF-CFRP Composites using Machine Learning
This repository presents a pioneering application of machine learning techniques for predicting the wear behavior of multiwall carbon nanotube (MWCNT) doped non-crimp fabric carbon fiber reinforced polymer (NCF-CFRP) composites. Our study introduces the first implementation of Deep Multi-Layer Perceptron (DMLP) modeling in this domain, marking a significant advancement in composite materials research.
Key Findings
Our DMLP model achieved superior predictive performance with R²=0.9726 in the testing phase
1 wt% MWCNT reinforced composites demonstrated:
48.1% reduction in wear loss under 10N load
61.1% reduction in wear loss under 30N load
for a sliding distance of 1000 m

**Implemented Models:**
Deep Multi-Layer Perceptron (DMLP)
Random Forest Regression
Gradient Boosting Regression
Linear Regression
Polynomial Regression

**Model Evaluation Metrics**
R² (Coefficient of Determination)
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Square Error)
MAPE (Mean Absolute Percentage Error)

## Dataset
Datasets are shared both in the manuscript and in this repo. They cannot be used without reference.

## Code
All code is shared in this repo. DMLP and other ML models are shared as separate codes. Do not use without permission without citing the source.

Contributing
Please open an issue first to discuss what you would like to change before making any contributions.
Contact
kkaraoglan@karabuk.edu.tr
Citation
If you use this work in your research, please cite:
Soon

## Project Owners and Contributors

### Project Owners:
  **Kürşat Mustafa Karaoğlan**  
  Department of Computer Engineering, Karabuk University, Karabuk, Turkey
  Email: [kkaraoglan@karabuk.edu.tr](mailto:fatih.aydin@karabuk.edu.tr)
  
- **Fatih Aydın**  
  TOBB Vocational School of Technical Sciences, Karabuk University, Karabuk, Turkey  
  Email: [fatih.aydin@karabuk.edu.tr](mailto:fatih.aydin@karabuk.edu.tr)

 

### Contributors:
-

- **Hatice Yakut Pektürk**  
  Department of Mechanical Engineering, Kırklareli University, Kırklareli, Turkey

- **Bilge Demir**  
  Department of Mechanical Engineering, Karabuk University, Karabuk, Turkey

- **Volkan Karakurt**  
  Sağlam Metal San. ve Tic. A.Ş, Kocaeli, Turkey

- **Hayrettin Ahlatçı**  
  Department of Metallurgical and Materials Engineering, Karabuk University, Karabuk, Turkey

### License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


# Wear Loss Prediction Using DMLP with Early Stopping

This project demonstrates the use of a Multilayer Perceptron (MLP) neural network for predicting wear loss under different load conditions during training. It uses early stopping to prevent overfitting and to improve the model's generalization capabilities.

## Project Overview
This project aims to predict wear loss under three different load conditions (30N, 20N, and 10N) using machine learning techniques. The MLP model is built using Keras, with dropout layers for regularization and early stopping to halt training when the validation loss stops improving.

### Key Features:
The model employs a feedforward neural network where the number of hidden layers, nodes per layer, and hyperparameters were dynamically optimized through GridSearchCV. The architecture incorporates early stopping with optimized patience values to halt training when validation loss stagnates, and dropout regularization with tuned rates to prevent overfitting. Similarly, for Polynomial Regression, polynomial degrees were dynamically selected based on data characteristics and model performance metrics rather than using fixed values.

## Installation

To run this project, you will need the following Python libraries:

- `pandas`
- `scikit-learn`
- `keras`
- `matplotlib`
- `numpy`

You can install the required packages via pip:
```bash
pip install pandas scikit-learn keras matplotlib numpy


## Note

This work is currently under review, and the datasets and all codes will be shared following the publication of the manuscript.
