# Crime Detection using LSTM with CLAHE

## Team Members

| Name            | Reg.No.   |
| --------------- | --------- |
| Abhinav LV      | 21BCE0192 |
| Ashwani Yadav   | 21BCE0231 |
| Anand Kumar Rai | 21BCE3803 |

## Abstract

Increased urbanization and the rising threat of criminal activities have led to the growing demand for automated surveillance systems capable of detecting suspicious behavior in real-time. The base work addresses this by leveraging multiple instance learning (MIL), and automatically learn a deep anomaly ranking model that predicts high anomaly scores for anomalous video segments. They also implemented sparsity and temporal smoothness constraints in the loss function to better localize anomaly during training, with an accuracy of 75.41%. However, challenges remain in improving detection accuracy, particularly under low-light conditions, such as nighttime surveillance.

This project builds upon the base model by incorporating several enhancements aimed at
improving performance and accuracy, especially in challenging lighting environments. We
introduce Contrast Limited Adaptive Histogram Equalization (CLAHE) as a preprocessing step to enhance video frames captured in low-light conditions, ensuring that important features are more visible to the model. Additionally, Batch Normalization layers are added after the convolutional layers to stabilize training and improve convergence, while Dropout layers are integrated to reduce overfitting and improve generalization.

With these enhancements, the model achieved a notable improvement in performance,
maintaining an accuracy of 97.39% across the test dataset, even in complex low-light scenarios. This outcome demonstrates the model’s robustness in detecting suspicious activities under varying lighting conditions, affirming the effectiveness of CLAHE, Batch Normalization, and Dropout as integral components of the framework. The refined model offers a practical solution for real-time surveillance applications, capable of delivering reliable detection accuracy in diverse environmental conditions.
