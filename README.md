This artifact contains the dataset used in the paper _Does the First-Response Matter for Future Contributions? A Study of First Contributions_.

It comprises of 4 preprocessed dataset as follows:
  * **D1**: contain sentiment, toxicity, and emotion in first response to two groups of contribution:first contributions and of non-first contributions.
  * **D2**: contain sentiment and responsiveness infirst response toward fist contribution in two groups of contributions: contri-butions that the first-time contributors interacted with project contributorsand contributions that the first-time contributors did not interact with projectcontributors. 
  * **D3**: contain statistical samples of negative first response, and distributed them to the coders to manually categorized them.
  * **D4**: contain variables vectors of the first contribution and the target class _future_contribution_ which indicate whether the first-time contributor continue contribute to the particular project or not.
 
sanity_check.csv: Contain data produced from sanity check

Data Filtering.ipynb: the script for data filtering process

Experiment.ipynb: the script for preprocessing data and experiment

We also provide the [deviations](DEVIATIONS.md) of the paper from the plan in [registered reported](https://arxiv.org/abs/2104.02933) 

# Note
The dataset is in \*.csv format in the \*.zip file.
