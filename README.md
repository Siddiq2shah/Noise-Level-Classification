# Noise-Level-Classification
This repo contains my completed notebook
## Files
- Exercise3.ipynb
- NoiseClassificationTrainingData.csv
- NoiseClassificationTestData.csv

## How to run
1) Open Exercise3.ipynb in Jupyter Notebook / JupyterLab
2) Run all cells top-to-bottom (Kernel -> Restart & Run All)
3) Ensure outputs (printed estimates, plots, counts, risks) are visible before submission

## Notes (matches assignment rules)
- Only numpy, pandas, scipy.stats, matplotlib, mpl_toolkits.mplot3d, seaborn, IPython.display used
- Template structure preserved (only edited [bracketed] text and ### code sections)
- Notebook is submitted fully executed

Loaded training and test datasets and visualized feature distributions to assess class separability

Estimated class-conditional parameters (mean vectors, covariance matrices) and class priors from training data (plug-in estimation)

Implemented a Maximum Likelihood (ML) classifier using only class-conditional likelihoods

Implemented a Maximum A Posteriori (MAP) classifier by incorporating class priors into the decision rule

Implemented a Bayes classifier with a general loss matrix by minimizing expected conditional risk

Compared how ML, MAP, and Bayes decision rules differ conceptually and geometrically

Plotted decision regions for ML, MAP, and Bayes classifiers to visualize the effect of priors and loss

Classified test data using each decision rule

Computed empirical error and expected risk for each classifier

Interpreted results to explain why the Bayes classifier can outperform ML/MAP when misclassification costs are unequal
