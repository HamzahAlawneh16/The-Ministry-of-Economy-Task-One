# ️ National Citizen Segmentation Framework
### **Ministry of Digital Economy and Entrepreneurship**
**AI Directorate - Task #1**

---

##  Engineer Information
* **Name:** Hamza Medhat Alawneh
* **Role:** AI Engineer
* **Project:** Population Clustering & Socio-Economic Analysis

---

##  Project Objective
This framework is engineered to strategically segment citizens into distinct groups based on demographic and economic indicators (Age, Income, Education, etc.). The goal is to provide the Ministry with a data-driven foundation for targeted resource allocation and policy personalization.

---

## ️ Tech Stack & Engineering Tools
The project utilizes a high-performance Python stack tailored for machine learning:
* **Core:** `Python 3.10+`
* **Data Science:** `Pandas`, `NumPy` (Heavy Matrix Operations)
* **Visualization:** `Matplotlib`, `Seaborn`
* **Modeling & Evaluation:** `Scikit-learn` (StandardScaler, PCA, GMM, Metrics)

---

##  Key Technical Highlights

### Custom Implementation (The Bonus Challenge)
Unlike standard implementations, this project features a **K-Means algorithm built from scratch**. 
* **Vectorization:** Uses NumPy broadcasting to eliminate Python loops, ensuring $O(n)$ efficiency.
* **Transparency:** Full control over centroid initialization, Euclidean distance calculation, and convergence stability.

### ️ Data Integrity Audit
A rigorous pre-processing pipeline was implemented to ensure "Production-Ready" data:
* Verification of zero null values and duplicates.
* **Z-score Normalization:** Crucial step to prevent high-magnitude features (Income) from biasing the distance metrics.

###  Competitive Benchmarking
To ensure the highest accuracy, we compared two distinct mathematical approaches:
1.  **K-Means (Custom):** Centroid-based partitioning.
2.  **GMM (Library):** Probabilistic density estimation.
> **Result:** K-Means outperformed GMM with a **Silhouette Score of 0.255**, providing sharper cluster boundaries.

---

## Project Structure
* `Task1_Citizen_Segmentation_Hamza.ipynb` -> Fully documented Google Colab Notebook.
* `Technical_Report_Hamza_Alawneh.pdf` -> Professional summary and complexity analysis.
* `segmentation data.csv` -> The processed dataset.

---

## How to Execute
1.  Open the `.ipynb` file in **Google Colab**.
2.  Upload the `segmentation data.csv` when prompted.
3.  Run all cells to generate the **Correlation Heatmaps**, **PCA Plots**, and **Quantitative Metrics**.

---

> **Final Engineering Note:** > "This framework is designed for scalability. The logic used in the scratch implementation ensures that as the Ministry's data grows, the underlying mathematics remain robust and interpretable."
