# Contributing to EDA Examples

Thank you for your interest in contributing to the EDA Examples repository! This guide will help you add new exploratory data analysis examples.

## How to Contribute

### 1. Choose a Dataset
- Select an interesting dataset that would be valuable for educational purposes
- Ensure the dataset is publicly available or has appropriate licensing
- Consider datasets that demonstrate different EDA techniques or data types

### 2. Prepare Your Contribution

#### Directory Structure
Create a new directory under `examples/` with a descriptive name:
```
examples/your_dataset_name_eda/
├── your_dataset_name_eda.ipynb
├── README.md
└── requirements.txt (if additional dependencies needed)
```

#### Dataset Storage
- Small datasets (< 10MB): Place in `datasets/your_dataset_name/`
- Large datasets: Provide download instructions and scripts
- Always include data source and licensing information

### 3. Use the Templates
Start with the provided templates in the `templates/` directory:
- Copy `eda_template.ipynb` as your starting notebook
- Copy `README_template.md` and customize it for your dataset

### 4. Notebook Guidelines

#### Structure Your Analysis
1. **Clear Introduction**: Explain the dataset and analysis goals
2. **Data Loading**: Include data source and loading code
3. **Data Cleaning**: Address missing values, duplicates, outliers
4. **Exploratory Analysis**: 
   - Univariate analysis (distributions, summary statistics)
   - Bivariate analysis (correlations, relationships)
   - Multivariate analysis (if applicable)
5. **Visualizations**: Use appropriate charts and plots
6. **Key Insights**: Summarize important findings
7. **Conclusions**: Provide actionable insights and next steps

#### Code Quality
- Use clear, descriptive variable names
- Add comments explaining complex operations
- Include markdown cells to explain your thinking
- Ensure all cells run successfully
- Remove or comment out experimental code

#### Visualizations
- Use appropriate chart types for your data
- Include clear titles, labels, and legends
- Consider using multiple visualization libraries (matplotlib, seaborn, plotly)
- Make plots accessible (consider colorblind-friendly palettes)

### 5. Documentation Requirements

#### README.md
Your example's README should include:
- Dataset description and source
- Key questions being explored
- Main findings and insights
- Instructions for running the analysis
- Any additional dependencies

#### Notebook Documentation
- Use markdown cells to create a narrative
- Explain why you're performing each analysis step
- Interpret your visualizations and findings
- Include data dictionary if variables aren't self-explanatory

### 6. Dependencies
- Use common libraries when possible (see main requirements.txt)
- Only add new dependencies if necessary
- Document any additional requirements in your example's requirements.txt
- Test that your notebook runs with the specified dependencies

### 7. Submission Process

1. **Fork the Repository**
   ```bash
   git fork https://github.com/dustinober1/EDA_Examples.git
   ```

2. **Create a Feature Branch**
   ```bash
   git checkout -b add-[dataset-name]-eda
   ```

3. **Add Your Files**
   - Create your directory structure
   - Add your notebook, README, and any additional files
   - Update the main README.md to include your example in the table

4. **Test Your Contribution**
   - Ensure your notebook runs from start to finish
   - Check that all visualizations display correctly
   - Verify file paths and data loading work

5. **Submit a Pull Request**
   - Include a clear description of your contribution
   - Mention any interesting findings or techniques used
   - Reference any issues your contribution addresses

### 8. Example Quality Standards

#### Good Examples Include:
- Clear problem statement and questions
- Thorough data exploration
- Multiple visualization techniques
- Insightful interpretations
- Actionable conclusions
- Clean, well-commented code
- Comprehensive documentation

#### Avoid:
- Overly simple analyses without insights
- Unclear or uncommented code
- Missing data source attribution
- Notebooks that don't run completely
- Poor or missing documentation

### 9. Dataset Guidelines

#### Preferred Dataset Characteristics:
- Educational value (demonstrates EDA techniques)
- Reasonable size (< 100MB preferred)
- Clean enough to focus on analysis, not just cleaning
- Interesting patterns or stories to discover
- Publicly available with clear licensing

#### Dataset Categories We Welcome:
- Business/Economics data
- Scientific/Research data
- Social media/Web data
- Sports/Entertainment data
- Government/Public data
- Health/Medical data (properly anonymized)
- Educational datasets

### 10. Code of Conduct
- Be respectful and constructive in all interactions
- Provide helpful feedback on others' contributions
- Focus on educational value and code quality
- Respect data privacy and licensing requirements

### 11. Questions or Help
If you have questions or need help:
- Open an issue for discussion
- Tag maintainers for guidance
- Check existing examples for inspiration

Thank you for contributing to the EDA Examples repository!