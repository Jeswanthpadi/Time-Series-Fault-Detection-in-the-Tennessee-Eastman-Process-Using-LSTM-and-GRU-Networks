# Time-Series-Fault-Detection-in-the-Tennessee-Eastman-Process-Using-LSTM-and-GRU-Networks

Overview

This project focuses on detecting and classifying process faults in the Tennessee Eastman Process (TEP) using deep learning techniques. The goal is to build reliable models that can identify abnormal operating conditions early, improving plant safety and operational efficiency.

Objective
1. Develop fault detection and classification models using LSTM and GRU networks.
2. Analyze time-series process data to capture complex dependencies between sensor variables.
3. Compare model performance in terms of accuracy, precision, recall, and computational efficiency.
4. Use explainable AI (LIME) to understand which process variables influence the predictions the most.

Dataset

The project uses the Tennessee Eastman Process (TEP) dataset, a benchmark for industrial fault detection.
It includes:

A) 52 process variables (sensors and manipulated variables)
B) 21 predefined fault types
C) Normal and fault operation time-series data

Methodology

1. Data Preprocessing – Cleaning, scaling, and reshaping time-series data for model training.
2. Model Development – Building and training LSTM and GRU networks.
3. Evaluation – Comparing both models using metrics like Accuracy, Precision, Recall, and F1-Score.
4. Explainability – Applying LIME to interpret model predictions and identify key influencing variables.
5. Workflow – The project follows the CRISP-DM framework for systematic development.

Results

1. GRU achieved slightly higher performance with an accuracy of 89.7%.
2. LSTM performed competitively but required more training time.

LIME analysis revealed that features like reactor pressure and feed flow rate had the strongest impact on fault prediction.

Conclusion

Both LSTM and GRU networks proved effective for detecting and diagnosing faults in industrial processes. GRU demonstrated better computational efficiency, making it suitable for real-time monitoring. The integration of explainable AI methods enhances model transparency and supports informed decision-making in process control environments.
