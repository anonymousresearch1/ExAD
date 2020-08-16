# ExAD
This is an anonymous repository with reference code for the paper "ExAD: An Ensemble Approach for Explanation-based Adversarial Detection" (under review in Asia CCS 2021).

## Getting Started
- If you wish to directly review the results of our whitebox evaluation,
  - You can view the **Review_whitebox_results.ipynb:** notebook
    - This can be done directly on GitHub. Note: GitHub occasionally does not render jupyter notebooks and asks to reload. In that case, please try reloading or follow the alternatives below.
    - You can access the repository on your local machine and open the notebook in a browser.
  - You can view **Review_whitebox_results.pdf:**, which is the pdf version of **Review_whitebox_results.ipynb:**

- If you wish to run the code, please follow the steps given below.

## Install Dependencies
```
pip install -r requirements.txt
```
The current implementation is tested using Python 3.6 and Keras 2.2.5.

## Download pre-trained detector models and explanations of adversarial examples
Please download the folder from the below link. You will need to place the folder named **data** in the root folder of this repository.
