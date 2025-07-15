Assignment 4 - Survival Analysis

This project has survival analysis work on a clinical dataset about head and neck cancer patients.

I did three main analyses here:

* Kaplan-Meier survival curves to compare survival between age groups
* Cox Proportional Hazards regression with multiple factors to see how they affect survival
* Random Survival Forest model to predict survival and check feature importance

The notebook main.ipynb has all the code and plots. The data file is in the Data folder.

How to run:

1. Make sure you have Python installed (version 3.8 or higher recommended).
2. Install required packages by running:
   pip install pandas numpy matplotlib lifelines scikit-survival
3. Open main.ipynb in Jupyter Notebook or VS Code and run the cells step-by-step.

This will load the data, run the survival analyses, and show the plots and results.