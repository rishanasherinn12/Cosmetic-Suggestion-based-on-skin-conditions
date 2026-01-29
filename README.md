# Cosmetic Suggestion Based on Skin Conditions Using AI

This project presents an AI-driven system that analyzes skin images and provides personalized cosmetic recommendations based on detected skin conditions. The goal is to reduce trial-and-error in skincare by offering accurate, data-driven product suggestions using deep learning.

The system classifies skin conditions from user-uploaded images and maps the results to a curated CSV-based cosmetic database to recommend suitable products. After experimenting with six different deep learning algorithms, **MobileNetV2** was selected as the final model due to its superior balance of accuracy, speed, and lightweight architecture.

---

## 🔍 Features

- Image-based skin condition classification  
- Supports common conditions such as acne, dry, oily, and sensitive skin  
- Deep learning model trained using MobileNetV2  
- CSV-based cosmetic recommendation engine  
- End-to-end pipeline: image → classification → product recommendation  
- Lightweight and efficient for real-time use  
- Can be integrated with a web UI (Anvil)

---

## 🧠 Model Comparison

The following six deep learning models were trained and evaluated:

1. MobileNetV2 *(Final Model)*  
2. MobileNetV3Small  
3. EfficientNetV2B0  
4. EfficientNetB0  
5. ResNet50  
6. VGG16  

Among these, **MobileNetV2** demonstrated the best trade-off between accuracy, inference speed, and computational efficiency, making it ideal for real-time and resource-constrained environments.

---

## 📁 Project Structure

├── skin_dataset/ # Image dataset for training
├── skin_classify_MobileNetV2.ipynb # Final model training notebook
├── predict&recommend_csv.ipynb # Prediction and recommendation logic
├── training_model_ipynb/ # Other model experiments (6 algorithms)
├── products.csv # Cosmetic product database
└── README.md

---

## ⚙️ Requirements

### Hardware
- Intel Core i5 or higher  
- 8 GB RAM or more  
- 256 GB SSD  
- GPU (optional for faster training)

### Software
- Python 3.9+  
- TensorFlow / Keras  
- OpenCV  
- Pandas, NumPy  
- Anvil (for UI integration)

---

## 🚀 How It Works

1. User uploads a skin image  
2. Image is preprocessed and passed to the trained MobileNetV2 model  
3. The model predicts the skin condition  
4. The predicted class is matched with the cosmetic CSV database  
5. Suitable products are recommended to the user  

---

## 🎯 Objectives

- Automate skin condition analysis using AI  
- Provide accurate and personalized cosmetic recommendations  
- Reduce dependency on trial-and-error product selection  
- Build a scalable and user-friendly solution for skincare guidance  

---

## 📌 Future Enhancements

- Expand dataset with more skin conditions  
- Improve accuracy using advanced augmentation techniques  
- Add user feedback loop for recommendation refinement  
- Deploy as a full-stack web or mobile application  

---

## 👩‍💻 Author

**Rishana Sherin**  
MSc Computer Science  
Project: *Cosmetic Suggestion Based on Skin Conditions Using Artificial Intelligence*

---

This project demonstrates how AI and computer vision can transform personalized skincare by providing fast, accurate, and reliable cosmetic recommendations.
