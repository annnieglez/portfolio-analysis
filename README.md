# Portfolio Analysis Tech Challenge

This challenge represents a practical tech assignment designed to test skills in portfolio analysis. Portfolio analysis is a systematic way to evaluate investment portfolios to optimize asset allocation and management.

## **Key Objectives:**

- To perform a series of calculations and create visualizations to analyze a set of financial assets.
- Develop the necessary code to accomplish each of these tasks effectively.
- An opportunity to demonstrate ability to apply Python programming skills in a real-world financial context.

## Project Structure

```bash
.
├──  scp                              # Folder containing Python scripts used for preprocessing, analysis and visualization
│    ├── fonts                        # Folder for storing the custom font files used in the visualizations
│    │    └── Montserrat-Regular.ttf  # Custom font Montserrat-Regular
│    ├── __init__.py                  # Marks the 'scripts' directory as a Python package
│    ├── data_check.py                # Script for checking the dataset for inconsistencies or issues
│    ├── data_cleaning.py             # Script for cleaning and preprocessing the dataset (e.g., handling missing data)
│    └── visualization.py             # Script containing functions used in exploratory data analysis (EDA) and visualization
├── .gitignore                        # Specifies files/folders for Git to ignore (e.g., temporary files, credentials)
│    └── node_modules/                # Ignore node_modules directory
│    └── *.log                        # Ignore log files
│    └── __pycache__/                 # Ignore Python bytecode cache
│    └── *.pyc                        # Ignore Python bytecode files
├── *.csv                             # The datasets used for the portfolio analysis
├── README.md                         # The readme file with project overview, objectives, and instructions
├── Tech-Challenge.ipynb                        # Main script to run the project
└── requirements.txt                  # List of Python dependencies required for the project (e.g., pandas, matplotlib, etc.)

```

## How to Run the Project

### 1. Install Dependencies

Before starting, make sure you have all the necessary dependencies installed. You can install them by running the following command in your terminal:

```bash
pip install -r requirements.txt 
```

### 2. **Run the Jupyter Notebook:**

Open `Tech-Challenge.ipynb` in Visual Code and execute the cells sequentially:

```bash
Tech-Challenge.ipynb 
```

## Technologies Used

- Python (Pandas, Matplotlib, Seaborn)
- Visual Studio Code
