# Feedback from the Depth of Reviews: Reimagining User Experience in Saudi Arabia’s Sehhaty App

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

## Install Dependencies

```bash
pip install pandas numpy scikit-learn openpyxl unidecode
 ``` 
## Reports (PDF)

- [Sehhaty Data Cleaning Report](reports/Sehhaty_Data_Cleaning_Report.pdf)
- [Data Analysis Report](reports/Data_Analysis_Report.pdf)
- [Review Classification Report](reports/Review_Classification_Report_2025-10-08.pdf)
## License
This project is licensed under the MIT License.
## Citation
If you use this project, please cite it as:

Hissah.S.Al-Atwi et al. (2025). *Sehhaty Reviews ML Classification Project*.


## 📬 Contact  
For inquiries, please contact:  

**Hissah S. Al-Atwi**  
📧 452010119@stu.ut.edu.sa  

**Areej M. Al-Wabisi**  
📧 452009812@stu.ut.edu.sa  

**Salmah M. Al-Qarni**  
📧 452010215@stu.ut.edu.sa  

**Gadaa S. Al-Atwi**  
📧 452010230@stu.ut.edu.sa  

**Wejdan B. Al-Marwani**  
📧 452009724@stu.ut.edu.sa  

**Omar I. Al-Asiri**  
📧 oasiri@ut.edu.sa  

**Fathi A. Mubaraki**  
📧 f.mubaraki@ut.edu.sa  

## License
This project is licensed under the MIT License.  
See the LICENSE file for details.

### ✅ What does it mean?
It means:
- The project is open-source  
- Anyone can use, modify, and distribute the code  
- They must keep your name/credit  
- You are **not legally responsible** for how others use it  
- The detailed legal text is found inside the `LICENSE` file

## Future Work
- Enhance model performance using deep learning
- Add visualization dashboard
- Automate data collection and labeling
## Acknowledgment
We would like to thank the University of Tabuk for supporting this work.
We also extend our gratitude to our supervisors, Dr. Omar Al-Asiri and Dr. Fathi Mubaraki, for their guidance and valuable support throughout this project.

## Disclaimer
This project is for research purposes only and is not affiliated with the Sehhaty application.
