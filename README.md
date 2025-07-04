# milling-fault-diagnosis-ae-hybrid-dl
Supplementary material and code for the paper.

# Milling machine fault diagnosis using acoustic emission and hybrid deep learning with feature optimization

This repository contains code, results, and supplementary material for the paper:

**Milling Machine Fault Diagnosis Using Acoustic Emission and Hybrid Deep Learning With Feature Optimization**  
Published in *MDPI Applied Sciences*
[Link to the paper](https://www.mdpi.com/2076-3417/14/22/10404)  

## 📌 Abstract
This paper presents a fault diagnosis technique for milling machines based on acoustic emission (AE) signals and a hybrid deep learning model optimized with a genetic algorithm. Mechanical failures in milling machines, particularly in critical components like cutting tools, gears, and bearings, account for a significant portion of operational breakdowns, leading to unplanned downtime and financial losses. To address this issue, the proposed method first acquires AE signals from the milling machine. AE signals, capturing the dynamic responses of machine components, are transformed into continuous wavelet transform (CWT) scalograms for further analysis. Gaussian filtering is applied to enhance the clarity of these scalograms, effectively reducing noise while maintaining essential features. A convolutional neural network (CNN) based on the VGG16 architecture is utilized for spatial feature extraction, followed by a bidirectional long short-term memory (BiLSTM) network to capture the temporal dependencies of the scalograms. The genetic algorithm (GA) is used to optimize feature selection and ensure the selection of the most relevant features to further improve the model’s performance. The optimized features are finally fed into a fully connected (FC) layer of the proposed hybrid model for fault classification. The proposed method achieves an accuracy of 99.6%, significantly outperforming traditional approaches. This method offers a highly accurate and efficient solution for fault detection in milling machines, allowing for more reliable predictive maintenance and operational efficiency in industrial settings.

