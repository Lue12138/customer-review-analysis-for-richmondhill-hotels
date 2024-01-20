# Customer Review Analysis for Richmond Hill Hotels

## Overview
This project focuses on analyzing customer reviews of hotels in Richmond Hill. The analysis aims to derive insights from review texts using various techniques including sentiment analysis, frequency analysis, mutual information (MI), and pointwise mutual information (PMI).

## Data
The dataset includes hotel reviews with details such as hotel names, rating scores, and review texts.

## Files Description
- `analysis.ipynb`: Jupyter notebook containing the entire analysis workflow.

## Analysis Workflow
1. **Preprocessing:**
   - `hotelDf`: Original dataset.
   - `reviewDF`: Reviews with Vader sentiment scores.
   - `finalDf`: Consolidated data with sentiment scores and one-hot encoded frequent words.

2. **Sentiment Analysis and Aggregation:**
   - Comparison of hotel rankings based on different sentiment analysis methods.

3. **Frequency Analysis:**
   - Analysis of the most frequent words in positive and negative reviews.
   - Generation of word clouds for visual representation.

4. **Mutual Information (MI) and Pointwise Mutual Information (PMI) Analysis:**
   - Examination of MI and PMI to identify significant associations between words and review sentiments.

5. **Visualization:**
   - Various visualizations are used throughout the analysis to illustrate findings, such as bar graphs, word clouds, and scatter plots.

## License
[MIT License](https://opensource.org/licenses/MIT)
