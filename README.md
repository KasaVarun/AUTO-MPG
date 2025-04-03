# AUTO-MPG
This project investigates causal relationships in the Auto MPG dataset to understand how features like horsepower, weight, and model year influence fuel efficiency (MPG). Using Python, causal inference libraries, and visualization tools, the analysis reveals insights beyond simple correlations.
# Understanding Causality in Auto-MPG Dataset

This project explores causal relationships in the Auto MPG dataset using Python and causal inference tools. The goal is to uncover how various features such as horsepower, weight, and model year causally affect fuel efficiency (measured in miles per gallon - MPG).

## Project Objectives

- Perform exploratory data analysis (EDA) on the Auto-MPG dataset
- Prepare the dataset for causal analysis by handling missing values and outliers
- Apply causal discovery techniques to identify potential cause-effect relationships
- Visualize causal graphs and interpret dependencies
- Use do-calculus or interventional analysis to estimate causal effects

## Tools and Libraries Used

- Python 3.x
- Pandas & NumPy
- Matplotlib & Seaborn
- CausalNex or DoWhy (depending on implementation)
- Scikit-learn

## Dataset

The Auto MPG dataset consists of various car attributes and their corresponding fuel efficiency. Key features include:

- `mpg`: miles per gallon (target variable)
- `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`
- `model year`, `origin`

The dataset is preloaded via seaborn or downloaded from UCI Machine Learning Repository.

## Key Outcomes

- Built a causal graph from data-driven assumptions
- Identified direct and indirect causes influencing `mpg`
- Estimated interventional effects of changing features (e.g., reducing weight on MPG)

## How to Run

1. Clone this repository
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook "Understanding Causality in Auto-MPG.ipynb"
   ```

## Author

**Varun Kasa**  
Master's in Information Systems, Northeastern University  
Email: varunkasa8@gmail.com  
GitHub:  https://github.com/KasaVarun

## License

This project is licensed under the MIT License.
