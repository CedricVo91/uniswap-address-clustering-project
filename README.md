# Uniswap Ethereum Address Clustering

## Project Overview

This project undertakes the clustering of Ethereum addresses active on Uniswap to categorize them based on trading behavior throughout the 2020-2022 crypto bull run. Utilizing data from Dune Analytics, this analysis aims to differentiate among various trader profiles, from amateur enthusiasts to sophisticated entities such as 'whales' and automated bots.

## Key Insights

- **Trader Classification**: Successful separation of casual and professional traders, followed by the identification of three persistent clusters within the pro trader category.
- **Persistence of Clusters**: Validation of the three pro trader clusters through advanced visualizations such as UMAP and t-SNE.
- **Analytical Techniques**: Extensive EDA leveraging PCA, advanced clustering algorithms, cluster validation methods, and state-of-the-art visualization techniques to refine and substantiate the clustering.

## Methodology

- **K-Means Clustering**: Inspired by Will Price's work, K-means was employed as the primary clustering technique. (Reference: [Clustering Ethereum Addresses](https://towardsdatascience.com/clustering-ethereum-addresses-18aeca61919d))
- **Cluster Validation**: A suite of evaluation metrics (elbow method, silhouette score, Davies-Bouldin score, Calinski-Harabasz score) and comparison with other methods like DBSCAN were used to validate cluster selection.
- **Visualization Techniques**: Implementation of KDE, violin plots, and boxplots, complemented by UMAP and t-SNE for advanced pattern recognition.

## Clustering Approach and Validation

The project begins with a K-means clustering to establish an initial grouping of Ethereum addresses, which is then rigorously validated using various metrics. A secondary level of refinement is applied through advanced visualization tools that confirm the stability and distinctiveness of the identified clusters.

## Results

The analysis has delineated three principal groups among pro traders:

1. **Sustainable Long-term Traders**
2. **Whales**
3. **Bots**

## Data Refinement Impact

Selective exclusion of casual traders and extreme outliers has honed the focus onto professional trading behaviors, enhancing the clarity and relevance of the analysis.

## Future Analysis

The project anticipates an in-depth examination of key players within each pro trader cluster. Investigating Etherscan data and token holdings will provide deeper insights potentially valuable for investment strategies.

## Data Source

Data is sourced from Dune Analytics, the most reputable indexer for Uniswap transaction data, offering the cleanest datasets for DEX transactions during the historic crypto bull run.

## Usage

Set-up instructions and guides for running the project will be made available for those interested in reproducing the analysis or conducting their own exploration.

## Contributions and Acknowledgments

The methodologies employed draw from the insights of Will Price's study on Ethereum address clustering. Contributions to enhance and build upon this analysis are welcomed.

## License

This project is distributed under the [MIT License](LICENSE).

## Contact

For questions or potential collaborations, please reach out through GitHub or the provided email contact.
