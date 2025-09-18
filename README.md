# 📊 Google Play Store Apps Analysis

This repository contains a Google Colab Notebook that analyzes the **Google Play Store dataset**.  
The goal is to explore app categories, app types, and content ratings to gain useful insights.

---

## 🚀 Features of the Notebook

The notebook performs the following tasks:

1. **Upload Dataset**  
   - Load the `googleplaystore.csv` dataset into Google Colab.

2. **Total Number of Unique Categories**  
   - Finds how many unique app categories exist.

3. **Number of Apps in a Category**  
   - Example: Counts how many apps are in the `ART_AND_DESIGN` category.

4. **Total Number of App Types**  
   - Lists all unique app types (e.g., `Free`, `Paid`).

5. **Free vs Paid Apps Analysis**  
   - Counts total number of free and paid apps.  
   - Calculates the percentage of free apps.

6. **Content Ratings**  
   - Lists all available content ratings in the dataset (`Everyone`, `Teen`, `Mature 17+`, etc.).

---

## 📂 Files in This Repo

- `Google_Play_Analysis.ipynb` → Main Jupyter/Colab Notebook.  
- `googleplaystore.csv` → Dataset used for analysis.  
- `.gitignore` → Standard ignore file for Colab/Notebooks.  
- `LICENSE` → License for open-source usage.  
- `README.md` → Project documentation.

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**.
2. Upload the dataset (`googleplaystore.csv`) when prompted.
3. Run the cells step by step.
4. View insights directly in the output.

---

## 🛠️ Example Output

- **Total Categories:** 33  
- **Apps in ART_AND_DESIGN:** 65  
- **Free Apps:** 8,719  
- **Paid Apps:** 647  
- **% of Free Apps:** 93%  
- **Content Ratings:** Everyone, Teen, Mature 17+, etc.

---

## 📌 Requirements

- Python 3  
- Pandas  
- Google Colab / Jupyter Notebook  

---

## 📜 License

This project is licensed under the **MIT License**.  
Feel free to use and modify for learning or research purposes.

---

## 🙌 Acknowledgements

Dataset: [Google Play Store Apps Dataset (Kaggle)](https://www.kaggle.com/lava18/google-play-store-apps)  
Inspired by data analysis practice exercises.
