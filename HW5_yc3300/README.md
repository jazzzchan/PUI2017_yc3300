## For this homework 5, Yunkun Wan, Yuwen Chang, Unisse Chua and Rachel Lim helped me with building codes, correcting my mistakes and answering confusions

## Assignment 1:
## Goal:
Generate N samples from a distribution of your choice, but not a Gaussian with a chosen mean μ and standard deviation σ: N(μ, σ) and calculate the mean of each sample (all samples should have the same size n).

Assess the validity of the Z-test: If the samples are drawn from the distribution you are testing the z-values you calculate should follow a N(0,1) distribution (a Gaussian with mean 0 and standard deviation 1). Show that the distribution of z -statistics (find the formula in a statistics book or in last week’s slides) that you calculated (one for each sample) is indeed consistent with N(0,1).
## Process:
1. I followed Professor's example from the lecture and write the code based on her example
2. Yukun Wan help me with understanding the question and corrected my code
3. Yuwen Chang explained why for this question our null hypothesis should be the same as our expectation 


## Assignment 2: 
## Goal: 
Test that in fact binomial and Poisson distribution look increasingly more similar to Gaussians as the mean of the distribution increases.
## Process:
1. I followed professor's skeleton for the first part
2. For binomial distribution and poisson distribution narray, I initially used np.arange, which built nparray that contains repeated numbers, Unisse Chua helped with it and corrected it to np.linspace.
3. I followed Yuwen's code on chi-square distribution. 
4. Yuwen explained KL divergence and chi-square, also null hypothesis and results for KS test, AD test, KL and chi-square test, I followed his explanations on four tests(null hypothesis and results)

## Assignment 3: 
## Process:
1. the fourth data (the shoot data, the one was not provided by professor) was provided by Rachel Lim, I followed Unisse Chua's code to download the data from url
2. I followed Yuwen's code to download all the other data.
3. Because at first I dropped na before the tables were merged, and there was index in my csv, the length of my merged table was different from others, therefore I followed Unisse Chua's method, which is dropping columns for each data table first before merging them.
4. I followed both professor's skeleton and Unisse Chua's code for the second part (Plot and interpretation for each plot)
5. I am a bit confused with the third part, i I conducted OLS table, but followed both Unisse Chua's and Yuwen's code for the rest part(Third part) and their interpretation for each model. 
