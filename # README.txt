# README

## Road Accident Data Analysis Project

### Project Overview
This project focuses on analyzing road accident data from 2022 and beyond. The primary goal is to preprocess the data, address missing values, and perform exploratory data analysis (EDA) to identify trends and insights that can contribute to traffic safety improvements.

### Features
1. **Data Loading:** Load accident data from a CSV file.
2. **Data Cleaning:**
   - Filter data for records from 2022 and later.
   - Identify and handle missing values.
   - Drop columns with over 50% missing data (except essential columns like 'RAMZOR').
3. **Exploratory Data Analysis:**
   - Display dataset statistics and structure.
   - Visualize key data trends.
4. **Data Insights:** Extract meaningful patterns to inform safety measures.

### Files
- `ML Advanced - Tal Davidi.ipynb`: Jupyter Notebook containing the project code and analysis.
- `דאטה תאונות דרכים.csv`: CSV file with road accident data.

### Prerequisites
To run this project, you need the following:
- Python 3.7 or higher.
- Jupyter Notebook or another IDE supporting `.ipynb` files.

### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook "ML Advanced - Tal Davidi.ipynb"
   ```

### Usage
1. Ensure the `דאטה תאונות דרכים.csv` file is in the project directory.
2. Run each cell in the notebook sequentially to execute the analysis.
3. Review the visualizations and insights generated in the notebook.

### Results
- Insights into missing data percentages per column.
- Identification of key features influencing traffic accidents.
- Data visualizations highlighting trends and anomalies.

---

# Requirements

pandas==1.3.3
matplotlib==3.4.3
numpy==1.21.2
seaborn==0.11.2
jupyter==1.0.0
