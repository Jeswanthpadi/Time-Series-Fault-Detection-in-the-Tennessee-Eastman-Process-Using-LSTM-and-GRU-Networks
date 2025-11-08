# Time-Series-Fault-Detection-in-the-Tennessee-Eastman-Process-Using-LSTM-and-GRU-Networks

Overview

This project focuses on detecting and classifying process faults in the Tennessee Eastman Process (TEP) using deep learning techniques. The goal is to build reliable models that can identify abnormal operating conditions early, improving plant safety and operational efficiency.

Objective

Develop fault detection and classification models using LSTM and GRU networks.

Analyze time-series process data to capture complex dependencies between sensor variables.

Compare model performance in terms of accuracy, precision, recall, and computational efficiency.

Use explainable AI (LIME) to understand which process variables influence the predictions the most.

Dataset

The project uses the Tennessee Eastman Process (TEP) dataset, a benchmark for industrial fault detection.
It includes:

52 process variables (sensors and manipulated variables)

21 predefined fault types

Normal and fault operation time-series data

Methodology

Data Preprocessing – Cleaning, scaling, and reshaping time-series data for model training.

Model Development – Building and training LSTM and GRU networks.

Evaluation – Comparing both models using metrics like Accuracy, Precision, Recall, and F1-Score.

Explainability – Applying LIME to interpret model predictions and identify key influencing variables.

Workflow – The project follows the CRISP-DM framework for systematic development.

Results

GRU achieved slightly higher performance with an accuracy of 89.7%.

LSTM performed competitively but required more training time.

LIME analysis revealed that features like reactor pressure and feed flow rate had the strongest impact on fault prediction.

Conclusion

Both LSTM and GRU networks proved effective for detecting and diagnosing faults in industrial processes. GRU demonstrated better computational efficiency, making it suitable for real-time monitoring. The integration of explainable AI methods enhances model transparency and supports informed decision-making in process control environments.
