# Netflix Data Analysis Project

This project analyzes a Netflix movie dataset to explore trends in genres, popularity, vote ratings, and release years. The analysis is performed in a Jupyter Notebook and focuses on extracting meaningful insights from the dataset using Python libraries such as pandas, NumPy, matplotlib, and seaborn.

## Project Overview

The goal of this project is to study the dataset and answer business-style questions such as:

- Which genre appears most frequently?
- Which movies have the highest and lowest popularity?
- Which year contains the most released titles?
- How are vote averages distributed?

## Files in this Project

- `Netflix_data_analysis.ipynb` – main analysis notebook
- `mymoviedb.csv` – dataset used for the analysis
- `movie data analysis project ppt.pptx` – presentation file for the project

## Dataset Description

The dataset contains movie information such as:

- Release date
- Title
- Overview
- Popularity
- Vote count
- Vote average
- Genre
- Original language
- Poster URL

## Tools and Libraries Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- matplotlib
- seaborn

## Data Cleaning and Preparation

The notebook includes steps such as:

- loading the CSV file
- checking for missing values and duplicate records
- converting release dates into usable year-based data
- dropping unnecessary columns
- categorizing vote averages into meaningful labels
- splitting the genre column into individual genre values for analysis

## Key Findings

From the analysis:

- Drama is the most frequent genre in the dataset.
- Spider-Man: No Way Home has the highest popularity score.
- Threads and The United States vs. Billie Holiday have the lowest popularity scores.
- 2020 has the highest number of movies in the dataset.

## How to Run

1. Open the project folder in VS Code or Jupyter Notebook.
2. Launch the notebook `Netflix_data_analysis.ipynb`.
3. Run the cells in order to reproduce the analysis.

## Requirements

Make sure the following Python packages are installed:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Purpose

This project demonstrates data cleaning, exploratory data analysis (EDA), and data visualization using a real-world movie dataset.

## License

This project is for educational and portfolio use.
