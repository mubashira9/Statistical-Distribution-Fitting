# Statistical Distribution Fitting

This project explores **statistical data analysis** by fitting a known probability distribution to a given dataset.  
It demonstrates parameter estimation techniques and how to quantify uncertainty using the bootstrap method.

---

## Overview

- Visualize the dataset with a histogram.
- Fit a known probability distribution (e.g., Normal distribution) using **scipy.stats**.
- Estimate distribution parameters using:
  - **Method of Moments (MoM)**
  - **Maximum Likelihood Estimation (MLE)**
- Construct approximate confidence intervals using the **bootstrap method**.

---

## Methods

1. **Histogram:**  
   Visualize the shape of the data to select an appropriate distribution.

2. **Distribution Fitting:**  
   Fit a theoretical distribution to the data and estimate its parameters.

3. **Parameter Estimation:**  
   Compare estimates from the Method of Moments and Maximum Likelihood Estimation.

4. **Bootstrap Confidence Intervals:**  
   Resample the data to compute approximate confidence intervals for the estimated parameters.

---

## How to Run

1. Clone this repository:

   git clone https://github.com/mubashira9/statistical-distribution-fitting.git
   
2. Install dependencies:
   
   pip install -r requirements.txt
   
3. Open the notebook:
   - Run in Google Colab: Open in Colab
   - Or run locally with Jupyter:
        jupyter notebook distribution_fitting.ipynb

---

## Libraries Used

1. numpy
   
3. scipy
   
5. matplotlib
   
7. seaborn

---

## License
This project is open source and free to use for educational purposes.
