## About
This repository contains the submission requirements for the EE5907/EE5027 Programming Assignment CA2 task.

## Requirements
The codes are written in **Python 3.6.12** and in **Jupyter Notebook**.

I highly recommend creating a new environment to install the required packages into.
For example, create a new conda environment:
`conda create --name ee5907_ca2 python=3.6`
You could also use virtualenv based on your own preference.

Please install the required packages using the following commands:<br>
`pip install jupyterlab`<br>
`pip install -U scikit-learn`<br>
`pip install libsvm`<br>
`pip install torch===1.6.0 torchvision===0.7.0 -f https://download.pytorch.org/whl/torch_stable.html`<br>
`pip install opencv-python`

## Running the Code
To run the code, simply start up Jupyter Notebook in your terminal.
E.g. After entering the Python environment, type `jupyter-notebook`

"PCA_LDA_GMM_SVM.ipynb" contains codes for Sections 1-4 while "NN.ipynb" contains codes for Section 5 of the PDF report. 
Open the ipynb files from the Jupyter console and the codes should appear.

Please note that the dataset should be saved as per the original format under the folder name "PIE", with subfolders labelled from 1 to 68, and placed in the same folder as the Jupyter Notebook ipynb script.

## Authors
If you need clarifications, please approach [Fiona Tan](tan.f@u.nus.edu).