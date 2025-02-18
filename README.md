# Apriori Data Mining 

## 📌 Overview

This project demonstrates **Market Basket Analysis** using the **Apriori Algorithm**. The objective is to find frequent itemsets and generate association rules from transactional data, helping businesses understand item relationships and optimize product placements.

## 🚀 Features

- **Implements the Apriori Algorithm** using `apyori` and `mlxtend` libraries.
- **Extracts frequent itemsets** based on support, confidence, and lift metrics.
- **Generates association rules** to uncover relationships between items.
- **Provides visual insights** into top-selling products and their associations.
- **Processes real-world sales data** from CSV files for practical applications.

## 🛠️ Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/apriori-data-mining.git
   cd apriori-data-mining
   ```
2. Install the required Python packages:
   ```sh
   pip install pandas numpy matplotlib apyori mlxtend
   ```

## 📂 Files Included

| File                             | Description                                             |
| -------------------------------- | ------------------------------------------------------- |
| `Apriori_DataMining_Demo.ipynb`  | Jupyter Notebook containing step-by-step implementation |
| `Market_Basket_Optimisation.csv` | Sample dataset used for Market Basket Analysis          |
| `data-2.csv`                     | Additional dataset for advanced analysis                |
| `apriori_rules.csv`              | Extracted rules using `apyori`                          |
| `strong_association_rules.csv`   | Extracted rules using `mlxtend`                         |
| `README.md`                      | Documentation for the project                           |

## 📊 How to Use

1. Open `Apriori_DataMining_Demo.ipynb` in Jupyter Notebook.
2. Run the notebook cells step by step.
3. Visualize **top-selling items and association rules**.
4. Analyze the **output CSV files** containing discovered rules.

## 📈 Example Output

**Top 10 Association Rules (Sorted by Lift):**

| LHS (Antecedent) | RHS (Consequent) | Support | Confidence | Lift |
| ---------------- | ---------------- | ------- | ---------- | ---- |
| Milk, Bread      | Butter           | 0.02    | 0.85       | 4.2  |
| Eggs, Cheese     | Yogurt           | 0.015   | 0.76       | 3.8  |

## 📜 License

This project is licensed under the MIT License.

## 🤝 Contributing

Pull requests are welcome! Feel free to **fork the repository**, enhance the project, and submit a PR.

