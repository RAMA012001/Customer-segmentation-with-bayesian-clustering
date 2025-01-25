# Customer Segmentation Analysis

This notebook implements and compares two clustering models for categorical time series data:
1. **Markov Chain Clustering**
2. **Dirichlet Multinomial Clustering**

The notebook is structured into two main parts:
1. **Simulations on Synthetic Data**: Tests the models on generated data to validate their performance.
2. **Testing on Real Data**: Applies the models to real-world data to analyze and interpret clustering results.

---

## Installation

### Create a virtual environment:
```bash
python -m venv venv
```

### Activate the virtual environment:
- **On Windows**:
  ```bash
  venv\Scripts\activate
  ```
- **On macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### Clone the repository:
```bash
git clone https://github.com/RAMA012001/Customer-segmentation-with-bayesian-clustering
```

### Navigate to the project directory:
```bash
cd favorita-customer-segmentation
```

### Install dependencies:
```bash
pip install -r requirements.txt
```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- **Dataset**: Retail Customer Data on Kaggle.
- **Tools**: Python, Scikit-learn, Matplotlib, Seaborn.
- **Reference**: Pamminger, C. and S. Frühwirth-Schnatter (2010). *Model-Based Clustering of Categorical Time Series*, Bayesian Analysis, 5, 345–368.