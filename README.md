# The Predictive Power of Reddit Retail Investor Sentiment for Gold Returns: An Econometric Analysis Using FinBERT

This is the GitHub Repository corresponding to the BSc Thesis *"The Predictive Power of Reddit Retail Investor Sentiment for Gold Returns: An Econometric Analysis Using FinBERT"*.

To showcase the methodology without requiring users to re-run computationally intensive code, the repository contains processed datasets and demonstration files that illustrate each stage of the workflow and how the data is transferred between preprocessing steps.

## workflow

**academic_torrents_data_extraction.ipynb**  
Extracts Reddit data from the `.zst` files obtained through Academic Torrents and prepares the raw dataset for analysis.

**sentiment_analysis.ipynb**  
Contains the full code used for the original research and complete sentiment analysis pipeline.

**test_sentiment_analysis.ipynb**  
Provides a demonstration version of the sentiment analysis workflow. It takes `test_sentiment_dataset.csv` as input and runs the analysis on a smaller subsample of the full `raw_gold_sentiment_data.csv` dataset, allowing users to reproduce the methodology without extensive computational requirements.

## remarks

- `sentiment_analysis.ipynb` contains the complete code used for the thesis research.
- `test_sentiment_analysis.ipynb` is intended for demonstration and reproducibility purposes and operates on a reduced dataset.
- The full `raw_gold_sentiment_data.csv` dataset is substantially larger than the demonstration sample and was used for the final empirical analysis.
- `academic_torrents_data_extraction.ipynb` contains the extraction procedure for Reddit data stored in `.zst` format.
- The Academic Torrents dataset used for data extraction can be found here:  
  https://academictorrents.com/details/3e3f64dee22dc304cdd2546254ca1f8e8ae542b4
- Processed and intermediate datasets are included where appropriate to illustrate preprocessing stages and improve reproducibility without requiring users to repeat the full extraction process.
