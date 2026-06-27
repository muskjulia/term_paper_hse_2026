# term_paper_hse_2026
This repo presents an empirical analysis of Reddit discussions about generative artificial intelligence in video game culture. It is conducted as part of Chapter 3 of the Term Paper titled "Machine learning (artificial intelligence) and modern culture: events and artifacts."

# Project context

This repository is part of a term paper prepared for the HSE University master’s programme Data Analytics and Social Statistics.
The empirical analysis is based on two Reddit datasets:
- post-level dataset;
- comment-level dataset.
The analysis was conducted in Python using Jupyter Notebook.

# Main analysis files
|Filename|Desciption|
| :--- | :---: |
|`Term Paper Mask.ipynb`|	Main Jupyter Notebook with the full empirical analysis, including data loading, cleaning, descriptive statistics, hypothesis testing, visualisations, and robustness checks.|
|`Term Paper Mask.html`|Rendered HTML version of the notebook. This file allows the analysis to be viewed without running the notebook.|

# Input datasets
| Filename | Description |
| :--- | :---: |
| `post-level dataset.csv` | Raw post-level dataset exported from the PostgreSQL database. It contains Reddit post metadata and manually coded variables such as author role, AI stance, AI type, disclosure type, and relevance flag. |
| `comment-level dataset.csv` | Raw comment-level dataset exported from the PostgreSQL database. It contains Reddit comments linked to collected posts, including comment-level AI stance and post-level coding variables. |
