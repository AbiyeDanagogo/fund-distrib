# fund-distrib

This package contains an implementation of two of the fundamental distributions widely used in statistics the Gaussian and Binomial distribution created by me for the AWS Machine Learning Foundations Program by Udacity. The package is available on Test Pypi from the following link https://test.pypi.org/project/fund-distrib/ .

The Gaussian distribution commonly referred to as the normal distribution is often used in the natural and social sciences to represent real-valued random variables whose distributions are not known. Their importance is partly due to the central limit theorem. It states that, under some conditions, the average of many samples (observations) of a random variable with finite mean and variance is itself a random variable—whose distribution converges to a normal distribution as the number of samples increases. In this package, all Gaussian classes have a mean and standard deviation

The Binomial distribution describes the number of positive outcomes in binary experiments, and it is the “parent” distribution from which other distributions like the Gaussian can be obtained. In this package, all objects made from the Binomial class have a mean, standard deviation, n(size), and p(probability of success).

# Installation

pip install --index-url https://test.pypi.org/simple/ fund-distrib

# Usage

```python
  
  # Creates a Gaussian object with mean 5 and standard deviation 3
  gaussian_one = Gaussian(5, 3)
  
  # Returns the mean of the Gaussian object which is 5
  gaussian_one.mean
  
  # Returns the standard deviation of the Gaussian object which is 3
  gaussian_one.stdev
  
  # Adding two Gaussian objects returns a new Gaussian object with mean 7 and standard deviation of 3.16
  gaussian_one + Gaussian(2, 1)
  
```

