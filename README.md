# Rainfall Data Analyzer (PS No. 28)

## 📌 Description
A Python-based data analysis tool to analyze monthly rainfall data from a CSV file. It uses **NumPy** and **Pandas** to calculate total and average rainfall, detect wettest/driest months, identify heavy-rainfall months, and plot rainfall trends using **Matplotlib**.

## 🚀 Features
- **Auto Data Generation:** Automatically generates a sample `rain.csv` on the initial run if the file doesn't exist.
- **Data Cleaning:** Handles missing (`NaN`), invalid (strings), and negative rainfall readings gracefully.
- **Statistical Analysis:** Calculates Mean, Total, Maximum, Minimum, and Population Standard Deviation using `numpy`.
- **Boolean Filtering:** Identifies heavy rainfall months (> 200 mm) and filters data above/below the average.
- **Data Visualization:** Generates dual Matplotlib charts (Bar and Line) to visualize monthly rainfall trends.

## 🛠️ Tech Stack
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Rainfall-Data-Analyzer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Rainfall-Data-Analyzer
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the script:
   ```bash
   python rainfall_analyzer.py
   ```
*(Note: A sample `rain.csv` will be created automatically when you run the script for the first time.)*
