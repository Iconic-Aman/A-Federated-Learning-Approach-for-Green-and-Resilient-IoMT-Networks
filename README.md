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
- **Dataset**: [MHEALTH Dataset](https://archive.ics.uci.edu/static/public/319/mhealth+dataset.zip)  
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
| **Decision Tree** | [🔗 Link](https://drive.google.com/file/d/1ttDMWIfSUdGjcNArtvUyV82hQ1FdaBvv/view?usp=sharing) |  
| **Neural Network (MLP)** | [🔗 Link](https://drive.google.com/file/d/1jMG7m1hdv5wRS649D5mDuLO7wHRoKAPh/view?usp=drive_link) |  
| **Support Vector Machine (SVM)** | [🔗 Link](https://drive.google.com/file/d/1Pze84BQsqeZoibPOnzy4k5APISvmQ1Tr/view?usp=sharing) |  
| **Random Forest** | [🔗 Link](https://drive.google.com/file/d/1t6DTyV1Rcbh65Ufz274C8a72jxuITzu-/view?usp=drive_link) |  

## 📡 Performance on Different Networks  
- **WiFi (100 Mbps)** → [🔗 Colab](https://drive.google.com/file/d/1uuoAS-rFHHeqk4Kgas4HJWvIVJ5LQO0A/view?usp=drive_link)  
- **5G (500 Mbps)** → [🔗 Colab](https://drive.google.com/file/d/1qLsk8wXfSIgyjvIsJ_I_vH5-0WMzIgGS/view?usp=drive_link)  
- **4G (20 Mbps)** → [🔗 Colab](https://drive.google.com/file/d/1ICaoKqLmWeg5Fkv0Tq3RgSoweYsdi89f/view?usp=drive_link)  
- **Bluetooth (2 Mbps)** → [🔗 Colab](https://drive.google.com/file/d/1t6DTyV1Rcbh65Ufz274C8a72jxuITzu-/view?usp=drive_link)  

## 🔮 Future Work  
- Testing on **other medical datasets** for better generalization  
- Running the FL framework on a **distributed computing setup**  
- Exploring **deep learning-based FL models** for IoMT  

## 🏫 Research & Contributors  
**Team Members (Group 21, IIIT Kottayam)**  
- **Aman Kumar Srivas
