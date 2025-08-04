# ML_Assignment2_ActionRecognition

Group project (3 members)

## Introduction
This project is the **second assignment** for the **Introduction to Machine Learning** course.  
The objective is to **reproduce and extend** the method from the paper:  
**"An Image Representation of Skeletal Data for Action Recognition Using Convolutional Neural Networks"**.  

The assignment focuses on:  
- **Human action recognition** using **pseudo-colored skeletal images**  
- **CNN model training, evaluation, and optimization**  
- **Cross-validation, data augmentation, and transfer learning**

---

## Project Overview
Key tasks include:

1. **Dataset Preparation & Model Training**  
   - Use the **PKU Action Dataset** (center camera)  
   - Train, validate, and test a **CNN** on pseudo-colored images  
   - Generate **training/validation loss & accuracy plots**

2. **Model Optimization**  
   - Address **underfitting/overfitting** using dropout, regularization, and architecture changes  
   - Experiment with activation functions and network modifications

3. **Model Evaluation**  
   - Compute **Confusion Matrix, Precision, Recall, and F1 Score**  
   - Perform **k-fold cross-validation**

4. **Data Augmentation**  
   - Apply **image rotations, zooming, and other transformations** to improve performance

5. **Cross-View Experiments**  
   - Train and test models across different **camera views (M, L, R)**

6. **Small Dataset & Transfer Learning**  
   - Train on a **limited dataset** to evaluate overfitting  
   - Apply **transfer learning** using the pre-trained PKU model  
   - Freeze layers, fine-tune, and compare results

Final deliverables include:  
- **Python scripts & Jupyter notebooks** for each task  
- **.h5 model files** for the trained CNNs  
- **Plots & result tables** with metrics similar to the reference paper

---
## Installation
1. Install **Python 3.x** and **pip**  
2. Install required libraries:  
   ```pip install keras tensorflow matplotlib numpy```
3. For GPU support:
``` pip install tensorflow[and-cuda] ```
---
**Requirements**
- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn for metrics and k-fold cross-validation
---
**Usage**
- Prepare the PKU Dataset and ensure the folder structure matches the scripts.
- Run training scripts to generate:
  - .h5 models
  - Training and validation plots
  - Evaluation metrics (confusion matrices, F1, precision, recall)
  - Perform cross-view, augmentation, and transfer learning experiments as instructed.
---
**Conclusion**
This assignment demonstrates:
1) CNN-based action recognition using skeletal image encoding
2) Model evaluation & optimization techniques
3) Cross-validation, data augmentation, and transfer learning for small datasets
   
The project serves as a practical exercise in deep learning for computer vision, combining implementation, analysis, and experimental reporting.
