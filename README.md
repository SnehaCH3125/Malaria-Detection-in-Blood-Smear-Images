# 🦠 Malaria Detection in Blood Smear Images

Malaria is a life-threatening disease caused by Plasmodium parasites, transmitted to humans through infected mosquito bites. Early and accurate detection of malaria is critical for effective treatment and management. This project uses deep learning to **automatically detect malaria-infected cells in blood smear images** with high accuracy.

## 🚀 Project Overview

- **Objective:** Classify blood smear images as **NEG** (uninfected with malaria) or **Trophozoite** (infected with malaria) and **WBC** using deep learning.
- **Dataset:** Publicly available dataset containing labeled images of parasitized and uninfected cells.
- **Approach:** Used **EfficientNetB0**, a powerful CNN architecture, fine-tuned with transfer learning for accurate and efficient classification.
- **Tools & Libraries:** Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib, Jupyter Notebook.


## 🧠 Key Features

- 📌 **Transfer Learning:** Leveraged pretrained EfficientNetB7 for high performance with less training data.
- 🧪 **Data Preprocessing:** Image resizing, normalization, and augmentation (rotation, flipping, zooming).
- 📈 **Visualization:** Training curves, and sample predictions for interpretability.

#### Clone the repository
     ```bash
    git clone https://github.com/SnehaCH3125/Malaria-Detection-in-Blood-Smear-Images.git
    cd Malaria-Detection-in-Blood-Smear-Images

#### Install the required libraries
     pip install -r requirements.txt

#### Open the Jupyter notebook
     jupyter notebook ML_Final_EfficientNetB0.ipynb

#### Run the cells and observe the model training and results.

#### 🧬 Sample Output
     <img src="images/sample_prediction.png" alt="Prediction" width="600"/>

#### 📌 Conclusion
This project demonstrates the effectiveness of transfer learning for medical image classification. With minimal domain-specific tuning, EfficientNetB7 successfully identifies malaria in blood smear images, providing a step toward AI-assisted diagnostics in healthcare.
