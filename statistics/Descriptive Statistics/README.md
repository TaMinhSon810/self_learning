# DESCRIPTIVE STATISTICS
## 1. Mean
**Mean** is the average of the given numbers and is calculated by dividing the sum of given numbers by the total number of numbers. 

``Mean = (Sum of all the observations/Total number of observations)``

- **Sample Mean**: an average of a set of data. The ***sample mean*** can be used to calculate the central tendency, standard deviation and the variance of a data set.

- **Population means**: the mean or average of all values in the given population. It is calculated by the sum of all values in the population

![MarineGEO circle logo](https://www.onlinemathlearning.com/image-files/population-mean.png)

**Example**: 
What is the mean of 2, 4, 6, 8 and 10?

***Solution:***
2 + 4 + 6 + 8 + 10 = 30

Mean = 30/5 = 6

## 2. Median
**Median** is the middle value of a set of data. To determine the median value in a sequence of numbers, the numbers must first be arranged in ascending order:

- `If there is an odd amount of numbers`, the median value is the number that is in the middle, with the same amount of numbers below and above.
- `If there is an even amount of numbers in the list`, the median is the average of the two middle values.

![MarineGEO circle logo](https://cdn1.byjus.com/wp-content/uploads/2022/10/Median.png)

**Example**:

![MarineGEO circle logo](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Finding_the_median.png/1200px-Finding_the_median.png)

**Median of grouped data** is the middle value of the data that is arranged in ascending order and written in a continuous manner. The data is in the form of a frequency distribution table that divides the higher level of data from the lower level of data.

![MarineGEO circle logo](https://media.geeksforgeeks.org/wp-content/uploads/4-min-1-1.png)

**Example**:

![MarineGEO circle logo](https://www.statology.org/wp-content/uploads/2022/02/modefreq1-300x270.jpg)

**Solution**:

In this example, there are N = 40 total values. Thus, the median value lies in the class where 40/2 = 20 is located. The 20th largest value would be located in the 71-80 class.

Knowing this, we can calculate the following values:

`L: Lower limit of median class:` 71
`W: Width of median class:` 9
`N: Total Frequency:` 40
`C: Cumulative frequency up to median class:` 12
`F: Frequency of median class:` 15
We can plug these values into the formula to calculate the median of the distribution:

**Median** = L + W[(N/2 – C) / F]

**Median** = 71 + 9[(40/2 – 12) / 15]

**Median** = 75.8

We estimate that the median exam score is 75.8.

## 3. Mode
**Mode** is the value that appears most frequently in a data set. A set of data may have one mode, more than one mode, or no mode at all.

**Example:** 
In the given set of data: 2, 4, 5, 5, 6, 7, the mode of the data set is 5 since it has appeared in the set twice.

## 4. Quantiles, Range and IQR

### 4.1. Quantiles

**Quantiles** are values that split sorted data or a probability distribution into equal parts. In general terms, a q-quantile divides sorted data into q parts. The most commonly used quantiles have special names:

- `Quartiles (4-quantiles)`: Three quartiles split the data into four parts.

- `Deciles (10-quantiles)`: Nine deciles split the data into 10 parts.

- `Percentiles (100-quantiles)`: 99 percentiles split the data into 100 parts

**Quartiles** are a type of percentile. A percentile is a value with a certain percentage of the data falling below it. In general terms, k% of the data falls below the kth percentile:

- `The first quartile (Q1, or the lowest quartile)` is the 25th percentile, meaning that 25% of the data falls below the first quartile.

- `The second quartile (Q2, or the median)` is the 50th percentile, meaning that 50% of the data falls below the second quartile.

- `The third quartile (Q3, or the upper quartile)` is the 75th percentile, meaning that 75% of the data falls below the third quartile.

![MarineGEO circle logo](https://www.scribbr.com/wp-content/uploads/2022/05/Quartile-example.webp)

### 4.2. Range and IQR

**Range** measures the difference between the minimum value and the maximum value in a dataset.

`Range = Max - Min`

**Interquartile range (IQR)** measures the difference between the first quartile (25th percentile) and third quartile (75th percentile) in a dataset. This represents the spread of the middle 50% of values

`IQR = Q3 – Q1`


![MarineGEO circle logo](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/interquartile-range-formula-1623222903.png)

## 5. Standard Deviation and Variance

### 5.1. Standard Deviation

**Standard Deviation** is a statistic that measures the dispersion of a dataset relative to its mean and is calculated as the square root of the variance.

![MarineGEO circle logo](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/standard-deviation-1626765925.png)


![MarineGEO circle logo](https://d138zd1ktt9iqe.cloudfront.net/media/seo_landing_files/standard-deviation-formula-1626765976.png)

### 5.2. Variance

**Variance** is the measure of how notably a collection of data is spread out

![MarineGEO circle logo](https://www.investopedia.com/thmb/_hIorwcVnDj-oKWhpTu_qnuUldM=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/Variance-TAERM-ADD-Source-464952914f77460a8139dbf20e14f0c0.jpg)

***Formula***

![MarineGEO circle logo](https://media.geeksforgeeks.org/wp-content/uploads/20230605183401/Variance-formula.png)

## 6. Coefficient of Variation

**Coefficient of variation (CV)** is a statistical measure of the dispersion of data points in a data series around the mean.

**Coefficient of variation (CV)** is a statistical measure of the dispersion of data points in a data series around the mean.

***Formula***

![MarineGEO circle logo](https://cdn.corporatefinanceinstitute.com/assets/coefficient-of-variation1.png)

## 7. Skew and Kurtosis

### 7.1. Skew

**Skewness** is a measurement of the distortion of symmetrical distribution or asymmetry in a data set:
- ***A left-skewed distribution*** has a long left tail. Left-skewed distributions are also called negatively-skewed distributions. That’s because there is a long tail in the negative direction on the number line. The mean is also to the left of the peak.
- ***A right-skewed distribution*** has a long right tail. Right-skewed distributions are also called positive-skew distributions. That’s because there is a long tail in the positive direction on the number line. The mean is also to the right of the peak.

![MarineGEO circle logo](https://www.statisticshowto.com/wp-content/uploads/2014/02/pearson-mode-skewness.jpg)

A distribution can have right (or positive), left (or negative), or zero skewness. A right-skewed distribution is longer on the right side of its peak, and a left-skewed distribution is longer on the left side of its peak:

![MarineGEO circle logo](https://www.scribbr.com/wp-content/uploads/2022/05/Skewness-of-a-distribution.webp)

### 7.2. Kurtosis

**Kurtosis** is a statistical measure used to describe the degree to which scores cluster in the tails or the peak of a frequency distribution.

The peak is the tallest part of the distribution, and the tails are the ends of the distribution.

There are **three** types of kurtosis: mesokurtic, leptokurtic, and platykurtic:

- ```Mesokurtic (Kurtosis = 3.0)```: Distributions that are moderate in breadth and curves with a medium peaked height.

- ```Leptokurtic (Kurtosis > 3.0)```: More values in the distribution tails and more values close to the mean (i.e., sharply peaked with heavy tails)

- ```Platykurtic (Kurtosis < 3.0)```: Fewer values in the tails and fewer values close to the mean (i.e., the curve has a flat peak and has more dispersed scores with lighter tails).

![MarineGEO circle logo](https://www.simplypsychology.org/wp-content/uploads/Kurtosis.gif)

There exists one more method of calculating the kurtosis called **excess kurtosis**. As kurtosis is calculated relative to the normal distribution, which has a kurtosis value of 3, it is often easier to analyse in terms of **excess kurtosis**.

```Excess Kurtosis = Kurtosis - 3```

## 8. Correlation

**Correlation** is a statistical measure that expresses the extent to which two variables are linearly related (meaning they change together at a constant rate).

**Correlations** are used in advanced portfolio management, computed as the correlation coefficient, which has a value that must fall between -1.0 and +1.0.

![MarineGEO circle logo](https://www.simplypsychology.org/wp-content/uploads/correlation.jpg)

