# 🧠 Optimasi Hyperparameter pada CNN ResNet-50 Menggunakan PSO untuk Klasifikasi Tumor Otak Berbasis MRI  

## 📌 Deskripsi  
Project ini bertujuan untuk mendeteksi tumor otak dari citra MRI menggunakan **Convolutional Neural Network (CNN)** dengan arsitektur **ResNet-50**.  
Untuk meningkatkan performa, dilakukan optimasi hyperparameter menggunakan **Particle Swarm Optimization (PSO)** sehingga diperoleh konfigurasi yang lebih optimal.  

Model melakukan **binary classification**:  
- `0` → Normal Brain  
- `1` → Brain Tumor  

---

## 📊 Hasil Eksperimen  

### 🔹 Baseline Model  
- **Learning Rate:** 0.0001  
- **Epochs:** 15  
- **Training Accuracy:** 89%  
- **Validation Accuracy:** 88%  
- **Validation Loss:** 0.50  
- **Precision:** 0.91  
- **Recall:** 0.89  
- **F1-Score:** 0.90  
- **False Negative (FN):** 5 kasus  
- **False Positive (FP):** 4 kasus  

### 🔹 Optimized Model (PSO)  
- **Learning Rate:** 0.0049  
- **Epochs:** 15  
- **Training Accuracy:** 92%  
- **Validation Accuracy:** 95%  
- **Validation Loss:** 0.28  
- **Precision:** 0.98  
- **Recall:** 0.94  
- **F1-Score:** 0.96  
- **False Negative (FN):** 3 kasus  
- **False Positive (FP):** 1 kasus  

---

## ✅ Kesimpulan  
Hasil eksperimen menunjukkan bahwa **optimasi hyperparameter menggunakan PSO** secara signifikan meningkatkan performa model **CNN ResNet-50** dalam klasifikasi citra MRI tumor otak.  
