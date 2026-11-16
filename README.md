# Final Bioinformatics Report – SWYNEX Technologies

## Project Title
**Exploratory Analysis and Visualization of Gene Expression Data in Type 2 Diabetes Using Python**

## 1. Project Overview

This project presents the final report of my Bioinformatics Internship at SWYNEX Technologies.

The project focuses on exploring gene-expression patterns in individuals with Type 2 Diabetes and non-diabetic controls using the NCBI Gene Expression Omnibus (GEO) dataset GSE20966.

Python-based data processing, descriptive statistical analysis, and visualization techniques were used to examine the dataset and interpret expression patterns.

## 2. Research Question

What differences in gene-expression patterns can be explored between pancreatic beta-cell-enriched tissue samples from individuals with Type 2 Diabetes and non-diabetic controls?

## 3. Dataset Information

- **Dataset ID:** GSE20966
- **Source:** NCBI Gene Expression Omnibus (GEO)
- **Organism:** Homo sapiens
- **Platform:** GPL1352 – Affymetrix Human X3P Array
- **Total Samples:** 20
- **Control Samples:** 10
- **Type 2 Diabetes Samples:** 10
- **Probe Identifiers:** 61,295

**Dataset Link:**  
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE20966

## 4. Project Objectives

- Retrieve and explore a public gene-expression dataset.
- Perform initial data-quality checks.
- Calculate descriptive statistical measurements.
- Compare expression patterns between control and diabetes samples.
- Generate meaningful data visualizations.
- Interpret the results and identify scientific limitations.

## 5. Methodology

The project was carried out using the following steps:

1. Dataset selection and retrieval from NCBI GEO.
2. Loading the processed expression matrix into Python.
3. Data inspection and quality assessment.
4. Calculation of sample-level descriptive statistics.
5. Visualization of expression distributions.
6. Sample correlation analysis.
7. Principal Component Analysis (PCA).
8. Control versus Type 2 Diabetes group comparison.
9. Interpretation of findings and documentation of limitations.

## 6. Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

## 7. Key Results and Observations

- The expression matrix contained 61,295 probe identifiers and 20 samples.
- Initial quality checks found no missing values or duplicate probe identifiers.
- Expression distribution and sample correlation patterns were explored using visualizations.
- PCA showed partial separation between control and diabetes samples.
- PC1 explained 12.84% of the variance, while PC2 explained 9.00%.
- The first two principal components together explained 21.84% of the total variance.
- Group comparison revealed differences in average expression signals among selected probes.

These findings are exploratory and descriptive. They do not establish statistical significance or prove a causal relationship with Type 2 Diabetes.

## 8. Repository Structure

```text
SWYNEX-Final-Bioinformatics-Report/
│
├── README.md
├── SWYNEX_Final_Bioinformatics_Report.docx
│
├── Figures/
│   ├── expression_boxplot.png
│   ├── correlation_heatmap.png
│   ├── PCA_plot_labeled.png
│   └── group_comparison_clean.png
│
└── Supporting_Files/
    ├── sample_statistics.csv
    └── control_vs_diabetes.csv
```

## 9. Scientific Limitations

- The analysis used processed GEO expression data.
- Probe identifiers were not comprehensively mapped to gene symbols.
- Formal differential-expression statistical testing was not performed.
- PCA separation does not establish statistical significance.
- Unusual measurements require further investigation.
- The results should not be interpreted as proof of causation.

## 10. Conclusion

This project provided an exploratory understanding of gene-expression patterns in Type 2 Diabetes using Python-based bioinformatics techniques.

The analysis demonstrated the application of data processing, descriptive statistics, sample correlation, PCA, and visualization methods in biological data analysis.

The project also highlighted the importance of data-quality assessment, cautious interpretation, and further statistical validation.

## 11. Final Report

The complete internship report is available in this repository:

**SWYNEX_Final_Bioinformatics_Report.docx**

## 12. Acknowledgement

I sincerely thank SWYNEX Technologies for providing me with the opportunity to work on this Bioinformatics Internship project.

This experience helped me develop practical knowledge of Python programming, gene-expression data analysis, bioinformatics tools, and scientific data interpretation.

## References

1. NCBI Gene Expression Omnibus – GSE20966: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE20966
2. NCBI GEO Platform – GPL1352: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GPL1352
3. Pedregosa et al. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12, 2825–2830.
