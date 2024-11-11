# The Comparative Evaluation of the Wear Behavior of Epoxy Matrix Hybrid Nano-Composites via Experiments and Machine Learning Models

**Authors:**  
Fatih Aydın¹²*, Kürşat Mustafa Karaoğlan³, Hatice Yakut Pektürk⁴, Bilge Demir⁵, Volkan Karakurt⁶, Hayrettin Ahlatçı⁷

## Overview

This repository contains the code and methodologies used for the comparative evaluation of the wear behavior of epoxy matrix hybrid nano-composites. The study employs various machine learning models, including Deep Multi-Layer Perceptron, Random Forest, Gradient Boosting, Linear Regression, and Polynomial Regression, to predict wear loss accurately. The performance of these models is evaluated using metrics such as R², MAE, MSE, RMSE, and MAPE, aiming to optimize time and cost in tribological assessments.

## Study Summary

This study aims to evaluate the wear behavior of multiwall carbon nanotube (MWCNT) doped non-crip fabric-carbon fiber reinforced polymer (NCF-CFRP) hybrid composites produced through vacuum infusion experiments and to model these experiments using Machine Learning (ML) techniques. Predicting wear behavior is crucial for understanding and optimizing complex tribological mechanisms. Due to the lengthy and costly nature of tribological testing, ML approaches are vital for predicting wear behavior and identifying system anomalies in advance.

Various ML methods, including Deep Multi-Layer Perceptron, Random Forest Regression, Gradient Boosting, Linear Regression, and Polynomial Regression, were utilized to predict wear loss. All models achieved performance values above 92%, with the highest results from Linear Regression and Deep Multi-Layer Perceptron exceeding 99%. These models optimize the time and cost required for experimental studies while providing highly accurate predictions of wear characteristics, offering a new perspective on the tribological characterization of MWCNT-doped NCF-CFRP composites.

## Dataset

The datasets used in this study will be made publicly available upon publication of the manuscript.

## Code

All code implementations utilized in this research will also be shared after the publication of the article.

## Project Owners and Contributors

### Project Owners:
- **Fatih Aydın**  
  TOBB Vocational School of Technical Sciences, Karabuk University, Karabuk, Turkey  
  Email: [fatih.aydin@karabuk.edu.tr](mailto:fatih.aydin@karabuk.edu.tr)

### Contributors:
- **Kürşat Mustafa Karaoğlan**  
  Department of Computer Engineering, Karabuk University, Karabuk, Turkey

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


# Wear Loss Prediction Using MLP with Early Stopping

This project demonstrates the use of a Multilayer Perceptron (MLP) neural network for predicting wear loss under different load conditions during training. It uses early stopping to prevent overfitting and to improve the model's generalization capabilities.

## Project Overview
This project aims to predict wear loss under three different load conditions (30N, 20N, and 10N) using machine learning techniques. The MLP model is built using Keras, with dropout layers for regularization and early stopping to halt training when the validation loss stops improving.

### Key Features:
- **MLP Architecture**: The model uses a feedforward neural network with five hidden layers.
- **Early Stopping**: Training is halted when the validation loss does not improve after a specified number of epochs (patience).
- **Dropout**: A dropout regularization technique is employed to prevent overfitting.

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
