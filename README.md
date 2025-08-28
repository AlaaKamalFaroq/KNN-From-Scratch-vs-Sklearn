# 🧠 KNN Classifier: From Scratch vs Scikit-learn

This project implements the **K-Nearest Neighbors (KNN)** algorithm from scratch and compares it with **scikit-learn’s `KNeighborsClassifier`** using the famous Iris dataset 🌸.

---

## 📊 Project Highlights
- ✅ Implemented KNN from scratch (distance metrics + majority voting).  
- ✅ Compared performance with scikit-learn’s optimized `KNeighborsClassifier`.  
- ✅ Visualized results with **confusion matrices** (custom vs sklearn).  
- ✅ Wrote a **clear conclusion** on differences in accuracy and tie-breaking.  

---

## 🚀 Technologies Used
- **Python**  
- **NumPy, Pandas**  
- **Matplotlib, Seaborn**  
- **Scikit-learn**  

---

## 📂 Repository Structure
```
├── knn_classifier.ipynb   # Jupyter Notebook with full implementation
├── README.md              # Project documentation
```

---

## 📈 Results

### 🔹 Accuracy
Both implementations achieve similar accuracy.  
- Custom KNN sometimes shows slightly higher/lower accuracy due to **random tie-breaking**.  
- Scikit-learn’s KNN is **more consistent and reproducible**.  

### 🔹 Confusion Matrices
| Custom KNN | Scikit-learn KNN |
|------------|------------------|
| ![Custom KNN](./images/custom_knn.png) | ![Sklearn KNN](./images/sklearn_knn.png) |

*(Add screenshots of your confusion matrices in an `images/` folder and update paths.)*

---

## 📝 Conclusion
Building KNN from scratch helped me understand:
- Distance calculation (Euclidean/Manhattan)  
- Selecting the `k` nearest neighbors  
- Majority voting and tie-breaking  

⚡ **Key Insight**:  
My implementation is not truly “better” — differences come from how ties are resolved.  
In real-world projects, I would rely on **scikit-learn’s KNN** because it’s **optimized, reliable, and reproducible**.  

---

## 📌 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/YourUsername/KNN-Classifier-Implementation.git
   ```
2. Open the notebook:
   ```bash
   jupyter notebook knn_classifier.ipynb
   ```
3. Run all cells to see results.

---

✨ This project was created as part of my learning journey in **Machine Learning** and will be updated with more experiments. 🚀
