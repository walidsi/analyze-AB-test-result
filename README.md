# Analyze A/B Test Result

![Contributors](https://img.shields.io/github/contributors/walidsi/analyze-AB-test-result?style=plastic)
![Forks](https://img.shields.io/github/forks/walidsi/analyze-AB-test-result)
![Downloads](https://img.shields.io/github/downloads/walidsi/analyze-AB-test-result/total)
![Stars](https://img.shields.io/github/stars/walidsi/analyze-AB-test-result)
![Licence](https://img.shields.io/github/license/walidsi/analyze-AB-test-result)
![Issues](https://img.shields.io/github/issues/walidsi/analyze-AB-test-result)


### Goal
A/B tests are very commonly performed by data analysts and data scientists. This project aims to understand the results of an A/B test run by an e-commerce website. The goal is to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

### Dataset


### Process

### Summary of Findings
My analysis approach tested our hypothesis that the new page design does not provide an improvement in conversion rate over the old page design. I tested our hypothesis using two statistical methods, namely sampling distribution and using logistic regression. Interpreting the results from both approaches did not provide any evidence against the null hypothesis in favor of the alternate hypothesis. Hence our recommendation is to continue to use the current page design and not the new page design.

### Install
This project requires **Python 3.x** and the following Python libraries installed:
- [NumPy](http://www.numpy.org)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org)
- [statsmodels](https://www.statsmodels.org)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Code
Code is provided in the `Analyze_ab_test_results_notebook.ipynb` notebook file.

### Run
In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
ipython notebook Analyze_ab_test_results_notebook.ipynb
```  
or
```bash
jupyter notebook Analyze_ab_test_results_notebook.ipynb
```

This will open the iPython Notebook software and project file in your browser.


