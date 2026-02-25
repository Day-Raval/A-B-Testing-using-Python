# 🚀 A/B Testing using Python

> Compare two marketing strategies, measure conversion performance, and choose the winning campaign with data.

![A/B Testing Banner](https://github.com/Day-Raval/A-B-Testing-using-Python/assets/132192767/5cd79076-7a2a-4fb5-a043-5b77791fc2da)

## 📌 Project Overview

This repository demonstrates **A/B Testing analysis** on two campaign groups:
- **Control Campaign**
- **Test Campaign**

The analysis focuses on key performance indicators (KPIs) such as impressions, clicks, add-to-cart actions, and purchases to identify which strategy performs better for business growth.

---

## 🎯 Goal Achieved

✅ Built a complete A/B testing workflow using real campaign data.  
✅ Compared campaign-level metrics across the full funnel.  
✅ Generated visual insights to support decision-making.  
✅ Identified which campaign strategy is more effective for future marketing efforts.

---

## 🧾 Dataset Information

The dataset files are located in the `datasets/` directory:

- `control_group.csv` → baseline campaign performance
- `test_group.csv` → experimental campaign performance

Each dataset includes fields like:
- Spend (USD)
- Impressions
- Reach
- Website Clicks
- Searches
- View Content
- Add to Cart
- Purchases

---

## 🗂️ Repository Structure

```text
A-B-Testing-using-Python/
├── Code/
│   └── A or B strategy-Analysis with Python.ipynb
├── datasets/
│   ├── control_group.csv
│   └── test_group.csv
├── Results of the Testing/
│   └── (visual output images)
└── README.md
```

---

## ⚙️ How to Run (Step-by-Step)

### 1) Clone the repository

```bash
git clone https://github.com/Day-Raval/A-B-Testing-using-Python.git
cd A-B-Testing-using-Python
```

### 2) Create and activate a virtual environment (recommended)

```bash
python -m venv .venv
source .venv/bin/activate        # Linux / macOS
# .venv\Scripts\activate        # Windows (PowerShell)
```

### 3) Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4) Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5) Open and run the notebook

Navigate to:

`Code/A or B strategy-Analysis with Python.ipynb`

Run all cells to reproduce the complete analysis and charts.

---

## 📊 Output

The notebook produces comparative plots and insights, and generated images can be found under:

`Results of the Testing/`

---

## 💡 Business Value

By applying this analysis, teams can:
- Reduce decision-making guesswork
- Allocate budget to better-performing strategies
- Improve ROI and conversion performance over time

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🙌 Contributing

Contributions, improvements, and enhancements are welcome.
Feel free to fork this repo and submit a pull request.

---

## ⭐ Support

If you found this project useful, please give it a ⭐ on GitHub.
