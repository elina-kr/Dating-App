# Final Report on A/B Test of Matching Algorithm for Dating App

## Introduction

The purpose of this analysis was to determine whether the new profile matching algorithm improved the quality of service in an online dating application. An A/B test was conducted where users were divided into two groups: one using the old algorithm and the other using the new one.

## Data Description

The dataset includes logs of user interactions, indicating which group each user belongs to (Group 0 or Group 1) and whether a match occurred (is_match: 0 - no, 1 - yes).

## Evaluation Metrics

The following metrics were chosen to assess the effectiveness of the new algorithm:
- Match-to-non-match ratio.
- User activity (number of likes given).
- Matches per user.

## Methodology

1. **Metric Selection:** Identifying relevant metrics for evaluating service quality.
2. **Statistical Analysis:** Conducting statistical tests to compare metrics between the two groups.
   - **chi-squared test for proportions:** Comparing match proportions in each group.
   - **t-test for independent samples:** Comparing average user activity and average matches per user.

## Results

- **Match-to-non-match Ratio:** Proportions in the control and test groups are not equal.
- **User Activity:** Average activity differs between the test and control groups.
- **Matches per User:** Average number of matches differs between the test and control groups.

## Conclusion

Based on the analysis, it is recommended to implement the new profile matching algorithm for all users, as it has improved the quality of service.

## Contact

For any questions or additional information, please contact me at elina8kr@gmail.com
or connect via https://www.linkedin.com/in/elina-krs/
