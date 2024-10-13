# A/B Testing for Marketing Campaigns

This project analyzes the performance of two marketing campaigns (Control and Test) using A/B testing. The analysis compares key metrics like spend, impressions, website clicks, and purchases to determine the effectiveness of each campaign.

## Datasets

- **Control Group:** Data from the control campaign.
- **Test Group:** Data from the test campaign.

Both datasets include the following columns:
- `Campaign Name`
- `Date`
- `Spend [USD]`
- `# of Impressions`
- `Reach`
- `# of Website Clicks`
- `# of Searches`
- `# of View Content`
- `# of Add to Cart`
- `# of Purchase`

## Analysis Steps

1. **Data Cleaning**: Convert date columns and handle missing values.
2. **Descriptive Statistics**: Summary statistics for both control and test campaigns.
3. **Exploratory Data Analysis (EDA)**: Visualizations of key metrics, such as spend, clicks, and purchases.
4. **A/B Testing**: T-tests for statistical comparison of metrics between control and test campaigns.
5. **ROI and Conversion Rates**: Calculation of conversion rates and return on investment (ROI).
6. **Final Recommendation**: Based on the analysis, the script outputs the more effective campaign.

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- scipy
- numpy

