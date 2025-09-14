# EDA Examples Repository

## Overview

This repository contains comprehensive Exploratory Data Analysis (EDA) examples using advanced analytical methods. Each dataset demonstrates different aspects of data exploration, feature engineering, statistical analysis, and machine learning techniques.

## Repository Structure

```
EDA_Examples/
├── README.md
├── .gitignore
├── Education_Districts/
│   ├── education_districtwise.csv
│   ├── advanced_education_eda.ipynb
│   └── findings.md
├── EPA_Air_Quality/
│   ├── c4_epa_air_quality.csv
│   ├── advanced_epa_air_quality_eda.ipynb
│   ├── EPA_Air_Quality_Analysis_Findings.md
│   └── README.md
└── New_York_Powerball_Winning_Numbers/
    └── New_York_Powerball_Winning_Numbers.csv
```

## Current Datasets

### 1. Education Districts Analysis

**Location**: `Education_Districts/`  
**Dataset**: `education_districtwise.csv` (634 districts across 36 states)  
**Notebook**: `advanced_education_eda.ipynb`  
**Findings**: `findings.md`

#### Analysis Highlights:
- 🔍 **Advanced Statistical Analysis**: Normality testing, correlation analysis, PCA
- 🛠️ **Feature Engineering**: Created 11 new meaningful variables
- 📊 **Machine Learning**: K-means clustering to identify district types
- 📈 **Comprehensive Visualizations**: Distribution plots, correlation heatmaps, scatter plots
- 🎯 **Actionable Insights**: Strategic recommendations for educational policy

#### Key Findings:
- **Population per village** is the strongest predictor of literacy (r=0.248)
- **Three distinct district types** identified through clustering
- **29.9 percentage point gap** between best and worst performing states
- **Administrative efficiency** matters more than infrastructure quantity

### 2. EPA Air Quality Analysis

**Location**: `EPA_Air_Quality/`  
**Dataset**: `c4_epa_air_quality.csv` (260 CO measurements across 52 states)  
**Notebook**: `advanced_epa_air_quality_eda.ipynb`  
**Findings**: `EPA_Air_Quality_Analysis_Findings.md`

#### Analysis Highlights:
- 🌬️ **Environmental Health Focus**: Carbon monoxide concentration analysis
- 📍 **Geographic Coverage**: Comprehensive 52-state monitoring network
- 🔬 **Statistical Rigor**: Multiple normality tests, correlation analysis
- 🤖 **Machine Learning**: K-means clustering (95.9% R² AQI prediction)
- 📊 **Professional Visualizations**: Spatial analysis, temporal patterns
- 🏥 **Public Health Insights**: AQI categorization and health recommendations

#### Key Findings:
- **100% Good Air Quality**: All measurements in "Good" AQI category
- **Geographic Patterns**: Nevada highest CO levels, California most monitored
- **Strong Correlation**: CO concentration perfectly predicts AQI (r=0.96)
- **Public Health**: No health concerns identified nationwide
- **Monitoring Excellence**: 93.3% data completeness across 253 sites

### 3. New York Powerball Winning Numbers

**Location**: `New_York_Powerball_Winning_Numbers/`  
**Dataset**: `New_York_Powerball_Winning_Numbers.csv` (1,838 lottery draws)  
**Status**: 📋 *Dataset available - Analysis in development*

#### Planned Analysis:
- 🎰 **Statistical Pattern Analysis**: Number frequency and distribution
- 📈 **Temporal Trends**: Drawing patterns over time
- 🔢 **Probability Modeling**: Random vs pattern-based number selection
- 📊 **Visualization**: Hot/cold numbers, multiplier analysis
- 🎯 **Insights**: Lottery statistics and randomness validation

## Getting Started

### Prerequisites

```bash
# Python packages required
pip install pandas numpy matplotlib seaborn plotly scipy scikit-learn
```

### Running the Analysis

1. **Clone the repository**:
```bash
git clone https://github.com/dustinober1/EDA_Examples.git
cd EDA_Examples
```

2. **Navigate to the desired analysis**:
```bash
cd Education_Districts
```

3. **Open the Jupyter notebook**:
```bash
jupyter notebook advanced_education_eda.ipynb
```

4. **Run all cells** to reproduce the complete analysis

## Methodology

### Advanced EDA Techniques Used

#### 1. **Data Quality Assessment**
- Missing value analysis and handling
- Duplicate detection
- Data type validation
- Consistency checks

