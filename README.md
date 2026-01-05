## 📊 Dataset Description

The dataset used in this project represents **sensor-level measurements from a semiconductor manufacturing process**.

- **Source**: Industrial sensor and process monitoring data  
- **File**: `signal-data.csv`  
- **Observations**: ~1,567 production entities  
- **Features**: ~591 sensor and process variables  
- **Target Variable**: Binary yield outcome  
  - `-1` → Pass  
  - `1` → Fail  

Each row corresponds to a single production entity at a specific test point, and each feature represents a measured signal collected from sensors or process control systems.

---

## 🧠 Problem Context

Modern semiconductor manufacturing generates a **large number of sensor signals**, many of which may be:
- Redundant  
- Noisy  
- Weakly related to yield outcomes  

The challenge is to:
- Identify **critical signals** impacting yield  
- Reduce dimensionality without losing predictive power  
- Build robust models that generalize well  

This makes the dataset **high-dimensional, noisy, and imbalanced**, closely reflecting real-world industrial data challenges.

---

## ⚙️ Data Challenges Addressed

- High feature-to-sample ratio  
- Missing values and noisy signals  
- Class imbalance in yield outcomes  
- Multicollinearity among sensor features  

These challenges were addressed through **data cleaning, feature selection, dimensionality reduction, and model tuning**.

