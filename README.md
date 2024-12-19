# 608_presentation

# Pandas vs DuckDB: A Chess Dataset Performance Comparison

This repository contains a Jupyter Notebook that compares the performance of **Pandas** and **DuckDB** on a large chess dataset. The notebook demonstrates various data analysis tasks, highlighting the strengths and limitations of each tool.

---

## **Features**
- Performance comparison of filtering, aggregation, self-joins, and custom calculations.
- Explains the difference between **row-based** (Pandas) and **columnar** (DuckDB) storage.
- Uses a dataset with over **6 million chess games** to test scalability and efficiency.

---

## **Dataset**
The dataset used in this analysis contains information about chess games, including:
- **Event Type**: Type of chess match (e.g., Classical, Blitz).
- **Player Ratings**: Elo ratings for white and black players.
- **Opening**: Opening strategy used in the game.
- **Result**: Outcome of the game.

Due to its large size, the dataset is not directly included in this repository. You can download it from the following link:

[Chess Dataset (Download)](https://www.kaggle.com/datasets/arevel/chess-games/data)

---

## **Contents**
The repository contains the following files:
1. **`608_presentation.ipynb`**:
   - The Jupyter Notebook with all the analysis and performance comparisons.
2. **`row_vs_column_storage.png`**:
   - A diagram explaining the difference between row-based and columnar storage.

---

## **Setup Instructions**
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
   cd YOUR_REPOSITORY
Download the chess dataset from the link provided above and place it in the same folder as the notebook.

Install the required Python libraries:

bash
Copy code
pip install pandas duckdb jupyterlab
Open the Jupyter Notebook:

bash
Copy code
jupyter lab 608_presentation.ipynb
Ensure the dataset (chess_games.csv), notebook, and any images (e.g., row_vs_column_storage.png) are in the same folder.

Run the notebook cell by cell to view the analysis and results.
