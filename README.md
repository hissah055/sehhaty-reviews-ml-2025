## Contributors

| Name |
|------|
| Hissah S. Al-Atwi |
| Areej M. Al-Wabisi |
| Salmah M. Al-Qarni |
| Gadaa S. Al-Atwi |
| Wejdan B. Al-Marwani |
| Omar I. Al-Asiri |
| Fathi A. Mubaraki |
## Project Overview

This project analyzes user reviews of the **Sehhaty mobile application** to better understand user experiences, identify key issues, and classify feedback into meaningful themes.

The project includes:
- Data extraction (Google Play)
- Data cleaning & preprocessing
- Exploratory data analysis (EDA)
- Thematic and sentiment classification (Arabic + English)
- Model development using machine learning (SVM + Logistic Regression)
- Reporting and visualization

The final repository contains:
- Cleaned review dataset
- Classification labels (Theme / Subtheme / Sentiment)
- Python scripts for ML processing
- PDF reports for cleaning, analysis, and classification
```
sehhaty-reviews-ml-2025/
│
├── data/
│   ├── data/
│   │   └── .keep
│   ├── sample_clean_labeled_2000.csv
│   └── sample_clean_labeled_2000.xlsx
│
├── reports/
│   ├── Sehhaty_Data_Cleaning_Report.pdf
│   ├── Data_Analysis_Report.pdf
│   └── Review_Classification_Report_2025-10-08.pdf
│
├── train_classifier.py
├── LICENSE
└── README.md
```
## Usage

To run the classification script, execute:

```bash
python train_classifier.py
The script will:

Load the dataset

Perform few-shot classification (Theme / Subtheme / Sentiment)

Fill only empty prediction cells

Preserve existing ground-truth labels

Generate final classification outputs
# (Optional) Create virtual environment
python -m venv .venv

# Activate environment
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# Upgrade pip
pip install -U pip

# Install dependencies
pip install pandas numpy scikit-learn openpyxl unidecode

## Reports (PDF)

- [Sehhaty Data Cleaning Report](Sehhaty_Data_Cleaning_Report.pdf)
- [Data Analysis Report](Data_Analysis_Report.pdf)
- [Review Classification Report](Review_Classification_Report_2025-10-08.pdf)
