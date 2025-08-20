# Optimasi-Hyperparameter-pada-CNN-ResNet-50-Menggunakan-PSO-untuk-Klasifikasi-Tumor-Otak-Berbasis-MRI

📌 Deskripsi

Project ini bertujuan untuk mendeteksi tumor otak dari citra MRI menggunakan Convolutional Neural Network (CNN) arsitektur ResNet-50.
Selain itu, dilakukan optimasi hyperparameter menggunakan Particle Swarm Optimization (PSO) untuk mendapatkan konfigurasi hyperparameter yang optimal dan dapat meningkatkan kinerja model.

Dengan pendekatan ini, model mampu melakukan binary classification:

0 → Normal Brain

1 → Brain Tumor


📊 Hasil Eksperimen

Baseline Model (LR=0.0001, Epoch=15):

Training Accuracy: 89%

Validation Accuracy: 88%

Validation Loss: 0.50

Precision: 0.91, Recall: 0.89, F1-Score: 0.90

FN: 5 kasus, FP: 4 kasus


Optimized Model (PSO, LR=0.0049, Epoch=15):

Training Accuracy: 92%

Validation Accuracy: 95%

Validation Loss: 0.28

Precision: 0.98, Recall: 0.94, F1-Score: 0.96

FN: 3 kasus, FP: 1 kasus


👉 Hasil ini menunjukkan bahwa optimasi hyperparameter menggunakan PSO secara signifikan meningkatkan performa model CNN ResNet-50 dalam klasifikasi citra MRI tumor otak.
