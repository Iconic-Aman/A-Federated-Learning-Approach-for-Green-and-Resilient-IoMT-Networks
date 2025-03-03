# A Federated Learning Approach for Green and Resilient IoMT Networks  

## 📌 Project Overview  
This project focuses on improving energy efficiency in the **Internet of Medical Things (IoMT)** using a **Federated Learning (FL) framework**. Our approach extends IoMT device lifespans, reduces energy consumption, and enhances sustainability while maintaining **data privacy** and **security**.  

## 🚀 Key Features  
- **Energy-aware Federated Learning** for IoMT devices  
- **Optimized data transmission & reduced computational load**  
- **Adaptive device clustering using K-medoids & Silhouette Index**  
- **Comparative analysis of ML models**: Decision Tree, Neural Networks, Random Forest, SVM  
- **Battery lifetime optimization & energy-efficient FL training**  

## 📊 Models Implemented  
- **Decision Tree** → Simple, interpretable, and energy-efficient  
- **Neural Network (MLP)** → Adaptive to resource constraints  
- **Random Forest** → Best balance of accuracy & energy efficiency  
- **Support Vector Machine (SVM)** → Robust but computationally heavy  

## 🔧 Experimental Setup  
- **Dataset**: [MHEALTH Dataset](https://archive.ics.uci.edu/dataset/319/mhealth+dataset)  
- **Features**: Motion & vital sign data from multiple sensors  
- **Metrics Evaluated**:  
  - **Accuracy vs. Energy Consumption**  
  - **Number of rounds to model convergence**  
  - **Performance across different communication protocols** (WiFi, 5G, 4G, Bluetooth)  

## 🏗️ System Workflow  
1. **Initial Clustering** of IoMT devices  
2. **Dynamic Re-clustering** based on energy constraints  
3. **Edge Device Evaluation** using performance & energy metrics  
4. **Selection of Representative Workers** for FL training  
5. **Local Model Updates** with energy-aware learning rate scheduling  
6. **Data Compression** (MessagePack) for efficient transmission  
7. **Global Model Aggregation** using Federated Averaging  

## 📌 Results & Insights  
- **Random Forest** achieves the best accuracy-energy trade-off  
- **Decision Trees & Neural Networks** are best for energy-limited devices  
- **SVM & SGD-based FL** consume more energy, making them less suitable  

## 📁 Code & Notebooks  
| Model | Colab Link |  
|--------|--------------------------------|  
| **Decision Tree** | [🔗 Link](https://colab.research.google.com/drive/1h9KKEpr4kGLB8c-7bvPM71kuB-l5GVtb?usp=sharing) |  
| **Neural Network (MLP)** | [🔗 Link](https://colab.research.google.com/drive/1qUbnWByD4EhkFGj07klxFYZy4POXpxYi?usp=sharing) |  
| **Support Vector Machine (SVM)** | [🔗 Link](https://colab.research.google.com/drive/1I4vTdeOuHo0t_TH8sKN-Lrb2fNKfwqqF) |  
| **Random Forest** | [🔗 Link](https://colab.research.google.com/drive/17bk8xCc-OW70KkKLaHSvXV7dI8lYkXWS?usp=sharing) |  

## 📡 Performance on Different Networks  
- **WiFi (100 Mbps)** → [🔗 Colab](https://colab.research.google.com/drive/1Pj5LZInNcmnaWbn1mQEsj_YsyIgUs_zw?usp=sharing)  
- **5G (500 Mbps)** → [🔗 Colab](https://colab.research.google.com/drive/1sw-G3JqWHOMjMYwrEiZb3VzfSsg1FAZw?usp=sharing)  
- **4G (20 Mbps)** → [🔗 Colab](https://colab.research.google.com/drive/1abtwJPq6vBrEOc3YQrjWPfyYJBYnKST1?usp=sharing)  
- **Bluetooth (2 Mbps)** → [🔗 Colab](https://colab.research.google.com/drive/1cxsxvSzJl4-uHTZKa4Kg3l5gQiCJD-B_?usp=sharing)  

## 🔮 Future Work  
- Testing on **other medical datasets** for better generalization  
- Running the FL framework on a **distributed computing setup**  
- Exploring **deep learning-based FL models** for IoMT  

## 🏫 Research & Contributors  
**Team Members (Group 21, IIIT Kottayam)**  
- **Aman Kumar Srivas
