## Iris Dataset Analysis
This project involves performing various statistical tests and visualizations on the Iris dataset. Below is a summary of the tests conducted and their results.

# Statistical Tests
# Shapiro-Wilk Test
Test Statistic: 0.9761
p-value: 0.0102
Explanation: This test assesses the normality of the data distribution. Since the p-value is less than 0.05, it indicates that the data significantly deviates from a normal distribution, rejecting the normality assumption.
# D’Agostino’s K^2 Test
Test Statistic: 5.7356
p-value: 0.0568
Explanation: This test evaluates the deviation of the data from a normal distribution. With a p-value near 0.05, it suggests that there may be some deviation from normality, though it is not definitive.
# Anderson-Darling Test
Test Statistic: 0.8892
Critical Values: 0.562 (15%), 0.64 (10%), 0.767 (5%), 0.895 (2.5%), 1.065 (1%)
Explanation: This test checks the fit of the data to a normal distribution. The test statistic is close to the 2.5% significance level critical value, suggesting limited adherence to normal distribution.
# ANOVA (Analysis of Variance)
Sum of Squares: species 63.212, Residual 38.956
Degrees of Freedom: species 2, Residual 147
F Statistic: 119.265
p-value: 1.67e-31
Explanation: ANOVA tests whether the means of different groups are significantly different. The very small p-value indicates that the mean differences among species are statistically significant and not due to random chance.
# t-Test
p-value: 8.9852e-18
Explanation: The t-Test assesses the significance of the mean difference between two groups. The very small p-value suggests that the difference in means is significant and not due to random variation.
# Visualizations
Histograms: Used to understand the distribution of data for each species.
Box Plots: Visualize the median, variance, and outliers across species.
Heatmap: Show relationships and interactions between different variables and species.
![Screenshot 2024-07-30 143950](https://github.com/user-attachments/assets/23179063-3706-438a-9961-ff951cdb5582)
![Screenshot 2024-07-30 143928](https://github.com/user-attachments/assets/5b98245e-c511-450f-a745-7dadd8c7f4fc)
![Screenshot 2024-07-30 143959](https://github.com/user-attachments/assets/1eeb80e8-1b98-4545-9f1a-8e60c1712874)

# Libraries Used
pandas

numpy

scipy

matplotlib

seaborn

# Conclusion
The statistical tests and visualizations performed provide insights into the Iris dataset's distribution and the differences between species. The results offer valuable information for understanding species characteristics and the dataset's overall structure.
