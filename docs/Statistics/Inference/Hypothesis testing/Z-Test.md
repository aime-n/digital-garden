A **z-test** is a statistical hypothesis test used to determine whether the mean of a sample is significantly different from a known population mean. It's based on the standard normal distribution (also known as the [[z-distribution]]), which has a mean of 0 and a standard deviation of 1. The z-test is commonly used when you have a _large sample size_ (typically n > 30) and when the _population standard deviation is known_.

Here's how a z-test works:

1. **Formulate Hypotheses:** The first step in a z-test is to formulate null (H0) and alternative (Ha) hypotheses. The null hypothesis typically states that there is no significant difference between the sample mean and the population mean, while the alternative hypothesis suggests the presence of a significant difference.

2. **Collect Data:** Gather a sample from the population of interest. Ensure that the sample is random and sufficiently large.

3. **Calculate the Test Statistic (z-score):** The test statistic, also known as the z-score, measures how many standard deviations the sample mean is away from the population mean. The formula for calculating the z-score is:

   $$z = \frac{{\bar{x} - \mu}}{{\sigma / \sqrt{n}}}$$

   - $\bar{x}$ is the sample mean.
   - $\mu$ is the population mean.
   - $\sigma$ is the population standard deviation.
   - $n$ is the sample size.

4. **Determine the [[Critical Region]]:** Choose a significance level (alpha, often set at 0.05) to determine the critical region in the z-distribution. This defines the threshold beyond which the results will be considered statistically significant.

5. **Compare the Test Statistic to [[Critical Value]]:** If the absolute value of the z-score calculated in step 3 falls in the critical region (i.e., exceeds the critical value(s) for the chosen significance level), you reject the null hypothesis. If it falls outside the critical region, you fail to reject the null hypothesis.

6. **Draw a Conclusion:** Based on the comparison in step 5, you draw a conclusion regarding the null hypothesis. Rejecting the null hypothesis suggests that there is a significant difference between the sample mean and the population mean.

Z-tests are commonly used when you have a large enough sample size to rely on the central limit theorem, which states that the distribution of sample means approaches a normal distribution, even if the population distribution is not normal. Z-tests are also used when the population standard deviation is known or when an estimated standard deviation from the sample can be used as an approximation. If the population standard deviation is unknown and the sample size is small, the t-test is typically more appropriate.

# See more
- [[z-distribution]]