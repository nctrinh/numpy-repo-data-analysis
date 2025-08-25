# 📊 NumPy Repository Data Analysis

This project focuses on analyzing the **official [NumPy GitHub repository](https://github.com/numpy/numpy)**.  
It collects data such as commits, issues, pull requests, contributors, languages, and repository growth, then processes and visualizes them using **Python** with **NumPy** and other supporting libraries.  

The goal is to provide insights into the development history and community dynamics of one of the most important scientific computing libraries in Python.

---

## 📂 Repository Structure

### 🔹 Data Collection (`get_raw_data/`)
Jupyter notebooks for extracting raw data from the NumPy GitHub repository:
- `get_commit.ipynb` – collect commit history
- `get_issues.ipynb` – extract issue details
- `get_pull_requests.ipynb` – gather pull request metadata
- `get_files_data.ipynb` – extract repository files information
- `get_languages.ipynb` – retrieve programming languages statistics

### 🔹 Data Analysis (`analyze_data/`)
Jupyter notebooks for cleaning, processing, and analyzing the collected data:
- `analyze_commits.ipynb` – commit activity and contributors
- `analyze_issues.ipynb` – issue creation, resolution, and trends
- `analyze_pulls.ipynb` – pull request activity
- `analyze_languages.ipynb` – breakdown of languages used in NumPy
- `analyze_files.ipynb` – file-level contribution analysis
- `analyze_network_graph.ipynb` – contributor collaboration network
- `analyze_repo_growth_rate.ipynb` – repository growth over time
- `analyze_readme.ipynb` – study and analyze README contents

### 🔹 Cleaned Data (`cleaned_data/`)
Exported, cleaned datasets for reuse:
- `cleaned_all_issues_data.xlsx`
- `cleaned_all_pulls_data.xlsx`
- `cleaned_commits_in_file_data.xlsx`
- `cleaned_languages_data.xlsx`
- and more preprocessed datasets.

### 🔹 Other Files
- `link_to_raw_data_files.txt` – references to raw data sources

---

## ⚙️ Requirements

To run the notebooks, you need:

- Python 3.8+
- Jupyter Notebook
- NumPy  
- Pandas  
- Matplotlib
- openpyxl
