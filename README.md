# EDA Examples Repository

This repository contains a collection of Exploratory Data Analysis (EDA) examples for various datasets. Each example demonstrates different techniques and approaches for understanding and visualizing data.

## Repository Structure

```
EDA_Examples/
├── datasets/
│   ├── titanic/
│   ├── iris/
│   ├── housing/
│   └── ...
├── examples/
│   ├── titanic_eda/
│   │   ├── titanic_eda.ipynb
│   │   ├── README.md
│   │   └── requirements.txt
│   ├── iris_eda/
│   │   ├── iris_eda.ipynb
│   │   ├── README.md
│   │   └── requirements.txt
│   └── ...
├── templates/
│   ├── eda_template.ipynb
│   └── README_template.md
├── requirements.txt
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/dustinober1/EDA_Examples.git
   cd EDA_Examples
   ```

2. Install common dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Navigate to any example directory and follow its specific README instructions.

## Available Examples

| Dataset | Description | Notebook | Key Techniques |
|---------|-------------|----------|----------------|
| Iris | Classic dataset with flower measurements from 3 species | [iris_eda.ipynb](examples/iris_eda/iris_eda.ipynb) | Correlation analysis, pair plots, 3D visualization, statistical testing |

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on how to add new EDA examples.

### Adding a New EDA Example

1. Create a new directory under `examples/` with a descriptive name
2. Use the template files in `templates/` as a starting point
3. Include a well-documented Jupyter notebook
4. Add a README.md explaining the dataset and analysis
5. List any additional dependencies in requirements.txt
6. Update this main README with your example

## Common Tools and Libraries

The examples in this repository commonly use:
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Basic plotting
- **seaborn** - Statistical visualization
- **plotly** - Interactive visualizations
- **scipy** - Scientific computing
- **scikit-learn** - Machine learning preprocessing

## License

This project is open source. Please check individual dataset licenses before using them in commercial projects.