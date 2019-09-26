# HW3

#### 1. (4 points)
\emph{From Lohr Exercise 2.10} Which of the following SRS designs will give the most precision (smallest variance) for estimating the population mean? Assume that each population has the same value of the population variance $S^2$. Please report the variance of the estimator for each scenario as a function of $S^2$ and then state which is the smallest.

1. An SRS of size 400 from a population of size 4000
2. An SRS of size 30 from a population of size 300
3. An SRS of size 3000 from a population of size 300,000,000


#### 2. 
Using the bird data set from Lab 2, a SRS sample of size 15 grid squares has been drawn for you. 
```{r}
birds <- read.csv('http://math.montana.edu/ahoegh/teaching/stat446/birdsurvey.csv', header = T)
set.seed(09252019)
sample_values <- sample(birds$bird.counts, size = 20)
```

##### a. (4 points)
Compute an estimate of the _total_ number of birds across the entire region composed of 200 grid squares.

##### b. (4 points)
Using the FPC compute the variance of the estimator for the population total.

##### c. (4 points)
Construct a 95\% confidence interval for the population total.

##### d. (4 points)
Discuss the similarities and differences for calculating uncertainty in our point estimates between this approach and the repeated sampling procedure from Lab 3.
