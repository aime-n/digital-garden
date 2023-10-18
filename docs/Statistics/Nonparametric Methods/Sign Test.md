---
tags:
  - nonparametric
---
# FISCHER SIGN TEST

- **Data Characteristics:**
   - Continuous
   - Independent
   - Single median equal to the parameter theta

>[!info] Definition
>The Sign Test is a non-parametric statistical method used to analyze the median of a single sample or to compare the medians of two paired samples. 

It’s particularly helpful when the assumptions of parametric tests, like t-tests, are not met (e.g., normality). Below is a comprehensive overview of the Sign Test:

### **Sign Test**

#### **Application:**

- **Single Sample**: Testing whether the median of a single sample is equal to a specified value.
- **Paired Samples**: Testing whether there is a difference in the medians of two paired samples.

#### **Key Concepts:**

- **Data Type:** The test uses ordinal, interval, or ratio data.
- **Null Hypothesis (\(H_0\)):** Assumes no difference in medians or that the median difference is zero.
- **Alternative Hypothesis (\(H_1\)):** Assumes a significant difference in medians or that the median difference is not zero.

#### **Advantages:**

- **Robust:** Less sensitive to outliers and non-normal data.
- **Flexibility:** Suitable for small sample sizes.

#### **Disadvantages:**

- **Sensitivity:** Less powerful than parametric tests like the t-test, meaning it might not detect differences that actually exist.

#### **Example:**

Suppose we are analyzing the effects of a training program by comparing the pre-test and post-test scores of participants.

1. **Hypotheses:**
   - \(H_0: \text{median difference} = 0\)
   - \(H_1: \text{median difference} \neq 0\)

2. **Differences and Signs:**
   - Calculate differences (post-test - pre-test) and assign signs.

3. **Test Statistic:**
   - Count the number of positive differences.

4. **Decision:**
   - Compare the count to a critical value or calculate the p-value to make a decision regarding the null hypothesis.

Using the Sign Test provides a non-parametric alternative to analyze and interpret the central tendency of datasets or the difference between paired datasets.

![[Sign Test - Step by Step]]

