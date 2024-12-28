# Customer Segmentation Analysis

This repository demonstrates customer segmentation using the **E-commerce** dataset. The project applies both frequentist and Bayesian clustering techniques to identify distinct customer groups based on their purchasing behavior. The aim is to provide actionable insights for targeted marketing and improved business strategies.

- **Data Preprocessing**: Handling missing values and standardizing features.
- **Feature Engineering**: Creating Monetary metrics to represent customer behaviors.
- **Frequentist Clustering**: 
  - Implementation of K-Means clustering.
  - Implementation of Gaussian Mixture Model (GMM).
  - Using the Elbow Method to determine the optimal number of clusters.
  - Visualizing cluster properties.
- **Bayesian Clustering**:
  - Employing Bayesian Gaussian Mixture Model (BGMM).
  - Implementation of AMGO (Model-Based Clustering of Categorical Time Series, Pamminger and Frühwirth-Schnatter, 2010).
  - Soft cluster assignments with associated probabilities.


## Installation

1. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
2. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/favorita-customer-segmentation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd favorita-customer-segmentation
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```


## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Dataset: [E-Commerce data](https://www.kaggle.com/datasets/carrie1/ecommerce-data) on Kaggle.
- Tools: Python, Scikit-learn, Matplotlib, Seaborn.
- Reference: Pamminger, C. and S. Frühwirth-Schnatter (2010). Model-Based Clustering of Categorical Time Series, Bayesian Analysis, 5, 345–368.
