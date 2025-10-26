#  Breast Cancer Classification with CNN and ResNet

This project aims to classify breast cancer using **Convolutional Neural Networks (CNN)** and **ResNet**, comparing their performance based on **accuracy**, **recall**, **F1-score**, **precision**, and **Area Under the Curve (AUC)** of the **Receiver Operating Characteristic (ROC)** curve.

---

##  Overview
Breast cancer is one of the most prevalent forms of cancer among women worldwide. **Early detection** is crucial for effective treatment and improved survival rates.  
Machine learning techniques, particularly **deep learning models**, have shown promising results in automating the detection and classification of breast cancer from medical images.

In this project, I employ **CNN** and **ResNet** architectures to classify breast cancer from mammogram images. The models are evaluated on multiple metrics to determine their effectiveness in accurately diagnosing breast cancer.

---

##  Dataset
I utilize the **Breast Cancer Histopathological Database (BreakHis)** for training and evaluation.  
This dataset consists of **high-resolution histopathological images** of breast tissue samples labeled with **cancerous** and **non-cancerous** regions.

---

##  Model Architecture

### 🔹 CNN
I design a custom **Convolutional Neural Network (CNN)** architecture tailored for breast cancer classification.  
The CNN comprises multiple **convolutional**, **activation**, and **pooling** layers, followed by **fully connected layers** for classification.

### 🔹 ResNet
I leverage the **Residual Neural Network (ResNet)** architecture, known for its **deep structure** and **skip connections**, which facilitate training of very deep networks.  
A **pre-trained ResNet model** is fine-tuned on the breast cancer dataset for optimized classification performance.

---

##  Evaluation Metrics
The performance of both CNN and ResNet models is evaluated using the following metrics:

- **Accuracy** – Overall proportion of correctly classified samples  
- **Recall** – Proportion of actual positive cases correctly identified  
- **Precision** – Proportion of predicted positive cases that are correct  
- **F1-score** – Harmonic mean of precision and recall  
- **AUC (ROC)** – Measure of the model's ability to distinguish between classes across various thresholds

---

##  Results
The comparative performance of **CNN** and **ResNet** models is analyzed based on the above metrics.  
ROC curves are plotted to visualize the **trade-off between true positive rate and false positive rate**, showcasing each model’s ability to discriminate between cancerous and non-cancerous samples.

---

##  Acknowledgements
I acknowledge the **Breast Cancer Histopathological Database (BreakHis)** for providing the dataset used in this project.



