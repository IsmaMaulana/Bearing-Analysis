# Bearing Diagnostic Using Machine Learning ⚙️📊

<h1>Bearing Analysis using HUST bearing: a practical dataset for ball bearing fault diagnosis</h1>

<h2>Project Overview</h2>
This study presents a practical approach to ball bearing fault diagnosis using the HUST (Huazhong University of Science and Technology) bearing dataset, which contains vibration signal data from various bearing health conditions. The objective is to accurately classify different types of bearing faults — such as inner race faults, outer race faults, and ball defects — as well as distinguish them from normal operational conditions.

A Decision Tree algorithm is employed as the core machine learning model due to its interpretability and efficiency in handling classification problems with labeled data. Prior to model training, signal preprocessing and feature extraction are conducted using statistical time-domain features such as RMS, standard deviation, kurtosis, and skewness. These features are used as input variables for the classifier.

The Decision Tree model is trained and tested using a portion of the dataset, with performance evaluated through accuracy, confusion matrix, and classification report metrics. The results demonstrate the model’s capability in distinguishing bearing faults with satisfactory accuracy, making it a practical tool for predictive maintenance in rotating machinery.

This approach provides a low-complexity yet effective diagnostic framework that can be integrated into real-time monitoring systems, especially in industrial environments where interpretability and fast decision-making are crucial.

<h2>Key Features</h2>

<b>✅ Real-Time Condition Monitoring – Capable of identifying various types of bearing faults using vibration signals.</b>

<b>✅ Interpretable Model – Decision Tree provides clear diagnostic paths, making fault classification transparent and traceable.</b>

<b>✅ Feature Extraction & Selection – Combines Ensemble Empirical Mode Decomposition (EEMD) and Distance Evaluation Technique (DET) for optimal input features.</b>

<b>✅ MATLAB-Based Implementation – All processing stages including feature extraction, training, and testing are carried out in MATLAB.</b>

<b>✅ Multi-Speed Testing – Evaluated under different shaft speeds (e.g., 500 RPM, 1000 RPM, 1500 RPM) to ensure robustness across conditions.</b>

<h2>Development Process</h2>
<b>1️⃣ Data Collection – Vibration signals obtained from accelerometers mounted on bearing housings with various fault types and severities.</b>

<b>2️⃣ Signal Processing – Applied both time-domain and frequency-domain techniques to extract informative statistical features.</b>

<b>3️⃣ Feature Selection – EEMD and DET used to reduce dimensionality and retain only relevant indicators for classification.</b>

<b>4️⃣ Machine Learning Model – Decision Tree classifier trained to distinguish between healthy and faulty bearing conditions (inner race, outer race, ball fault).</b>

<b>5️⃣ Model Evaluation – Performance assessed using accuracy, confusion matrix, precision, recall, and F1-score.</b>

<h2>Results & Impact</h2>
<b>🚀 Achieved average classification accuracy of 98.12%, validating the effectiveness of Decision Tree for bearing fault diagnosis.</b>

<b>🚀 Transparent decision rules allow easier implementation and trust in industrial diagnostic systems.</b>

<b>🚀 Helps reduce downtime and extends equipment life through early fault detection and targeted maintenance.</b>

<h2>Future Improvements</h2>
<b>🔹 Integration with wireless IoT sensors for real-time bearing health monitoring.</b>

<b>🔹 Extension to detect compound bearing faults and other rotating component failures.</b>

<p align="center">
Scatter Plot of Decision Tree Model: <br/>
<img src="https://i.imgur.com/toBCfUa.png" height="80%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confusion Matrix Using Decision Tree Model:  <br/>
<img src="https://i.imgur.com/lRcz0vG.png" height="80%" width="50%" alt="Disk Sanitization Steps"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
