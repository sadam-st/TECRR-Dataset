# TECRR-Dataset
Breast Imaging-Based Radiological Reports Dataset and ML, DL and LLMs-Based Baselines

# Breast Imaging-Based Radiological Reports Dataset  

A curated and annotated dataset for BI-RADS and breast density classification with benchmark results.

---

## Background  

This dataset addresses the need for a high-quality annotated dataset for the classification of radiological reports based on BI-RADS categories and breast density scores, as characterized by the American College of Radiology (ACR). Currently, there are no publicly available datasets for this purpose.  

The dataset was collected and annotated by board-certified radiologists at the Breast Radiology department, TecSalud Hospitals Monterrey, Mexico. The original dataset, in Spanish, was translated into English using Google Translate and further preprocessed to remove duplicates and missing values.  

### Key Features:  
- **Total Reports:** 5,046 unique radiological reports.  
- **Patient Demographics:**  
  - Average age: 53 years.  
  - Gender: 100% women.  
- **Annotations:** Based on the BI-RADS lexicon and categories.  
- **Preprocessing:** Translation, duplicate removal, and handling of missing values.  

---

## Dataset Details  

- **Language:** English (originally in Spanish).  
- **Source:** Breast Radiology department, TecSalud Hospitals Monterrey, Mexico.  
- **Content:** Radiological reports for breast imaging with BI-RADS and breast density scores.  

---

## Baseline Models and Results  

The dataset was evaluated using multiple machine learning (ML), deep learning (DL), and large language models (LLMs) for BI-RADS category classification. Baseline results are provided as benchmarks for future studies.  

### **Benchmark Results**  
| Classifier                | Mean Sensitivity | 95% Confidence Interval (CI)     |  
|---------------------------|------------------|----------------------------------|  
| BioGPT                    | 0.60            | (0.391–0.812)                     |  
| BERT                      | 0.54            | (0.477–0.607)                     |  
| Long Short-Term Memory (LSTM) | *Varies*   | *Details in paper*                 |  
| Support Vector Machine (SVM) | *Varies*    | *Details in paper*                 |  

- **Best Model:** BioGPT, which performed 6% better than BERT in sensitivity.  
- **Embedding Techniques:** TF-IDF, Word2Vec for semantic and syntactic analysis.  

### **Models Evaluated:**  
- **ML Models:** K-Nearest Neighbour (KNN), Support Vector Machine (SVM), Naive Bayes (NB), Random Forest (RF), Adaptive Boosting (AdaBoost), Gradient Boosting (GB), Extreme Gradient Boosting (XGB).  
- **DL Models:** Long Short-Term Memory (LSTM), BERT.  
- **LLMs:** Biomedical Generative Pre-trained Transformer (BioGPT).  

---

## Dataset Use  

This dataset is designed to support research and development in:  
- **BI-RADS Classification:** Categorization of breast imaging reports based on ACR guidelines.  
- **Breast Density Scoring:** Assigning density scores to reports for clinical decision-making.  
- **NLP in Radiology:** Developing machine learning, deep learning, and large language models for free-form radiological reports.  

### Objectives:  
- To provide a benchmark dataset for researchers entering the field.  
- To establish baseline results for future investigation.  

---

## How to Use the Dataset  

1. **Clone the Repository:**  
   ```bash  
   git clone https://github.com/your-username/radiology-birads-dataset.git

To cite our work:
  ```bash
@article{hussain2024tecrr,
  title={TECRR: a benchmark dataset of radiological reports for BI-RADS classification with machine learning, deep learning, and large language model baselines},
  author={Hussain, Sadam and Naseem, Usman and Ali, Mansoor and Avenda{\~n}o Avalos, Daly Betzabeth and Cardona-Huerta, Servando and Bosques Palomo, Beatriz Alejandra and Tamez-Pe{\~n}a, Jose Gerardo},
  journal={BMC Medical Informatics and Decision Making},
  volume={24},
  number={1},
  pages={310},
  year={2024},
  publisher={Springer}
}
```

## Contact

Please feel free to contact me if you require any further information.
Email: sadamteewino@gmail.com

