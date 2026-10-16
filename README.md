# Hillview Harmony: Business Analytics model

MQBS3010 Capstone, Group 1I, Macquarie University (2026). Author: Quang, N. (Business Analytics). Client: The King's Foundation.

This repository holds the Python analysis behind Chapter 4 (Business Analytics) of the Hillview Harmony report.

## Read the notebook
- **[Hillview_Harmony_Analytics_Notebook.ipynb](Hillview_Harmony_Analytics_Notebook.ipynb)**: the full analysis with explanations, code, results and Figures 4.1 to 4.6. GitHub displays it directly; results are already saved, so nothing needs to be run.
- [Open in nbviewer](https://nbviewer.org/github/quydkh-cmyk/hillview/blob/main/Hillview_Harmony_Analytics_Notebook.ipynb) if GitHub is slow to render it.
- [Hillview_Harmony_Analytics_Notebook.html](Hillview_Harmony_Analytics_Notebook.html): the same notebook as a web page. Download it and open it in a browser.

## What the notebook does
1. Rebuilds Finance's cost model and checks it reproduces Finance's Year 5 surplus of $203,657.
2. Projects school student-days under Low, Base and High scenarios.
3. Tests one input at a time (sensitivity) and all inputs together (Monte Carlo, 10,000 runs, seed 42).
4. Tests the cost of the heritage and access commitments in the recommendations.
5. Draws Figures 4.1 to 4.6.

## Run it yourself
Python 3.9 or later with `numpy` and `matplotlib`, then run all cells in order (about one minute):

    pip install numpy matplotlib jupyter
    jupyter notebook Hillview_Harmony_Analytics_Notebook.ipynb

No data files are needed. Finance's inputs are typed into the notebook with their sources, and the random seed is fixed.
