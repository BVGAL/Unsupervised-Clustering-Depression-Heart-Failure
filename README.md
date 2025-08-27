
## ❤️‍🩹 Clustering Depression Severity and Heart Failure Progression

### An Unsupervised Analysis of PHQ-9 Scores and Cardiac Outcomes

This repository presents an unsupervised clustering study exploring the relationship between **depression severity** (measured by PHQ-9) and **heart failure indicators**, including mortality, ejection fraction, BNP levels, and kidney function.

---

### 🎯 Project Aim

To determine whether patients with higher **depression scores** also tend to experience **worse cardiovascular outcomes**, by applying clustering algorithms to a clinical dataset of **425 patients** with heart failure.

---

### 🧠 Methods Used

Clustering was conducted in **Orange Data Mining** using:

* **K-Means** (optimal k=2, silhouette validated)
* **Hierarchical Clustering** (3 clusters, 89% tree height)
* **DBSCAN** (ε = 3.62, k-distance optimized)

Preprocessing included normalization and feature selection of clinically relevant variables.

---

### 📋 Key Features Used

* **PHQ-9** (depression score)
* **Ejection fraction (%)**
* **BNP / NT-proBNP levels**
* **Blood urea nitrogen**, **eGFR**
* **Systolic blood pressure**, **age**
* **Hospitalization & mortality status**

---

### 📊 Key Findings

Across all clustering methods:

* Clusters with **higher PHQ-9** scores consistently exhibited:

  * **Lower ejection fraction**
  * **Higher mortality** (up to 96.5% in K-Means C2)
  * **Elevated BNP**, **more hospitalizations**
  * **Worse kidney function**

* Visual tools (box plots, scatter plots, MDS) confirmed these patterns and supported the link between **mental health** and **cardiac decline**.

---

### ✅ Conclusion

This analysis provides strong evidence that **depression severity** is associated with **worse heart failure progression**. Clustering methods reveal that higher PHQ-9 scores align with poor cardiac and renal outcomes, reinforcing the need for **integrated mental and physical health care** in chronic heart failure management.



