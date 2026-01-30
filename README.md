## Project Description

This research focuses on analyzing the performance of hybrid machine learning models using the Air Quality Index (AQI) dataset from New Delhi.  
The primary objective is to evaluate and compare different hybrid and baseline model configurations, and to assess their effectiveness through empirical experimentation and result analysis.


---

## Repository Structure

```text
├── data/            # Datasets used in the study (if shareable)
├── src/             # Source code for experiments and analysis
├── appendix/        # Appendix and supplementary materials
├── figures/         # Plots and graphs used in the paper
├── paper/           # Final IEEE-accepted manuscript
└── README.md
```

---

## Methodology

The study follows a structured experimental pipeline comprising the following stages:

### 1. Data Processing
- Data preprocessing
- Missing value imputation

### 2. Model and Algorithm Implementation

Experiments are performed using the following model configurations:

#### Base Models
- With both PCA and ARIMA
- With PCA only
- With ARIMA only
- Without PCA and ARIMA

#### Hybrid Models
- With both PCA and ARIMA
- With PCA only
- With ARIMA only
- Without PCA and ARIMA

### 3. Experimental Evaluation
- Model training and testing
- Performance evaluation across different configurations

### 4. Result Analysis and Visualization
- Comparative performance analysis
- Visualization of experimental results


---

## Publication

This work has been accepted for publication in an IEEE conference.

**Citation**
Rajhans, Abhijeet, Ayush Dubey, and Akshay Jadhav. "Analyzing Hybrid Machine Learning Performance Through Air Quality Prediction." In 2025 International Conference on Computing Technologies & Data Communication (ICCTDC), pp. 1-7. IEEE, 2025.

---

## Requirements

The experiments were conducted using:
- Python 3.10
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

## Limitations

Due to data loss, a small portion of the experimental code could not be recovered.  
However, all final results, visualizations, and the accepted manuscript are preserved. It may also be noted that due to the presence of multiple codes and iterations for each analysis segment, the codes in the repo may have the possibility to not be fully correct. In such cases, please reach out :)

---

## Reproducibility

While full reproducibility may not be possible due to missing code components,  
the available scripts and datasets can be used to replicate key parts of the analysis.

---

## Contact

For questions or collaboration inquiries, please contact:

**Abhijeet Rajhans**  
Email: abhijeetrajhans.ar@gmail.com

---
## License

No license is provided with this repository.  
All contents are © the authors and are protected under full copyright.

The materials are shared for academic reference only.  
Any reuse, modification, redistribution, or commercial use requires prior permission from the authors.  
Please cite the original paper if you reference this work.


