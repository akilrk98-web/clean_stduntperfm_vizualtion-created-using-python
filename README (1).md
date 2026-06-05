# 📊 Student Performance Visualization
**Created using Python | Jupyter Notebook**

---

## 📌 Project Overview

This project performs **data cleaning and visualization of student performance data** using Python.  
It analyzes how study hours and previous scores relate to final exam scores through multiple chart types.

---

## 🎯 Objective

- Load and explore cleaned student performance dataset (`clnd_stdnt_prfrm.csv`)
- Visualize the relationship between study hours and previous scores
- Compare average studied hours, previous marks, and annual marks
- Analyze distribution of final scores
- Understand how study time impacts final exam results

---

## 🛠️ Libraries Used

| Library | Purpose |
|---------|---------|
| `pandas` | Load and manipulate the dataset |
| `matplotlib` | Bar chart and Pie chart plotting |
| `seaborn` | Scatter plot and Histogram with KDE |

---

## 📂 Project Structure

```
clean_stduntperfm_vizualtion-created-using-python/
│
├── clean_stduntperfm_vizualtion.ipynb   # Main Jupyter Notebook
├── clnd_stdnt_prfrm.csv                 # Cleaned student performance dataset
└── README.md                            # Project documentation
```

---

## 📊 Visualizations Included

### 1. 📊 Bar Chart — Performance Score
- X-axis: **Hours Studied**
- Y-axis: **Previous Score**
- Shows how study hours relate to previous exam performance

### 2. 🥧 Pie Chart — Average Comparison
- Compares the **mean** of:
  - Hours Studied
  - Previous Marks
  - Annual (Final) Marks
- Displays percentage contribution of each metric

### 3. 🔵 Scatter Plot — Study Hours vs Final Marks
- X-axis: **Hours Studied**
- Y-axis: **Final Scores**
- Reveals correlation between study time and final results

### 4. 📈 Histogram — Annual Mark Distribution
- Distribution of **Final Scores** with KDE curve
- Shows the spread and frequency of student marks

---

## 📋 Dataset Columns Used

| Column | Description |
|--------|-------------|
| `Hours Studied` | Number of hours the student studied |
| `Pervious Score` | Score from previous exam |
| `final Scores` | Final exam score (annual marks) |

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/akilrk98-web/clean_stduntperfm_vizualtion-created-using-python.git
   ```

2. Navigate to the project folder:
   ```bash
   cd clean_stduntperfm_vizualtion-created-using-python
   ```

3. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook clean_stduntperfm_vizualtion.ipynb
   ```

5. Run all cells to see the visualizations.

---

## 💡 Key Insights

- Students who studied more hours generally scored higher in final exams
- There is a visible positive correlation between study hours and final scores
- The histogram shows most students scored in the mid-range band
- Pie chart reveals how previous marks weigh against final performance

---

## 🧑‍💻 Author

**akilrk98-web**  
📎 GitHub: [https://github.com/akilrk98-web](https://github.com/akilrk98-web)

---

## 📄 License

This project is open source and free to use.
