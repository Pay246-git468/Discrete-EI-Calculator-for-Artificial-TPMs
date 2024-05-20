# Discrete-EI-Calculator-for-Artificial-TPMs
Here is the source codes of the DECAT introduced in the article "Quantify the Causes of Causal Emergence: Critical Conditions of Uncertainty and Asymmetry in Causal Structure"
## Introduction
This project is based on Jupyter Notebook and implements a method to generate artificial Transition Probability Matrices (TPMs) with controllable uncertainty and asymmetry. This is achieved by using three parameters: $n$, $deg\_vector$, and $x$. The project also includes a method to calculate the Effective Information (EI) of the artificial TPMs to measure the numerical conditions of the occurrence of Causal Emergence (CE).
## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
### Prerequisites

The project requires the following environment to be set up:

1. Download Anaconda from the official website.
2. Create a virtual environment named "causal" with Python 3.9 using the following command:
    ```
    conda create --name causal python=3.9
    ```
3. Activate the created virtual environment using the following command:
    ```
    conda activate causal
    ```
4. Install the following packages: jupyter notebook, numpy, matplotlib, scikit-learn, pandas, ipykernel, nbformat==5.10.4, nbconvert==7.16.1 using the following command:
    ```
    pip install jupyter notebook numpy matplotlib scikit-learn pandas ipykernel nbformat==5.10.4 nbconvert==7.16.1
    ```
5. Set the virtual environment as the Jupyter Notebook's kernel and change the kernel to "causal" after launching Jupyter Notebook using the following command:
    ```
    python -m ipykernel install --user --name=causal
    ```
6. If you are unable to connect to the kernel for a long time after changing it, upgrade Jupyter Notebook using the following command:
    ```
    pip install --upgrade jupyter notebook
