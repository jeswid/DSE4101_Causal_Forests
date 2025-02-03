# DSE4101_Causal_Forests

## 📌 Project Overview  
This repository contains our work on estimating **Heterogeneous Treatment Effects (HTEs)** using **Causal Forests** and other causal inference techniques. Our project explores how machine learning methods, particularly **Generalized Random Forests (GRF)**, can improve treatment effect estimation compared to traditional methods like **Causal Trees, AIPW, and BART**.  

We simulate synthetic datasets with randomized treatment assignment and heterogeneous treatment effects, evaluate model performance using **out-of-sample RMSE**, and discuss the strengths and limitations of different models.  

---

## 🛠️ How to Explore This Repository  

### 🔹 Key Files & Folders
- **📂 `data.rmd`** – Code for generating synthetic dataset
- **📂 `data.Rds`** – Synthetic dataset   
- **📂 `ML.rmd`** – Implementation of causal inference models and evaluation 
- **📄 `README.md`** – This file! Start here for an overview  

### 🚀 Getting Started
1. **Clone the repository**  
   ```sh
   git clone https://github.com/yourusername/DSE4101_Causal_Forests.git
   cd DSE4101_Causal_Forests
   ```
   
2. **Run data generation**
   ```r
   source("data.Rmd")
   ```
   
3. **Train and evaluate causal models**
   ```r
   source("ML.Rmd")
   ```




