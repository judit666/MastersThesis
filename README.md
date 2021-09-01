# Anomaly Detection in User Behaviour Logs on Streaming service Consumption Using Isolation Forest
This repository hosts the code for my Masters Thesis project. 

## 🖋️ Description
This code aims to detect anomalous behaviour in a company’s user logs with Isolation Forest method. Before choosing it as the final method for anomaly detection, it has been evaluated with the help of cross-scoring. Cross-scoring is an approach based on the multi-class classification that allows us to make user-based predictions by comparing one user to the
other users. This thesis has been written as part of an internship at Irdeto B.V. The data has been gathered by receiving events on an S3 bucket.

The data pipeline consists of the following steps:

- preprocess received data (including PCA)
- clean data
- prediction with Isolation Forest
- get anomalous events and users

### 💻 Built with
- sklearn

## 📙 References
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html

## 👤 Contact
- GitHub: judit666
- Linkedin: https://www.linkedin.com/in/juditgyorfi/
