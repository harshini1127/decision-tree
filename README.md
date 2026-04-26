# decision-tree
# 🌳 Decision Tree Models Comparison

## 📌 Project Title

Implementation and Comparison of 7 Types of Decision Tree Models on a Common Dataset

---

## 📖 Description

This project demonstrates the implementation of **seven different decision tree-based models** using the same dataset. The goal is to analyze how different decision tree approaches perform and compare their accuracies.

---

## 🎯 Objective

* To understand different types of decision tree algorithms
* To implement multiple tree-based models on the same dataset
* To compare their performance using accuracy metrics

---

## 📊 Dataset

A small dataset is used with the following features:

* Age
* Income
* Student (Yes/No)
* Credit Rating (Fair/Excellent)
* Target: Buys Computer (Yes/No)

The dataset is preprocessed using label encoding to convert categorical values into numerical form.

---

## 🌳 Models Implemented

The following 7 types of decision tree models are used:

1. **ID3 (Entropy-based Decision Tree)**
2. **CART (Gini-based Decision Tree)**
3. **Decision Tree with Max Depth Constraint**
4. **Decision Tree with Min Samples Split**
5. **Decision Tree with Min Samples Leaf**
6. **Pruned Decision Tree (Cost Complexity Pruning)**
7. **Extra Trees Classifier (Randomized Tree Ensemble)**

---

## ⚙️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Google Colab

---

## 🚀 Steps to Run

1. Open Google Colab
2. Copy and paste the provided code into a notebook
3. Run all cells sequentially
4. Observe accuracy results for each model

---

## 📈 Results

Example output:

```
1. ID3 (Entropy) → Avg Accuracy: 1.00  
2. CART (Gini) → Avg Accuracy: 1.00  
3. Max Depth = 3 → Avg Accuracy: 1.00  
4. Min Samples Split = 4 → Avg Accuracy: 1.00  
5. Min Samples Leaf = 2 → Avg Accuracy: 1.00  
6. Pruned Tree → Avg Accuracy: 1.00  
7. Extra Trees → Avg Accuracy: 0.80  
```

---

## 🧠 Conclusion

* Most models achieved high accuracy due to the **small and simple dataset**
* Extra Trees showed slightly lower accuracy due to **randomization**
* Cross-validation improves evaluation reliability
* Decision trees are easy to implement and interpret

---

## ⚠️ Limitations

* Dataset size is very small
* Results may not generalize to real-world data
* High accuracy may indicate overfitting

---

## 📌 Future Improvements

* Use larger and real-world datasets
* Compare with other algorithms (SVM, KNN, Neural Networks)
* Visualize decision trees
* Perform hyperparameter tuning

---

## 👩‍💻 Author

Harshini

---
