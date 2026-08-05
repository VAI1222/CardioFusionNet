# CardioFusionNet
Cardiovascular diseases are a major cause of death worldwide. This paper introduces two related 
systems for analysing cardiac signals automatically. The first system uses 1D CNN to classify arrhythmias based 
on ECG signals from the MIT-BIH Arrhythmia Database. It applies beat-level segmentation, Butterworth 
bandpass filtering, and AAMI-standard class mapping. The trained model reaches an overall accuracy of 97% 
and an average F1 score of 0.81 . The second system suggests a multimodal anomaly detection pipeline. It 
combines statistical features from synchronized (ECG) and phonocardiogram (PCG) signal windows. It uses 
Isolation Forest to generate unsupervised pseudo-labels. Then, a tuned XGBoost classifier with probability 
thresholds achieves 98.24% accuracy and a binary F1 score of 94.22%.A window-based cardiac risk scoring 
method is proposed to help with continuous patient monitoring. These systems show that both deep learning 
and machine learning methods can effectively analyze cardiac signals. They have real-world applications for 
detecting arrhythmias in real time and for monitoring heart health using multiple modalities.
