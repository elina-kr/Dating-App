# Dating App Algorithm A/B Test Analysis

## Overview

This project focuses on analyzing an A/B test conducted to evaluate a new matching algorithm for an online dating application. Users see each other's profiles and can like or dislike them. A mutual like results in a match, allowing users to connect.

The development team introduced a new algorithm aimed at improving the matching process. To test its effectiveness, an A/B test was conducted, dividing users into two groups: Group 0 used the old algorithm, while Group 1 used the new one. My task was to assess whether the new algorithm improved the quality of the service.

## Goals

- Identify key metrics that reflect the quality of the service.
- Statistically compare these metrics between the two groups to determine the impact of the new algorithm.

## Data Description

The dataset includes user interaction logs indicating:
- Which group each user belongs to (Group 0 or Group 1).
- Whether a match occurred (is_match: 0 - no, 1 - yes).

## Metrics for Evaluation

To evaluate which matching algorithm is better, I decided to check several metrics:
- Match-to-no-match ratio.
- User activity (number of likes given).
- Number of matches per user.

## Methodology

1. **Metric Selection:** Identifying relevant metrics for evaluating the quality of the service.
2. **Statistical Analysis:** Conducting statistical tests to compare metrics between the two groups.
   - **Chi-squared test for proportions:** To compare the match rates in each group.
   - **t-test for independent samples:** To compare the average user activity and the average number of matches per user.

## Results

- The match rates in the control and test groups are not equal.
- The average activity in the test and control groups differs.
- The average number of matches in the test and control groups differs.

## Conclusion

Based on the analysis conducted, it is recommended to implement the new matching algorithm for all users as it improved the quality of the service.

## Contact

For any questions or additional information, please contact me at elina8kr@gmail.com.
My LinkedIn: [https://www.linkedin.com/in/elina-krs/](https://www.linkedin.com/in/elina-krs/)

## Key Skills

- Python
- Pandas
- NumPy
- Seaborn
- SciPy
- Statistics
- A/B Testing
- Data Analysis

## Repository Contents

- `Dating_app`: Jupyter notebooks with detailed analysis.
- `reports`: Final analytical report.