#### 2. **Statistical Analysis**
- Descriptive statistics with advanced measures (skewness, kurtosis)
- Normality testing (Shapiro-Wilk, D'Agostino, Jarque-Bera)
- Correlation analysis (Pearson and Spearman)
- Statistical significance testing

#### 3. **Feature Engineering**
- Population density metrics
- Infrastructure efficiency ratios
- Administrative coverage indicators
- Categorical encoding
- Composite indices

#### 4. **Advanced Visualization**
- Distribution analysis with KDE curves
- Box plots for outlier detection
- Correlation heatmaps
- Bivariate scatter plots with regression lines
- Q-Q plots for normality assessment

#### 5. **Machine Learning Integration**
- Principal Component Analysis (PCA)
- K-means clustering with optimal cluster determination
- Silhouette analysis for cluster validation

## Project Goals

This repository aims to:

1. **Demonstrate Best Practices** in exploratory data analysis
2. **Showcase Advanced Techniques** beyond basic statistics
3. **Provide Actionable Insights** from real-world datasets
4. **Serve as Educational Resource** for data science learning
5. **Build a Library** of comprehensive EDA examples

## Analysis Standards

Each analysis in this repository follows these standards:

### 📋 **Completeness**
- ✅ Data quality assessment
- ✅ Missing value handling
- ✅ Statistical testing
- ✅ Feature engineering
- ✅ Advanced visualizations
- ✅ Machine learning integration
- ✅ Comprehensive findings document

### 🔬 **Rigor**
- Statistical significance testing
- Multiple correlation methods
- Normality assessment
- Outlier detection and analysis
- Cross-validation where applicable

### 📊 **Visualization Quality**
- Professional, publication-ready plots
- Clear labeling and legends
- Appropriate color schemes
- Multiple visualization types
- Interactive elements where beneficial

### 📝 **Documentation**
- Detailed code comments
- Markdown explanations
- Methodology notes
- Limitations discussion
- Future research directions

## Future Datasets

Planned additions to this repository:

- **New York Powerball Analysis**: Statistical pattern analysis of lottery drawings (data ready)
- **Healthcare Analytics**: Patient outcomes and treatment effectiveness  
- **Financial Markets**: Stock performance and economic indicators
- **Customer Analytics**: Behavior patterns and segmentation
- **Sports Analytics**: Performance metrics and team analysis

## Contributing

We welcome contributions! Please follow these guidelines:

1. **Fork the repository**
2. **Create a new branch** for your dataset analysis
3. **Follow the established methodology** and documentation standards
4. **Include comprehensive findings** document
5. **Submit a pull request** with detailed description

### Contribution Standards:
- Complete EDA following repository methodology
- High-quality visualizations
- Statistical rigor and significance testing
- Feature engineering where appropriate
- Comprehensive documentation
- Actionable insights and recommendations

## Technical Requirements

### Minimum Requirements:
- Python 3.8+
- Jupyter Notebook or JupyterLab
- 4GB RAM minimum
- Required packages: pandas, numpy, matplotlib, seaborn, plotly, scipy, scikit-learn

### Recommended Setup:
- Python 3.9+
- 8GB+ RAM for large datasets
- GPU acceleration for complex ML operations
- VS Code with Python extension for development

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- **Author**: Dustin Ober
- **GitHub**: [@dustinober1](https://github.com/dustinober1)
- **Repository**: [EDA_Examples](https://github.com/dustinober1/EDA_Examples)

## Acknowledgments

- Educational data providers for making datasets available
- Open source community for excellent Python libraries
- Contributors and reviewers for improving the analyses

---

## Quick Start Example

```python
# Quick start examples for multiple datasets

# Education Districts Analysis
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Load education data
df_edu = pd.read_csv('Education_Districts/education_districtwise.csv')
print(f"Education Dataset shape: {df_edu.shape}")
print(f"Average literacy rate: {df_edu['OVERALL_LI'].mean():.1f}%")

# EPA Air Quality Analysis
df_epa = pd.read_csv('EPA_Air_Quality/c4_epa_air_quality.csv')
print(f"EPA Dataset shape: {df_epa.shape}")
print(f"Average CO concentration: {df_epa['arithmetic_mean'].mean():.3f} ppm")
print(f"Average AQI: {df_epa['aqi'].mean():.1f}")

# Quick visualization comparison
fig, axes = plt.subplots(1, 2, figsize=(15, 6))

# Education literacy distribution
axes[0].hist(df_edu['OVERALL_LI'], bins=30, alpha=0.7, color='blue')
axes[0].set_title('Distribution of Literacy Rates')
axes[0].set_xlabel('Literacy Rate (%)')
axes[0].set_ylabel('Frequency')

# EPA CO concentration distribution  
axes[1].hist(df_epa['arithmetic_mean'], bins=30, alpha=0.7, color='green')
axes[1].set_title('Distribution of CO Concentrations')
axes[1].set_xlabel('CO Concentration (ppm)')
axes[1].set_ylabel('Frequency')

plt.tight_layout()
plt.show()
```

For the complete analysis, see the full notebook in each dataset folder.

---

*This repository is actively maintained and updated with new datasets and improved methodologies.*