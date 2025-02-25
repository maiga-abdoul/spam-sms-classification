# SMS Spam Classification using Logistic Regression and Deep Learning  

## 📌 Overview  
This project focuses on **SMS spam classification** using two different approaches:  
✅ **Logistic Regression** (with TF-IDF vectorization)  
✅ **Deep Learning** (LSTM-based model with word embeddings)  

Since the dataset is **imbalanced**, we conduct experiments **twice for each model**:  
1️⃣ On the **imbalanced dataset**  
2️⃣ On the **balanced dataset** (using **undersampling**)  

## 📂 Dataset  
The dataset used in this project comes from the following publication:  
> **Almeida, T.A., Gómez Hidalgo, J.M., Yamakami, A.**  
> *Contributions to the Study of SMS Spam Filtering: New Collection and Results.*  
> Proceedings of the 2011 ACM Symposium on Document Engineering (DOCENG'11), Mountain View, CA, USA, 2011.  

📌 **Please cite the original authors if you use this dataset.**  

## 🛠️ Models & Methodology  
### 🔹 Models Used  
- **Logistic Regression** (TF-IDF vectorized text)  
- **Deep Learning Model** (LSTM-based with word embeddings)  

### 🔹 Data Handling Approaches  
- **Imbalanced Data** → Training on the original dataset  
- **Balanced Data** → Using **undersampling** to equalize spam & ham instances  

### 🔹 Feature Extraction  
- **TF-IDF Vectorization** for Logistic Regression  
- **Tokenization & Padding** for Deep Learning  

## 📊 Results & Comparison  
✔️ Evaluated using:  
- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1-score**  
- **Confusion Matrix**  

📌 Performance is analyzed **before and after balancing the dataset** to observe the impact of handling class imbalance.  

## 📦 Requirements  
Install the required dependencies using:  
```bash
pip install -r requirements.txt
