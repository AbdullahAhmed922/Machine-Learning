# 📊 Machine Learning — Linear Regression

A hands-on machine learning project exploring **Linear Regression** using scikit-learn. It includes two Jupyter notebooks that walk through the fundamentals—from fitting a simple line to predicting real-world salaries.

## 🗂️ Project Structure

```
Machine Learning/
├── notebook/
│   ├── data/
│   │   └── salary_dataset.csv      # Salary vs. Years of Experience (30 samples)
│   ├── notebook1.ipynb              # Simple Linear Regression (synthetic data)
│   └── notebook2.ipynb              # Salary Prediction (real-world dataset)
├── .python-version
├── pyproject.toml
├── uv.lock
└── README.md
```

## 📓 Notebooks

### Notebook 1 — Simple Linear Regression (Synthetic Data)

Fits a `LinearRegression` model on a hand-crafted dataset to learn the relationship `y = 2x − 1`, then predicts a value for `x = 20`.

- **Input:** `xs = [-1, 0, 1, 2, 3, 4, 5]`, `ys = [-3, -1, 1, 3, 5, 7, 9]`
- **Learned:** slope = 2, intercept = −1
- **Prediction:** `y(20) = 39`

### Notebook 2 — Salary Prediction (Real-World Data)

Uses a CSV dataset of **Years of Experience vs. Salary** (30 records) to train a linear regression model and derive the salary equation.

- **Dataset:** `salary_dataset.csv` — features: `YearsExperience`, target: `Salary`
- **Learned equation:** `Salary = 9449.96 × YearsExperience + 25792.20`
- **Example prediction:** 12 years of experience → **\$139,191.75**

## ⚙️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.13** | Runtime |
| **NumPy** | Numerical arrays |
| **pandas** | Data loading & manipulation |
| **scikit-learn** | Machine learning models |
| **Jupyter / IPyKernel** | Interactive notebooks |
| **uv** | Dependency & environment management |

## 🚀 Getting Started

### Prerequisites

- [Python 3.13+](https://www.python.org/downloads/)
- [uv](https://docs.astral.sh/uv/) (recommended) or pip

### Installation

```bash
# Clone the repository
git clone <your-repo-url>
cd "Machine Learning"

# Create the virtual environment and install dependencies
uv sync

# Launch Jupyter
uv run jupyter notebook
```

Then open `notebook/notebook1.ipynb` or `notebook/notebook2.ipynb` to run the cells.

## 📄 License

This project is for educational purposes as part of an AI / ML course.

## ✍️ Author

**Abdullah Ahmed** — [abd1962964@gmail.com](mailto:abd1962964@gmail.com)

