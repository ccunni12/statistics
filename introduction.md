Introduction and Some Vocabulary
================

Overview
--------

In a new digit world, just about every company in every industry is looking to use their vast amounts of data collected to make educated and target decisions. This has lead to a major shift of companies hiring data analysts and scientist whether it's to develop machine learning models to decide what ads to show a new visitor of their website or to perform statistical tests and report key data points helpful in making business decisions. One common theme in hiring is the need for statistical knowledge. The purpose of this entire git repo is to provide simple and easy interpretations of introductory, intermediate, and advanced applied statistical methods for anyone who needs them - students taking a statistics course, people in industry looking to shift into the data analysis space, data analysis end users in industry who want basis for the analyses they review, etc.

For most, statistics is a difficult and confusing subject to learn. I have taught statistics at the collegiate level to students of non-quantitative backgrounds and to math/engineering majors. I saw one common trend between the two groups: a solid understanding the vocabulary from the very start of the course is vital. Essentially, if you do not get a solid basis of understanding in the distinction between a statistic and a parameter early on in a statistics course you are left with questions like: why are we testing if the mean is 0 - the question literally says it was .2? Whereas .2 may be a statistic calculated by a sample and the point of the problem is to test whether or not that .2 could have just occured by chance if the true average of the population (the parameter) is actually 0.

Thus this first introductory module is meant to teach the definitions and interpretations of the vocabulary commonly used in statistics education and which will be used in all of the modules which follow this one.

Parameter vs Statistic
----------------------

For whatever reason, this is a difficult concept for grasp for most students taking their first statistics course. I myself, stuggled with this very concept and received an F in my first every statistics course as an undergrad (I now have a master of science in statistics and work as a lead statistician).

My definitions are as follows:

**Parameter:** a value that describes the distribution of a variable of some POPULATION which is denoted by a GREEK symbol (*μ*, *σ*, *e**t**c*.); we will probably never actually know the true value of a population parameter because it is unrealistic to be able to measure every single subject in the population

*Example: If we are animal researchers we might wish to know the weight of all black bears in New Jersey forests. Here the POPULATION we are interested in is all black bears in NJ, the variable we care about is the weight of the bears in NJ, and one way we can summarize or DESCRIBE the weight of all black bears in NJ is to average the weights together. This leads to the POPULATION PARAMETER that we would care about being the average (MEAN) weight of all black bears in NJ.*

Statistic: a value that describes the distribution of a variable of a SAMPLE that comes from a POPULATION which is denoted by an ENGLISH letter ($\\bar{x}, \\bar{y}, s^2,$ etc.); we do know the exact value of this number because he actually obtain a sample from the population, collect the measurements for each subject in the sample, and then calculate the statistic from them - the whole point of calculating this value is to make a good guess about

*Example: Building off the bear example above, we would find it extremely difficult to capture and weigh every single bear in the forests of NJ. It would make a lot more sense to capture a SAMPLE of bears, weigh those bears and record their weights, and then release them back into their natural habitats. This way, we can calculate the average (MEAN) of the sample and use that SAMPLE STATISTIC to make an educated guess about what the actual POPULATION MEAN is.*

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:

![](introduction_files/figure-markdown_github/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
