# MNIST Digit Classification using Neural Network

## 📌 Project Overview

This project focuses on handwritten digit classification using the
**MNIST dataset** and a **Deep Learning Neural Network** built with
TensorFlow and Keras.

The model is trained to recognize handwritten digits from **0 to 9**.

## 📊 Dataset

The MNIST dataset contains:

-   **60,000** training images
-   **10,000** test images
-   Image size: **28 × 28 pixels**
-   Grayscale images
-   10 digit classes: **0--9**

## 🧠 Model Architecture

The neural network consists of:

-   Flatten layer: converts each 28×28 image into a 1D array
-   Dense layer: 50 neurons with ReLU activation
-   Dense layer: 50 neurons with ReLU activation
-   Output layer: 10 neurons with sigmoid activation

The model is compiled using:

-   **Optimizer:** Adam
-   **Loss Function:** Sparse Categorical Crossentropy
-   **Metric:** Accuracy

## ⚙️ Training

The model was trained for **10 epochs** on the MNIST training dataset.

### Results

-   **Training Accuracy:** 98.9%
-   **Test Accuracy:** 97.1%

## 📈 Model Evaluation

A **confusion matrix** was generated to visualize the model's
classification performance across all 10 digit classes.

## ✍️ Custom Digit Prediction

The project also includes a predictive system for a custom handwritten
digit image.

The input image is:

`3-digit.PNG`

The image is:

1.  Loaded using OpenCV
2.  Converted to grayscale
3.  Resized to 28×28 pixels
4.  Normalized
5.  Reshaped for the neural network
6.  Passed to the trained model for prediction

## 🛠️ Technologies Used

-   Python
-   NumPy
-   Matplotlib
-   Seaborn
-   OpenCV
-   Pillow
-   TensorFlow
-   Keras

## 📂 Project Files

``` text
MNIST-Digit-Classification-Neural-Network/
│
├── MNIST_Digit_Classification_Neural_Network.ipynb
├── 3-digit.PNG
├── README.md
├── requirements.txt
└── MNIST_Digit_Classification_Presentation.pptx
```

## 🚀 How to Run

1.  Open the Jupyter Notebook / Google Colab notebook.
2.  Upload `3-digit.PNG` when using the custom image prediction section.
3.  Run the notebook cells in order.
4.  The model will train on the MNIST dataset.
5.  Evaluate the model on the test dataset.
6.  Use the custom image prediction section to recognize a handwritten
    digit.

## 🎯 Project Outcome

The trained neural network achieved **97.1% accuracy on the test
dataset** and successfully demonstrates handwritten digit classification
using a basic deep learning approach.

## 👩‍💻 Author

**Priyanka Gunjal**

This project was completed as part of a Machine Learning / Deep Learning
project portfolio.
