# Spectrum-Aware Debiasing: A Modern Inference Framework with Applications to Principal Components Regression

We share implementation code and data used for numerical experiments for the paper SPECTRUM-AWARE DEBIASING: A MODERN INFERENCE FRAMEWORK
WITH APPLICATIONS TO PRINCIPAL COMPONENTS REGRESSION, available on arxiv https://arxiv.org/pdf/2309.07810.

The implementation code, exact correspondence to each plots in our manuscript, and step-by-step instructions for running the code for reproduction is enclosed in a Jupyter Notebook `code.ipynb`.

The data we used in this study to demonstrate our methodology are all in the public domain, extracted from (i) UCI Machine Learning Repository, (ii) OpenML and (iii) Scikit-Learn's real data repository. We include the data files in a zip file (`data.zip`). We also cite the studies that originally published these data in Section 4.4 and provide more information in Section J.1, Appendix of the Supplementary Material.

To run the code:
1. Decompress `data.zip`
2. Open `code.ipynb` in a Jupyter notebook server
3. Change `datapath` in the first code cell to the dcompressed data folder that contains the following data files: Speech_data.csv, DNA_data.csv, SP500_data.csv, FaceImage_data.csv, Crime_data.csv, attributes.csv.
4. Change `filepath` in the first code cell to preferred location for storing results (i.e. figures)
5. Run code cells in-order (the code cells will install necessary dependencies and define necessary utility functions in the correct order).

For readers' convenience, we also make the notebook accessible through the Google Colaboratory:

https://colab.research.google.com/drive/1deadJjVmF66ZdRzJ2-fGMPVeugfnyX0t?usp=sharing
