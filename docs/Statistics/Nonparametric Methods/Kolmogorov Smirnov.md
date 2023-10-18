# Kolmogorov-Smirnov Test Procedure

>[!info] Definition
>The Kolmogorov-Smirnov (K-S) test is utilized for continuous data to test the goodness of fit, determining whether a sample follows a specific distribution.

## **Procedure Steps:**

### **1) Formulate the Hypotheses**
   - **Null Hypothesis ( $H_0$ ):** The sample follows distribution X.
   - **Alternative Hypothesis ( $H_1$ ):** The sample does not follow distribution X.

### **2) Order Data and Construct a Table**
   - Order the data in ascending order.
   - Calculate the Empirical Cumulative Distribution Function (ECDF) and the theoretical CDF.
#### ECDF
![[Cálculo da Distribuição Acumulada Empírica (ECDF)]]
   
   **Columns of the Table:**
   - $x$: Value, ordered from smallest to largest.
   - **Order:** From 1 to the sample size.
   - $Fn(x)$: Order/n (ECDF).
   - $F0(x)$: Theoretical CDF, calculate the integral of the probability density function (pdf).
   - $|F0(x) - Fn(x)|$: $D_n$.
   - $|F0(x) - Fn(x-)|$: Crossed $D_n$.  --> subtrai o Fn da linha anterior



### **3) Find the Maximum Deviation, $d$, Value**
   - Look for $d$, i.e., the maximum value of the last two columns.

### **4) Comparison with Critical Values**
   - Compare the calculated $d$ value with the critical values given in the K-S test table, and identify the $p-value$ range.
   - If the $p-value > 0.05$, we do not reject the null hypothesis $H_0$.

   **Example for Uniform Distribution PDF:**
   - $PDF$: $(x+1)/2$

