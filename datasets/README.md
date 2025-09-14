# Datasets Directory

This directory contains the datasets used in the EDA examples. Datasets are organized by name/topic.

## Directory Structure

- `iris/` - Iris flower measurements dataset (loaded from scikit-learn)
- `samples/` - Small sample datasets for quick examples
- `[dataset_name]/` - Specific dataset directories

## Guidelines for Adding Datasets

### File Organization
```
datasets/your_dataset_name/
├── README.md              # Dataset description and source
├── data.csv              # Main dataset file(s)
├── data_dictionary.txt   # Variable descriptions
└── LICENSE.txt           # Data license (if applicable)
```

### Dataset Size Guidelines
- **Small datasets** (< 10MB): Include directly in the repository
- **Medium datasets** (10MB - 100MB): Consider using Git LFS
- **Large datasets** (> 100MB): Provide download scripts and instructions

### Required Documentation
Each dataset directory should include:
1. **README.md** with:
   - Data source and collection method
   - Variable descriptions
   - Any preprocessing applied
   - License information
   - Citation requirements

2. **Data dictionary** explaining each column/variable

### Licensing
- Only include datasets with appropriate licensing for educational/research use
- Always attribute the original data source
- Include license files when required

## Common Data Sources
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [Google Dataset Search](https://datasetsearch.research.google.com/)
- [Data.gov](https://www.data.gov/)
- [World Bank Open Data](https://data.worldbank.org/)
- [FiveThirtyEight Data](https://data.fivethirtyeight.com/)

## Notes
- The iris dataset is loaded programmatically from scikit-learn and doesn't require files here
- Check existing examples before adding new datasets
- Consider the educational value and diversity of analysis techniques each dataset enables