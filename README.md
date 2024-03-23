Breast Cancer Classification with CNN and ResNet
This project aims to classify breast cancer using Convolutional Neural Networks (CNN) and ResNet, comparing their performance based on accuracy, recall, F1-score, precision, and Area Under the Curve (AUC) of the Receiver Operating Characteristic (ROC) curve.

Overview
Breast cancer is a prevalent form of cancer among women worldwide. Early detection is crucial for effective treatment. Machine learning techniques, particularly deep learning models, have shown promising results in automating the detection and classification of breast cancer from medical images.

In this project, I employ CNN and ResNet architectures to classify breast cancer from mammogram images. I evaluate the performance of both models using various metrics to determine their effectiveness in accurately diagnosing breast cancer.

Dataset
I utilize the Breast Cancer Histopathological Database for training and evaluation. This dataset consists of high-resolution histopathological images of breast tissue samples labeled with cancerous and non-cancerous regions.

Model Architecture
CNN: I design a convolutional neural network architecture tailored for breast cancer classification. The CNN comprises multiple convolutional and pooling layers followed by fully connected layers for classification.

ResNet: I leverage the Residual Neural Network (ResNet) architecture, known for its deep structure and skip connections, which facilitate training of very deep networks. I use a pre-trained ResNet model and fine-tune it for breast cancer classification.

Evaluation Metrics
I assess the performance of both CNN and ResNet models using the following metrics:

Accuracy: Overall accuracy of the model in correctly classifying cancerous and non-cancerous samples.
Recall: Proportion of actual positive cases correctly identified by the model.
Precision: Proportion of predicted positive cases that are correctly classified.
F1-score: Harmonic mean of precision and recall, providing a balanced measure between the two.
Area Under the ROC Curve (AUC): Measure of the model's ability to distinguish between positive and negative classes across various thresholds.
Results
I present the comparative performance of CNN and ResNet models in terms of the aforementioned metrics. Additionally, I visualize the ROC curves to demonstrate the trade-off between true positive rate and false positive rate for both models.


Acknowledgements
I acknowledge the Breast Cancer Histopathological Database for providing the dataset used in this project.
