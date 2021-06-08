# CREDIT SCORE ENGINE 
### DESIGNED AND DEVELOPED BY JASPREET SINGH DHANI
The Credit Score Engine is based on the concepts of feature representation, clustering and foundations of mathematics and finance. The model considers the given attributes to compute a penalty score which is then normalized in the credit score range to obtain the final result. The implementation has been done in Jupyter Notebook, for better comprehension of code and simultaneous visualizations.

### TECHNOLOGY STACK
ipynb == 0.5.1 is required in order to import the encoded dataframe within the notebooks.
Other modules include the standard Python modules such as numpy, pandas and matplotlib.

# FILES
### main.ipynb:
Accepts the encoded df from prepare_dataset.ipynb in order to compute the downstream tasks of penalty score calculation and credit score generation.

### prepare_dataset.ipynb
Takes the provided financial dataset and analyses for any required preprocessing. This is followed by ordinal encoding the categorical entities and partitioning age values into age groups. 
Using the combination of penalty scores for each considered attribute in the dataset, the overall penalty score is computed in order to be normalized to obtain the final credit score.