# 🎭 Emotion Classifier

This project is an **Emotion Classification** system built using **TensorFlow/Keras** that can detect human emotions from facial images.  
It uses a **Convolutional Neural Network (CNN)** trained on the *Human Emotions Dataset* from Kaggle.

---

## 📘 Project Overview

The model classifies images into different emotion categories based on facial expressions.  
It performs best on **cropped face images** where the emotions are clearly visible.  
You can either train your own model or use the **pre-trained model** provided below.

---

## 🎬 Demo Video

Check out the demo of the model in action:  
[Watch Demo on YouTube](https://youtu.be/sYWt0kcxBvY)

---

## ⚙️ Usage Instructions

### 🧠 **To Train the Model**

1. Open **`Emotion-classifier--modelling.ipynb`**
2. Run the **first cell** — it will automatically download the dataset from Kaggle.
3. In the **second cell**, update these paths:
   ```python
   train_directory = "path_to_your_train_folder"
   test_directory = "path_to_your_test_folder"
  (Both should point to folders inside the human-emotions-dataset)

4.Run the remaining cells to train and evaluate your model.

### 💾 **Using the Pre-trained Model (Recommended)**

If you don't want to train the model manually:

- Download the pre-trained model from here:  
  👉 [Emotion Model (Google Drive)](https://drive.google.com/file/d/1k1EiKhrQEwBS4Kl5kQHMGZ0s56LOJFHM/view?usp=sharing)

- Place the downloaded model file in the **same folder** as the notebooks.

Then, open **`Model-Test.ipynb`** and set the paths like this:

```python
model = "path_to_your_downloaded_model"
img = "path_to_your_test_image"
```

---

### 🧪 **Testing**

Run **`Model-Test.ipynb`** to test predictions on your images.

For best results, make sure your image is **cropped to show only the face** and the **emotion is clearly visible**.  
Sample test images are already provided in the **`test/`** directory.

---

### 🧠 **Model Information**

- **Framework:** TensorFlow / Keras  
- **Architecture:** CNN with Conv2D, MaxPooling, BatchNormalization, and Dense layers  
- **Input Size:** 256 × 256 × 3  
- **Activation:** ReLU + Softmax  
- **Optimizer:** Adam  

---

### 📜 **License**

This project is licensed under the **MIT License** — feel free to use, modify, and share it for learning or research.

---

### 📬 **Contact**

For queries or collaboration, reach out on **Discord:**  
**`adarsh0910`**

---

