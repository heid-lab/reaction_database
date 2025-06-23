
The reaction_database repository includes a collection of reaction datasets. For each dataset, a folder `data`is provided.
Each dataset has a `fullDataset` folder containing the complete dataset, and, where applicable, additional directories for any split strategies not directly supported by the DeepReaction framework.

# Overview of datasets for barrier height predictions
| name | data points | original literature (DOI) | level of theory | type of reaction | unit | coordinates (r/TS/p) | reverse reactions | data storage |
|------|------------|--------------------------|-----------------|------------------|------|-------------------|----------------|-------------|
|rdb7 | 11,926 | [10.1038/s41597-022-01529-6](https://www.nature.com/articles/s41597-022-01529-6) | CCSD(T)-F12/cc-pVDZ-F12 | multiple | kcal/mol | (y/y/y) | yes | |
| rgd1 | 176,898 | [10.1038/s41597-023-02043-z](https://www.nature.com/articles/s41597-023-02043-z) | B3LYP-D3/TZVP | multiple | kcal/mol | (y/y/y) | | [Figshare](https://figshare.com/articles/dataset/model_reaction_database/21066901/6) |
