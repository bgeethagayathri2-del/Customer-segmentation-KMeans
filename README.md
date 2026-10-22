# Customer Segmentation using K-Means

Groups customers into segments based on annual income and spending score, so a business could target each group differently.

- **Data:** synthetic data of 300 customers, generated in the notebook (not a real dataset)
- **Method:** K-Means clustering, with the number of groups chosen using the elbow method and silhouette score
- **Result:** best k = 4

## Segments found

| Segment | Customers | Avg income (thousands) | Avg spending score |
|---|---|---|---|
| 0 | 120 | 108.5 | 58.7 |
| 1 | 59 | 30.8 | 78.1 |
| 2 | 60 | 45.2 | 11.4 |
| 3 | 61 | 70.4 | 85.7 |

## Conclusion
- **Segment 3** (income 70k, spending 85.7) is the best group: good income and high spending.
- **Segment 0** (income 108.5k, spending 58.7) is the largest group: high earners who spend only moderately, so a business could try offers to get them to spend more.
- **Segment 1** (income 30.8k, spending 78.1) spends a lot for a low income.
- **Segment 2** (income 45.2k, spending 11.4) spends very little.

## How to run
Open `Customer_segmentation.ipynb` in Google Colab and click Run all.
