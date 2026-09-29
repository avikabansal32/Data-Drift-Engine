# Automated Data Drift & Statistical Profiling Engine 📊

## Overview
Machine learning models fail in production when the incoming real-world data changes from the data they were originally trained on. This phenomenon is called **Data Drift**. 

This project is a Python-based engine that automatically compares a historical (reference) dataset against a new (current) dataset, calculates the statistical differences, and visualizes the drift. It acts as an early-warning system for data degradation.

## Visualizing the Drift
<img width="500" alt="KDE plot graph" src="https://github.com/user-attachments/assets/26af5146-2f6f-4deb-8154-7c04da13b3be" />


## Tech Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib

## How It Works
The engine takes two CSV files and performs the following operations:
1. **Baseline Profiling:** Calculates the mean, median, standard deviation, and missing values for the reference data.
2. **Comparison:** Evaluates the new dataset against the baseline.
3. **Visualization:** Generates side-by-side distribution plots to physically show where the data has shifted.

## Quick Start
To run this project locally:

1. **Clone the repository:**
   ```bash
   git clone (https://github.com/avikabansal32/Data-Drift-Engine.git)
