# Continuous Distributions

## 1. What is Continuous Distributions?

**Continuous data** is a type of numerical data that refers to the unspecified number of possible measurements between two realistic points.

![MarineGEO circle logo](https://learn.g2.com/hs-fs/hubfs/what%20is%20continuous%20data.jpeg?width=600)

![Alt text](image-1.png)

## 2. Normal Distributions

### 2.1. Definition

**Normal distribution,** also known as the **Gaussian distribution**, is a probability distribution that is symmetric about the mean, showing that data near the mean are more frequent in occurrence than data far from the mean.

In graphical form, the normal distribution appears as a `bell curve`.

![MarineGEO circle logo](https://www.scribbr.de/wp-content/uploads/2023/01/Standard-normal-distribution.webp)

### 2.2. The Empirical Rule

![MarineGEO circle logo](https://www.investopedia.com/thmb/eJXNNmErfqAH6sZrWRxUZi9jcco=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/dotdash_final_Optimize_Your_Portfolio_Using_Normal_Distribution_23-0701d4f1047045a392ba624b68a8b8be.jpg)

### 2.3. Formula

![Alt text](image-2.png)

### 2.4. Calculate in Excel

***Calculate Normal Distribution:***

`NORMDIST(x, mean, standard_dev, cumulative)`

- ***x***: Represents the value for which you want to calculate the normal distribution.
- ***mean***: Denotes the mean or average value of the distribution.
- ***standard_dev***: Indicates the standard deviation of the distribution.
- ***cumulative***: A logical value that determines the type of distribution. If set to TRUE (or omitted), it returns the cumulative distribution function. If set to FALSE, it returns the probability density function.

***Calculate inverse of Normal Distribution***

`= NORMINV (probability, mean, standard deviation)`

### 2.5. Z-score

The **standard normal distribution**, also called the **z-distribution**, is a special normal distribution where the mean is 0 and the standard deviation is 1.

![MarineGEO circle logo](https://www.scribbr.de/wp-content/uploads/2023/01/standard-normal-distribution-example.webp)

![Alt text](image-3.png)

**Z-score**

![Alt text](image-4.png)

## 3. Normal Approximations to Binomial Distributions

![Alt text](image-5.png)

***Example***

![Alt text](image-6.png)

![Alt text](image-7.png)

## 4. Normal Approximations to Poisson Distributions

![Alt text](image-8.png)

***Example***

![Alt text](image-9.png)

## 5. The Central Limit Theorem

The **central limit theorem** states that if you take sufficiently large samples from a population, the samples’ means will be normally distributed, even if the population isn’t normally distributed.

![MarineGEO circle logo](https://www.scribbr.com/wp-content/uploads/2022/07/Central-limit-theorem.webp)

![Alt text](image-10.png)

***Example***

![Alt text](image-11.png)

![Alt text](image-12.png)

![Alt text](image-13.png)

## 6. Continuous Random Variables

![Alt text](image-14.png)

***Example***

![Alt text](image-15.png)

**Expectation and Variance**

![Alt text](image-16.png)

***Example***

![Alt text](image-17.png)

![Alt text](image-18.png)

**Median**

![Alt text](image-19.png)

**Quatiles**

![Alt text](image-20.png)

**Mode**

![Alt text](image-21.png)