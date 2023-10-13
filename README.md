# FMCG-Store-CustomerAnalytics

Customer behavior insights of a Fast Moving Consumer Goods (FMCG) store are extracted and analyzed. After pre-processing the data, Logistic regression (mono and multinominal) was employed to segment the data into 4 clusters and categorize each new customer data. This analysis helps in understanding:

- The purchase probability modeling and its predictive analysis.
- The probability of a (chocolate bar) brand choice and its predictive analysis.
- The purchase quantity modeling and its predictive analysis.

**Dataset information:** All datasets were provided by the 365Datascience training institution.

## Repository Structure

- `data`: Contains datasets used for analysis.
  - `purchase data.csv`: Purchase data.
  - `segmentation data.csv`: Data used for customer segmentation.
  
- `models`: Contains saved models and preprocessing utilities.
  - `kmeans_pca.pickle`: KMeans clustering model post-PCA.
  - `pca.pickle`: PCA model.
  - `scaler.pickle`: Scaler used for data normalization.
  
- `notebooks`: Jupyter notebooks detailing the analysis.
  - `customer_segmentation.ipynb`: Customer segmentation analysis.
  - `purchase-analytics-predictive-analysis-notebook.ipynb`: Predictive analysis on purchase data.

## How to Use
(TBD)

## Dependencies

(TBD)

## Contributing

If you wish to contribute to this repository, kindly raise an issue or submit a pull request.

## License

(TBD)
