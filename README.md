# Early Detection of Parkinson’s Disease

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📖 Overview
This project investigates whether **proteomic biomarkers** can enable the **early detection of Parkinson’s Disease** using blood samples.  

It combines:
- Data from **proteomic blood assays**
- Feature engineering and biomarker filtering
- Machine learning models for classification
- Exploratory data analysis and visualization

The goal is to assess if specific biomarkers can distinguish **healthy controls** from **Parkinson’s patients** in early stages.

---

## 📂 Repository Structure <br>
Early-Detection-of-Parkinsons/<br>
├── Toward_Early_Detection_of_Parkinsons_Disease.ipynb # Main analysis notebook <br>
├── Toward Early Detection of Parkinson’s Disease.pdf # Paper/summary report<br>
├── filtered_BIO_pivot_df.csv # Processed biomarker dataset <br>
├── LICENSE # MIT license <br>
└── README.md # Project overview <br>


---

## ⚙️ Requirements & Setup

1. **Clone the repository:** <br>
   ```bash<br>
   git clone https://github.com/jcjaylani/Early-Detection-of-Parkinsons.git<br>
   cd Early-Detection-of-Parkinsons<br>

2. **Install required libraries** (recommend using a virtual environment):<br>
pip install pandas, numpy, matplotlib, seaborn, scikit-learn<br>

3. **Open the Jupyter notebook:** <br>
jupyter notebook Toward_Early_Detection_of_Parkinsons_Disease.ipynb<br>

## 🔬 Analysis Pipeline

- Data Preparation: Load and filter biomarker data

- Exploratory Analysis: Distribution plots, missingness, correlations

- Feature Engineering: Identify candidate proteomic biomarkers

- Modeling: Apply classification models (Logistic Regression, Random Forest, etc.)

- Evaluation: Compare accuracy, precision/recall, ROC-AUC

- Interpretation: Highlight potential biomarkers for early-stage detection

## 📊 Example Visualizations

<img width="906" height="1109" alt="Screenshot 2025-09-24 133246" src="https://github.com/user-attachments/assets/73e8fab1-e0f9-4cb4-95fa-9ed1b13b8d27" />
<img width="695" height="448" alt="Screenshot 2025-09-24 133103" src="https://github.com/user-attachments/assets/1171eaa5-dd15-4c51-a740-8b089b52b6dc" />
<br>

#### Analysis of top feature Homovanillic Acid

<img width="1264" height="325" alt="Screenshot 2025-09-24 133228" src="https://github.com/user-attachments/assets/09d6d3da-fe68-4861-9035-4bf2e180df94" />

---
## 📜 License

This project is licensed under the MIT License
.

## 🙌 Acknowledgments

Data used in the preparation of this article were obtained on 2024-09-18 from the Parkinson’s Progression Markers Initiative (PPMI) database (https://www.ppmi-info.org/access-data-specimens/download-data), RRID:SCR_006431. For up-to-date information on the study, visit http://www.ppmi-info.org.

PPMI PARTNER ACKNOWLEDGEMENTS
PPMI – a public-private partnership – is funded by the Michael J. Fox Foundation for Parkinson’s Research and funding partners, including 4D Pharma, Abbvie, AcureX, Allergan, Amathus Therapeutics, Aligning Science Across Parkinson's, AskBio, Avid Radiopharmaceuticals, BIAL, BioArctic, Biogen, Biohaven, BioLegend, BlueRock Therapeutics, Bristol-Myers Squibb, Calico Labs, Capsida Biotherapeutics, Celgene, Cerevel Therapeutics, Coave Therapeutics, DaCapo Brainscience, Denali, Edmond J. Safra Foundation, Eli Lilly, Gain Therapeutics, GE HealthCare, Genentech, GSK, Golub Capital, Handl Therapeutics, Insitro, Jazz Pharmaceuticals, Johnson & Johnson Innovative Medicine, Lundbeck, Merck, Meso Scale Discovery, Mission Therapeutics, Neurocrine Biosciences, Neuron23, Neuropore, Pfizer, Piramal, Prevail Therapeutics, Roche, Sanofi, Servier, Sun Pharma Advanced Research Company, Takeda, Teva, UCB, Vanqua Bio, Verily, Voyager Therapeutics, the Weston Family Foundation and Yumanity Therapeutics.
