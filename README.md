# Network_intrusion_Detection
This project is Created using IBM's cloud platform using No-code Machine Learning Tool provided by IBM ,

## 📌 Problem Statement

Communication networks are increasingly vulnerable to cyber-attacks such as DoS, Probe, R2L, and U2R. Early detection of intrusions is critical to maintaining network integrity and preventing data breaches. This project aims to build a machine learning model that can analyze network traffic and classify activity as normal or potentially malicious.

---
## 📈Progess Map

![Progress Map Image](Screenshot (21).png)

---

## 🚀 Features

- Uses IBM Cloud Watson Studio AutoAI (no-code ML)
- Trained on Kaggle's [Network Intrusion Detection dataset](https://www.kaggle.com/datasets/sampadab17/networkintrusion-detection)
- Deployed as a REST API for real-time inference
- Includes browser-based frontend (HTML + JS) to test predictions
- Prediction classes: `normal` or `anomaly`

---

## 🧠 Machine Learning Model

- Tool: **IBM Watson AutoAI**
- Algorithm: **Snap Decision Tree Classifier**
- Accuracy: **99.5%**
- Input Features: 41 (e.g., protocol_type, service, src_bytes, dst_bytes, etc.)
- Prediction: Binary classification (`normal` or `anomaly`)

---

## 📚 References
Kaggle Dataset: https://www.kaggle.com/datasets/sampadab17/networkintrusion-detection

IBM AutoAI Docs: https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/autoai-overview.html

