# car_object_detection
Bounding box car detector using CNN

# 🚗 Car Object Detection using CNN

This project uses a custom Convolutional Neural Network (CNN) to detect cars and predict bounding boxes in grayscale images.

---

## 📌 Project Overview

- Trains a CNN on car images to detect and localize objects
- Input: Grayscale images resized to 380x676
- Output: Bounding box coordinates `[xmin, ymin, xmax, ymax]`
- Implemented using TensorFlow/Keras
- Includes real-time prediction and visualization

---

## 🧠 Model Summary

- 2 convolutional layers with ReLU + MaxPooling
- Flatten + Dense layers with Dropout
- Final Dense layer (4 units, linear activation)
- Loss: MAE (mean absolute error)
- Optimizer: Adam

---

## 🧪 Example Predictions

Here are some example prediction images showing bounding boxes:

![Prediction Example 1](images/prediction1.png)

*Red box = Predicted bounding box*  
*Green box = Ground truth bounding box*

![Prediction Example 2](images/prediction2.png)

---

## 🔧 How to Run

1. Clone the repository or download the notebook:

   ```bash
   git clone https://github.com/ArevikMatinyan/car_object_detection.git
---

## 📁 Files

| File | Description |
|------|-------------|
| `car_object_detection.ipynb` | Main notebook with model training and prediction |
| `README.md` | This file |
| `requirements.txt` (optional) | Python dependencies |
| `model.h5` (optional) | Saved trained model |
| `test_predictions.csv` (optional) | Output predictions on test images |

---

## 🧪 Example Prediction

![Car Image](https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Car_detection_example.jpg/640px-Car_detection_example.jpg)
---


## 🔧 How to Run

1. Prepare your data:

2. Open `car_object_detection.ipynb` and run all cells

3. Adjust paths if needed and visualize prediction results

---
