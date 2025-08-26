# What Makes a Classic? Text Analysis of Books

This project analyses a selection of classic and non-classic books from Project Gutenberg to explore linguistic and stylistic differences, with the goal of understanding what might contribute to a book being considered a "classic." The classics chosen are widely labelled as such whereas the non-classics are those often considered 'forgotten' and have significantly less downloads on the Project Gutenberg website.

## Overview

The analysis includes:

- Cleaning and preprocessing text files from Project Gutenberg.
- Calculating metrics such as:
  - Average word length
  - Average sentence length
  - Vocabulary richness (unique and rare words)
  - Dialogue proportion
- Visualising results through bar charts and boxplots.
- Comparing classic books with non-classics to identify patterns in writing style.

## Key Findings

- There are **few noticeable differences between classics and non-classics**, and there is a wide range of metrics across individual books within both categories.  
- Some trends observed in classics that could contribute to popularity:
  - **Shorter sentences** — may make the text easier to read.
  - **Moderate word length and vocabulary richness**.
  - Dialogue patterns vary but are generally accessible.
- Many differences are likely due to **specific author style** rather than category.  

## How to Use

1. Place the text files from Project Gutenberg into the `data` folder, organised into `classics` and `non_classics` subfolders.  
2. Run the `clean_text` function to preprocess each file.  
3. Use the provided scripts to calculate and visualise text metrics.  

## Requirements

- Python 3.x  
- `pandas`  
- `matplotlib`  
- `nltk`  

## Conclusion

The analysis shows that while certain stylistic features may contribute to readability and appeal, the **status of a book as a classic is likely determined by broader cultural and historical factors**, not just linguistic properties.