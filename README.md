# ⛽ Vent-Flow Event Severity Classification (AER Wells)

## 🔍 Problem
Surface Casing Vent Flow (SCVF) and gas migration events in oil & gas wells can cause methane emissions, groundwater contamination, and serious safety hazards.  
Early identification of **high-risk wells** is critical for preventing environmental damage.

## 🎯 Goal
Build machine learning models to classify well events as **Serious** or **Non-Serious**, enabling proactive monitoring and risk-based inspections.

## 📊 Dataset
Alberta Energy Regulator – Vent Flow & Gas Migration Report  
- 39,321 wells  
- Public regulatory dataset  
- Target: event severity (Serious / Non-Serious)

### Features used
- Flow substance type  
- Flow rate (m³/day)  
- Groundwater depth  
- Shut-in pressure  
- Source depth  

## ⚙️ Methods
- Data cleaning & preprocessing
- Feature engineering
- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Decision Trees
- Cross-validation & confusion matrix evaluation

## 📈 Results
- Compared multiple classifiers to identify the best-performing model
- Identified key predictors of severe vent-flow events
- Generated decision rules to flag high-risk wells

👉 Enables data-driven inspection prioritization and improved environmental safety.

## 🛠 Tech Stack
Python / R • Pandas / tidyverse • scikit-learn • Statistical modeling • Visualization

## ▶️ How to Run
```bash
git clone <repo-url>
