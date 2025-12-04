# 🚀 Hate Speech Classification – Baseline Model

A simple baseline Transformer-based text classification model that categorizes text into:
- **Hate Speech**
- **Offensive Language**
- **Normal**

This repository contains everything needed to **train the model from scratch** or **directly use the trained model** with your own custom text.

---

## 📁 Project Structure


---

## 🔧 1. How to Train the Model (Optional)

If you want to train the model yourself:

1. Upload the dataset:  
   `english_preprocessed/datasets/all_english_data_merged.csv`
2. Open the training notebook:  
   **`transformerTraining_final_(1).ipynb`**
3. Run all cells to train the model.

> The notebook contains steps for data loading, preprocessing, training, and saving the model.

---

## ⚡ 2. Use the Already Trained Model (Recommended)

If you want to directly test the model with your own input texts:

### **Step 1 — Upload the `model` Folder**

#### Option A: Direct Upload  
Upload the full `model` folder into your environment (Google Colab / Jupyter Notebook).

#### Option B: Manual Upload  
If you cannot upload an entire folder:
1. Create a new folder named **`model`**.
2. Upload all files *inside* the original model folder into this folder.

---

### **Step 2 — Run the Usage Notebook**

Open the notebook:

**`usage_example.ipynb`**

This notebook includes:
- Model loading  
- Inference code  
- Sample test texts  

---

## 📝 Testing With Your Own Text

Inside `usage_example.ipynb`, you will find:

```python
test_texts = [
    # sample test texts already included
]

test_texts = [
    "your custom sentence here",
    "another sample text",
]
# aiml-text-classification
