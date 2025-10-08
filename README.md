# IDATG2208 Assignment 2 - Machine Learning Exercises

This repository contains a comprehensive machine learning assignment with four exercises covering fundamental ML concepts and algorithms.

## 📋 Assignment Overview

This assignment focuses on practical implementation and comparison of machine learning algorithms, specifically:

- **Exercise 1: Data Preparation** - Data preprocessing, cleaning, and feature engineering
- **Exercise 2: Decision Trees** - Implementation and analysis of Decision Tree algorithms
- **Exercise 3: Support Vector Machines (SVM)** - SVM implementation with different kernels
- **Exercise 4: Model Comparison** - Comprehensive comparison of ML algorithms

**Total Points: 100**

## 🗂️ Repository Structure

```
idatg2208-assignment-2/
├── notebooks/                          # Jupyter notebooks for each exercise
│   ├── 01_Data_Preparation.ipynb
│   ├── 02_Decision_Trees.ipynb
│   ├── 03_Support_Vector_Machines.ipynb
│   └── 04_Model_Comparison.ipynb
├── data/                               # Dataset storage
├── models/                             # Saved models and related files
├── reports/                            # Analysis reports and visualizations
│   ├── tables/
│   └── figures/
├── .gitignore                          # Git ignore file
├── requirements.txt                    # Python dependencies
└── README.md                           # This file
```

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Required Python packages (see installation section)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/SigurdRiseth/idatg2208-assignment-2.git
cd idatg2208-assignment-2
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter mlxtend graphviz scipy
```

Or create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter mlxtend graphviz scipy
```

3. Start Jupyter:
```bash
jupyter notebook
```

## 📚 Exercise Details

### Exercise-1: Data Preparation [10 points]
**File:** `notebooks/Exercise-1_Data_Preparation.ipynb`

**Learning Objectives:**
- Data loading and exploration
- Data cleaning and preprocessing
- Feature engineering and selection
- Data splitting for ML workflows

**Key Topics:**
- Exploratory Data Analysis (EDA)
- Missing value handling
- Outlier detection and treatment
- Feature scaling and encoding
- Train-test splitting

### Exercise-2: Decision Trees [30 points]
**File:** `notebooks/Exercise-2_Decision_Trees.ipynb`

**Learning Objectives:**
- Understanding Decision Tree algorithms
- Hyperparameter tuning and optimization
- Tree visualization and interpretation
- Overfitting analysis and prevention

**Key Topics:**
- Decision Tree implementation
- Feature importance analysis
- Hyperparameter optimization (max_depth, min_samples_split, etc.)
- Cross-validation
- Learning curves and overfitting analysis

### Exercise-3: Support Vector Machines [30 points]
**File:** `notebooks/Exercise-3_Support_Vector_Machines.ipynb`

**Learning Objectives:**
- SVM algorithm implementation
- Kernel functions and their effects
- Hyperparameter tuning for SVMs
- Decision boundary analysis

**Key Topics:**
- Linear and non-linear SVMs
- Kernel tricks (RBF, polynomial, sigmoid)
- Regularization parameter (C) optimization
- Support vector analysis
- Decision boundary visualization

### Exercise-4: Model Comparison [30 points]
**File:** `notebooks/Exercise-4_Model_Comparison.ipynb`

**Learning Objectives:**
- Systematic model comparison
- Statistical significance testing
- Performance vs. complexity analysis
- Model selection criteria

**Key Topics:**
- Comprehensive model evaluation
- Cross-validation comparison
- Statistical significance testing
- Bias-variance trade-off analysis
- Computational efficiency analysis
- Final model recommendation

## 📊 Dataset Requirements

Each exercise expects preprocessed data from Exercise-1. You should:

1. **Add your dataset** to the `data/` directory
2. **Complete Exercise-1** first to prepare the data
3. **Save preprocessed data** for use in subsequent exercises

Common dataset formats supported:
- CSV files
- JSON files
- Excel files (with pandas)

## 🔧 Technical Requirements

### Python Packages Used:
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **matplotlib & seaborn**: Data visualization
- **scikit-learn**: Machine learning algorithms
- **jupyter**: Interactive notebook environment
- **mlxtend**: Additional ML tools and visualizations
- **scipy**: Statistical analysis

### Hardware Recommendations:
- Minimum 4GB RAM
- Multi-core processor recommended for GridSearchCV operations

## 📈 Expected Deliverables

1. **Completed Jupyter Notebooks** with:
   - All code cells executed
   - Proper markdown documentation
   - Visualizations and analysis
   - Reflection questions answered

2. **Data Files** (in `data/` directory):
   - Original dataset
   - Preprocessed data files

3. **Reports** (in `reports/` directory):
   - Exported visualizations
   - Model comparison summaries
   - Performance analysis reports

## 🎯 Assessment Criteria

- **Code Quality**: Clean, well-documented, and functional code
- **Analysis Depth**: Thorough exploration and interpretation of results
- **Visualization**: Clear and informative plots and charts
- **Model Understanding**: Demonstration of ML concept comprehension
- **Reflection**: Thoughtful answers to reflection questions

## 🤝 Contributing

This is an academic assignment. Please ensure your work is original and follows academic integrity guidelines.

## 📝 License

This project is for educational purposes as part of the IDATG2208 course.

## 👨‍💻 Author

**Sigurd Riseth**

## 📞 Support

For questions about the assignment, please refer to:
- Course materials and lectures
- Scikit-learn documentation
- Office hours with course instructors

---

**Good luck with your machine learning journey! 🚀**