# Student Performance Clustering with Gaussian Mixture Models (GMM)

## 📌 Project Overview
This project applies **Gaussian Mixture Models (GMM)** to cluster students based on their academic performance in **Math, Reading, and Writing**.  
The goal is to uncover hidden learning patterns and group students with similar performance profiles for better educational insights.

---

## 📂 Dataset
- **Source:** [Exam Scores Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Features Used:**
  - **Math Score**
  - **Reading Score**
  - **Writing Score**
- Additional attributes include gender, race/ethnicity, parental education level, lunch type, and test preparation course completion.

---

## 🛠 Methodology
1. **Data Cleaning & Preparation**
   - Removed unnecessary columns for clustering.
   - Selected only numerical features (scores).
   - Standardized data for GMM.

2. **Gaussian Mixture Model**
   - Used `sklearn.mixture.GaussianMixture` for clustering.
   - Chose optimal number of clusters based on BIC/AIC.
   - Assigned cluster labels to each student.

3. **Evaluation**
   - Visualized clusters using 2D scatter plots.
   - Analyzed distribution of student attributes across clusters.

---

## 📊 Results
- **Clusters Formed:**
```

Cluster 0 → 441 students
Cluster 1 → 264 students
Cluster 2 → 295 students

````
- Insights:  
- Each cluster shows distinct academic profiles.
- Useful for targeted learning programs and student support.

---

## 📦 Installation & Usage
```bash
# Clone the repository
git clone https://github.com/Laiba-Azhar0707/student-performance-gmm.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook student_gmm.ipynb
````

---

## 📌 Requirements

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

## 📜 License

This project is for educational purposes only.

