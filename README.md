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

[Chess Dataset (Download)]([Chess Dataset (Download)](YOUR_DATASET_LINK_HERE))

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
