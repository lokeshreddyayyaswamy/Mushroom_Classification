# 🍄 Mushroom Safety Classifier

This project is a machine learning model designed to classify mushrooms as **edible** or **poisonous**.  
Using a dataset of mushroom characteristics, the model learns to identify patterns that distinguish safe mushrooms from toxic ones — helping to prevent accidental poisoning.

---

## 📖 Project Overview
The goal of this project is to build a reliable classifier that acts like a **digital mushroom expert**.  
By inputting a mushroom’s physical attributes (cap shape, color, odor, etc.), the system predicts its classification with **high accuracy**.  
This project demonstrates a practical application of machine learning for **public safety**.

**License:** Google

---

## ⚙️ How It Works
The model follows a standard ML pipeline:

1. **Data Loading & Cleaning**  
   - Loads the mushroom dataset.  
   - Handles missing values in the *stalk-root* feature by filling them with the **mode**.

2. **Feature Engineering**  
   - Converts categorical features (e.g., *cap-color = red/brown*) into numerical format.  
   - Uses **One-Hot Encoding** to generate binary columns for each attribute.

3. **Model Training**  
   - Splits the dataset into **80% training** and **20% testing**.  
   - Trains a **Decision Tree Classifier** that learns if-then-else rules to make predictions.

4. **Prediction**  
   - Uses the trained model to classify unseen mushrooms as **poisonous** or **edible**.

---

## 📊 Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Mushroom)  
- **Samples:** 8,124 mushrooms  
- **Features:** 22 categorical attributes  
- **Challenge:** Since all features are categorical, preprocessing is essential.  

---

## ✨ Key Features
- **Data Preprocessing** → Handles missing values smoothly.  
- **Robust Encoding** → Converts categorical data into machine-readable format.  
- **High Accuracy** → Decision Tree model achieves **100% accuracy**.  
- **Prediction Ready** → Classifies new mushroom data instantly.  

---

## 💻 Technology Stack
- **Language:** Python  
- **Libraries:**  
  - `pandas` → Data manipulation & analysis  
  - `scikit-learn` → Preprocessing, model training & evaluation  

---

## 🚀 Getting Started

### 1. Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
