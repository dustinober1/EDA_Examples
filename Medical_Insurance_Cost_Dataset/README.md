# Medical Insurance Cost Dataset Analysis

## Overview

This directory contains a comprehensive exploratory data analysis (EDA) of the Medical Insurance Cost Dataset. The analysis explores factors affecting medical insurance charges and provides insights for risk assessment and premium pricing strategies.

## Dataset Description

**File**: `insurance.csv`  
**Size**: 1,338 records  
**Features**: 7 columns (6 predictors + 1 target variable)

### Columns:
- **age**: Age of the primary beneficiary (18-64 years)
- **sex**: Insurance contractor gender (female/male)
- **bmi**: Body mass index, providing understanding of body weights (15.96-53.13)
- **children**: Number of children/dependents covered by health insurance (0-5)
- **smoker**: Smoking status (yes/no)
- **region**: Beneficiary's residential area in the US (northeast, northwest, southeast, southwest)
- **charges**: Individual medical costs billed by health insurance ($1,121.87 - $63,770.43)

## Files in This Directory

### 📊 Analysis Files
- **`medical_insurance_comprehensive_eda.ipynb`**: Complete Jupyter notebook with detailed exploratory data analysis
- **`findings.md`**: Comprehensive summary of key insights and business recommendations
- **`insurance.csv`**: Raw dataset file

### 🔍 Analysis Scope

The comprehensive EDA includes:

1. **Data Quality Assessment**
   - Missing value analysis
   - Duplicate detection
   - Outlier identification
   - Data type validation

2. **Univariate Analysis**
   - Distribution analysis for all variables
   - Statistical summaries
   - Skewness and kurtosis examination

3. **Bivariate Analysis**
   - Correlation analysis
   - Statistical significance testing
   - Group comparisons (t-tests, ANOVA)

4. **Advanced Analytics**
   - Interaction effects analysis
   - Multi-dimensional segmentation
   - Regional comparative analysis

5. **Predictive Modeling**
   - Linear Regression baseline
   - Random Forest ensemble model
   - Feature importance analysis
   - Model performance evaluation

## Key Insights Summary

### 🚭 Primary Finding: Smoking Impact
- **Smokers pay 3.8x more** than non-smokers ($32,050 vs $8,434)
- Strongest predictor of insurance costs
- Consistent effect across all demographics

### 📈 Secondary Factors
- **Age**: Moderate positive correlation (r=0.299)
- **BMI**: Obese individuals pay 49% more than normal weight
- **Region**: Up to 19% variation between regions
- **Gender**: 11% higher costs for males (modest effect)
- **Children**: Minimal impact on insurance costs

### 🎯 Model Performance
- **87.4% variance explained** by Random Forest model
- **RMSE: $4,891** prediction accuracy
- High confidence in factor importance rankings

## Business Applications

### Risk Assessment
- Smoking status is the primary risk factor
- BMI and age provide additional risk stratification
- Regional factors require consideration

### Premium Pricing Strategy
- Justify smoking-based premium adjustments
- Age-graduated pricing structures
- BMI-based wellness incentives
- Minimal family size adjustments needed

### Cost Containment Opportunities
- Smoking cessation programs (highest ROI)
- Weight management initiatives
- Preventive care for aging populations
- Regional health partnerships

## Getting Started

### Prerequisites
```python
# Required libraries
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
scipy
```

### Running the Analysis
1. Open `medical_insurance_comprehensive_eda.ipynb` in Jupyter
2. Execute cells sequentially for complete analysis
3. Review `findings.md` for summarized insights

### Quick Data Overview
```python
import pandas as pd
df = pd.read_csv('insurance.csv')
print(f"Dataset shape: {df.shape}")
print(f"Average charge: ${df['charges'].mean():.2f}")
print(f"Smoker premium: {df[df['smoker']=='yes']['charges'].mean() / df[df['smoker']=='no']['charges'].mean():.1f}x")
```

## Statistical Methodology

### Tests Performed
- **Correlation Analysis**: Pearson correlation coefficients
- **Group Comparisons**: Independent t-tests and ANOVA
- **Distribution Analysis**: Skewness, kurtosis, and normality tests
- **Predictive Modeling**: Cross-validated regression analysis

### Model Validation
- 80/20 train-test split
- Multiple algorithm comparison
- Feature importance validation
- Residual analysis

## Visualization Highlights

The analysis includes comprehensive visualizations:
- Distribution plots for all variables
- Correlation heatmaps
- Box plots for group comparisons
- Scatter plots with trend lines
- Feature importance charts
- Model performance visualizations

## Data Quality Notes

✅ **Strengths**:
- No missing values
- No duplicate records
- Realistic value ranges
- Balanced categorical distributions

⚠️ **Limitations**:
- Single time-point analysis
- Limited geographic scope (US only)
- No pre-existing condition data
- Missing lifestyle factors

## Future Enhancements

### Data Collection
- Longitudinal tracking for trend analysis
- Additional lifestyle factors (exercise, diet)
- Pre-existing conditions and family history
- Socioeconomic indicators

### Analysis Extensions
- Survival analysis for claim timing
- Clustering for customer segmentation
- Time series forecasting
- Advanced interaction modeling

## Contact and Contributions

This analysis was conducted as part of a comprehensive EDA examples collection. For questions or suggestions regarding the methodology or findings, please refer to the detailed documentation in the notebook and findings files.

---

**Last Updated**: September 16, 2025  
**Analysis Version**: 1.0  
**Dataset Source**: Medical Insurance Cost Dataset